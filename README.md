# Atividade Teórica 01 - Documentação da API REST

  <img width="500" height="241" alt="image" src="https://github.com/user-attachments/assets/f31ebd0f-4ae3-4830-8f29-3168bc33cc83" />


# 1.1) O que é uma API? Expliquem a sigla, pra que serve, por que é importante. Tentem usar uma analogia do dia a dia.

  # 🔌 O que é uma API?

### 📜 A Sigla
> **API** é a sigla para *Application Programming Interface*, ou em português, **Interface de Programação de Aplicações**.

---

### 🚀 Para que serve?
É um conjunto de **regras, protocolos e ferramentas** que funciona como uma **ponte ligando diferentes sistemas**, programas ou aplicativos.

💡 Ao invés dos aplicativos precisarem entender todo o funcionamento interno um do outro, a API define **padrões, caminhos e regras** para uma interação segura. Assim, os aplicativos solicitam dados ou serviços sem acessar diretamente o código interno alheio.

---

### 🌟 Por que é importante?
- ✅ Permitem a **conexão segura** entre diferentes plataformas.
- ✅ Essenciais para **redes sociais** e **apps de entrega** (iFood, Uber, etc).
- ✅ Facilitam o desenvolvimento de novos sistemas e **economizam tempo**.
- ✅ Permitem que empresas criem soluções **conectadas entre si**.

---

### 🏦 Analogia do Dia a Dia: O Caixa Eletrônico
*Imagine que você está em um **caixa eletrônico** para sacar dinheiro.*

Você não precisa entender como o sistema do banco funciona ou como as notas são contadas. Você apenas:
1. 💳 **Insere o cartão**
2. 🔢 **Digita a senha**
3. 💵 **Pede o valor**

> 🎯 O **caixa eletrônico atua como uma API**: ele é o intermediário que recebe o seu pedido, leva ao banco e traz o resultado!


<img width="1814" height="867" alt="image" src="https://github.com/user-attachments/assets/ad71ec97-10e5-4007-9ffe-41ebdd132a9f" />



# 🌐 1.2) O que é REST? O que é uma API REST?

## 📑 O que é REST?
**REST** é a sigla para *Representational State Transfer* (Transferência de Estado Representativo). 

Não é uma linguagem, mas sim um **conjunto de padrões** usados para organizar a comunicação entre sistemas na internet. Imagine o REST como um "manual de etiqueta" ou um **modelo de arquitetura** que ajuda os aplicativos a trocarem informações de maneira:
* ⚡ **Simples**
* 🚀 **Eficiente**
* 🌐 **Padronizada** (utilizando o protocolo HTTP)

---

## 🛠️ O que é uma API REST?
Uma **API REST** é aquela que segue fielmente os princípios do modelo REST. Ela organiza a conversa entre sistemas através de "endereços" específicos.

### 📍 Endpoints e Ações
A comunicação acontece por meio de URLs chamadas **endpoints**. Cada um representa algo real no sistema (usuários, produtos, pedidos). Para interagir com eles, usamos os "verbos" do HTTP:

| Método | Ação | Descrição |
| :--- | :--- | :--- |
| 🔍 **GET** | Buscar | Retorna informações de um recurso. |
| ✨ **POST** | Criar | Adiciona novos dados ao sistema. |
| 🔄 **PUT** | Atualizar | Altera informações que já existem. |
| 🗑️ **DELETE** | Remover | Exclui um dado do sistema. |

---

## 🌟 Por que elas são tão populares?
> As APIs REST são as queridinhas dos desenvolvedores porque são **universais**. Elas funcionam com qualquer linguagem de programação e facilitam absurdamente a integração entre sites, apps e serviços na nuvem. ☁️

---

## 📦 Analogia: O Serviço de Entregas
Para entender o fluxo de uma API REST, pense em um **Serviço de Entregas**:

1.  **O Pedido:** O cliente (Sistema A) faz um pedido usando um **endereço específico** e informa o que quer realizar (Ação).
2.  **O Entregador:** Segue as regras (Protocolo) para buscar ou entregar o pacote corretamente.
3.  **A Resposta:** Em uma API REST, o sistema faz o "pedido" para a URL, usa o método (GET, POST, etc.) e recebe uma **resposta organizada**.

---
<p align="center">
  <i>"Comunicação rápida, clara e fácil de manter! 🚀"</i>
</p>

<img width="500" height="333" alt="image" src="https://github.com/user-attachments/assets/c1d4ac3c-3974-40b8-b4ec-6078d1d7b14b" />


# 1.3) O que é CRUD?


## 🧬 O que é CRUD?
A sigla **CRUD** representa as quatro operações fundamentais que qualquer sistema de gerenciamento de dados precisa realizar. Se você usa uma rede social, um banco ou um e-commerce, você está fazendo operações CRUD o tempo todo!

---

## 🛠️ As 4 Operações Básicas
Cada letra da sigla corresponde a uma ação vital dentro do sistema:

* ✨ **[C] Create** (Criar): Quando você posta uma foto ou cria um cadastro.
* 📖 **[R] Read** (Ler): Quando você visualiza seu feed ou busca um produto.
* 🔄 **[U] Update** (Atualizar): Quando você edita seu perfil ou altera uma senha.
* 🗑️ **[D] Delete** (Deletar): Quando você exclui um comentário ou encerra uma conta.

---

## 🔌 CRUD vs. Métodos HTTP
Em **APIs REST**, conectamos cada letra do CRUD a um "verbo" do protocolo HTTP para que o servidor entenda exatamente o que queremos fazer:

| Letra | Operação | Método HTTP | Comportamento |
| :---: | :--- | :--- | :--- |
| **C** | **Create** | `POST` | Envia novos dados para a API para criar um registro. |
| **R** | **Read** | `GET` | Busca ou visualiza dados já armazenados. |
| **U** | **Update** | `PUT` / `PATCH` | **PUT:** Substitui tudo. | **PATCH:** Altera só um pedaço. |
| **D** | **Delete** | `DELETE` | Remove permanentemente uma informação do sistema. |

---

## 💡 Observação Importante: PUT vs. PATCH
> 🛠️ **Dica de mestre:** > Imagine que você quer mudar a cor de uma parede da sua casa.
> - O **PUT** seria como derrubar a parede e construir uma nova com a cor diferente. 🧱
> - O **PATCH** seria apenas passar o pincel e pintar a cor nova por cima da existente. 🖌️

---
<p align="right">
  <i>Dominar o CRUD é o primeiro passo para construir aplicações robustas! 🚀</i>
</p>
<img width="612" height="408" alt="image" src="https://github.com/user-attachments/assets/3b32a5f5-76bb-4877-9259-a1195381416c" />

# 🌍 O Protocolo HTTP e os Status Codes

#1.4) O que é HTTP e o que são status codes? Expliquem o protocolo de forma simples. Façam uma tabela com pelo menos 6 status codes incluindo obrigatoriamente 200, 201, 400, 404 e 500. Para cada um: nome, significado, e quando aparece no nosso projeto.

## 🛰️ 1.4) O que é HTTP?
O **HTTP** (*HyperText Transfer Protocol ou Protocolo de Transferência de Hipertexto*) é o "idioma oficial" da internet. Ele é o protocolo responsável pela comunicação entre **Clientes** (seu navegador ou celular) e **Servidores** (onde os dados estão guardados).

Imagine o HTTP como o **sistema de correios** da web: ele define as regras de como as cartas (informações) devem ser endereçadas, enviadas e entregues para que todo mundo se entenda. 📮

---

### 🔄 Como funciona o fluxo? (Passo a Passo)
1. 👤 **Usuário:** Acessa um site ou app.
2. 📨 **Navegador:** Envia uma **Requisição HTTP** para o servidor.
3. ⚙️ **Servidor:** Recebe, processa e prepara a resposta.
4. 📦 **Resposta:** Os dados chegam e a página aparece na sua tela!

---

## 🔢 O que são Status Codes?
Sempre que o servidor responde, ele envia um **código numérico**. Esses são os **Status Codes**. Eles servem para dizer rapidamente o que aconteceu com o seu pedido, sem que você precise ler todo o conteúdo da resposta.

### 📋 Tabela 

| Código | Nome | Significado | 🛠️ No nosso Projeto |
| :--- | :--- | :--- | :--- |
| <img src="https://img.shields.io/badge/-100-blue"><img width="750" height="600" alt="image" src="https://github.com/user-attachments/assets/94a81e0b-02f1-461e-b17e-2a36bbcba7c9" />| **Continue** | O servidor recebeu o início do pedido. | O ESP32 envia o cabeçalho e aguarda a confirmação para mandar o restante dos dados. |
| <img src="https://img.shields.io/badge/-200-green"> <img width="750" height="600" alt="image" src="https://github.com/user-attachments/assets/760a5ed8-d0a5-4e92-bac3-42d9e21f5552" />| **OK** | Requisição realizada com sucesso! ✅ | Quando o GET retorna os dados de temperatura e umidade. |
| <img src="https://img.shields.io/badge/-201-green"><img width="750" height="600" alt="image" src="https://github.com/user-attachments/assets/0b673e42-20b7-4b67-9e46-296079d19611" />| **Created** | Novo recurso criado com sucesso! ✨ | Quando o ESP32 envia um POST e salva uma nova leitura. |
| <img src="https://img.shields.io/badge/-204-brightgreen"><img width="750" height="600" alt="image" src="https://github.com/user-attachments/assets/4f351e9d-c30b-4d54-be24-cbaa641bb240" />| **No Content** | Processado sem retorno de corpo. | Após deletar um registro de log antigo com sucesso, a API confirma sem enviar texto. |
| <img src="https://img.shields.io/badge/-301-yellow"><img width="750" height="600" alt="image" src="https://github.com/user-attachments/assets/ae3ff610-49b3-4f43-adf0-e49fb59faa93" />| **Moved Perm.** | Recurso mudou de lugar permanentemente. | Se a URL da nossa API mudar definitivamente de `/api` para `/v1`. |
| <img src="https://img.shields.io/badge/-302-yellow"><img width="750" height="600" alt="image" src="https://github.com/user-attachments/assets/d86b9ac2-216e-4780-ab9b-5cad8f177f13" />| **Found** | Mudança temporária de endereço. | Se redirecionarmos o ESP32 para um servidor de testes durante uma manutenção rápida. |
| <img src="https://img.shields.io/badge/-400-orange"><img width="750" height="600" alt="image" src="https://github.com/user-attachments/assets/a04008e2-b202-4dd6-91c3-6db53973eee5" />| **Bad Request** | Erro na requisição ou dados inválidos. ⚠️ | Quando enviamos dados de temperatura no formato errado. |
| <img src="https://img.shields.io/badge/-401-orange"><img width="750" height="600" alt="image" src="https://github.com/user-attachments/assets/d07ddee8-3c81-47d3-b9f0-195edad32fc2" />| **Unauthorized** | Falta de autorização/login. 🔑 | Caso a API passe a exigir uma senha de acesso no futuro. |
| <img src="https://img.shields.io/badge/-402-orange"><img width="750" height="600" alt="image" src="https://github.com/user-attachments/assets/1128c841-2a2e-4930-8936-350eb75ae2ae" />| **Forbidden** | Sem permissão de acesso. | O dispositivo está autenticado, mas tenta acessar dados de um setor que ele não tem permissão. |
| <img src="https://img.shields.io/badge/-404-orange"><img width="750" height="600" alt="image" src="https://github.com/user-attachments/assets/2e5e2e8e-86a4-417f-8c0f-00a33a71c328" />| **Not Found** | Caminho ou rota não encontrada. 🔍 | Ao tentar acessar uma URL que não existe na nossa API. |
| <img src="https://img.shields.io/badge/-500-darkred"><img width="750" height="600" alt="image" src="https://github.com/user-attachments/assets/253290bf-419f-461c-bb2b-e8c9eec22fb4" />| **Server Error** | Deu problema no motor do servidor! 🔥 | Quando há um erro no código da API ou falha interna. |
| <img src="https://img.shields.io/badge/-502-darkred"><img width="750" height="600" alt="image" src="https://github.com/user-attachments/assets/a9b95446-61b3-4d0b-92e6-3bf1ceb6ec7d" />| **Bad Gateway** | Falha na ponte entre servidores. | O servidor principal (Gateway) não recebeu resposta do servidor que roda o código da API. |
| <img src="https://img.shields.io/badge/-503-darkred"><img width="750" height="600" alt="image" src="https://github.com/user-attachments/assets/f731b993-de7c-4aed-b434-248d925686ce" />| **Service Unav.** | Servidor temporariamente fora do ar. | A API está em manutenção ou o servidor caiu por excesso de requisições dos sensores. |
| <img src="https://img.shields.io/badge/-504-darkred"><img width="750" height="600" alt="image" src="https://github.com/user-attachments/assets/663015aa-9a86-4fd8-b4eb-91e40af129de" />| **Gateway Timeout** | Tempo de resposta esgotado. | A API demorou muito para salvar os dados e a conexão do ESP32 "expirou". |

---

---

---

# 📂 Categorias de Status Codes (Cheat Sheet💩)

Para facilitar a vida do desenvolvedor, os códigos são agrupados em 5 grandes "famílias". Cada uma começa com um número específico que já indica o que aconteceu:

---

### 🔵 1xx: Informativa (Provisória)
> **Significado:** *"Aguarde, estou trabalhando nisso."* ⏳

Indica que a solicitação foi recebida e o processo continua. O servidor ainda não enviou a resposta final, mas está processando.
* **Exemplo Comum:** `100 Continue` (Pode continuar enviando o restante da requisição).

---

### 🟢 2xx: Sucesso (Bem-sucedido)
> **Significado:** *"Tudo certo! Recebi e processei com sucesso."* ✅

Esta é a família favorita dos desenvolvedores! Indica que a ação foi entendida e concluída.
* **200 OK:** Resposta padrão para sucesso total.
* **201 Created:** Sucesso! Um novo recurso (como um cadastro) foi criado.
* **204 No Content:** Deu certo, mas não há nada para te mostrar no corpo da resposta.

---

### 🟡 3xx: Redirecionamento
> **Significado:** *"Esta página mudou, siga para o novo local."* ↪️

Indica que o cliente precisa tomar medidas adicionais para completar a solicitação. Geralmente usado quando uma URL muda de endereço.
* **301 Moved Permanently:** O recurso agora mora em outro endereço para sempre.
* **302 Found:** O recurso mudou de lugar só por enquanto.

---

### 🟠 4xx: Erro de Cliente (Erro do Usuário)
> **Significado:** *"Você (usuário/aplicativo) cometeu um erro na requisição."* ❌

Indica que a requisição tem algum problema de sintaxe, falta de permissão ou simplesmente não existe.
* **400 Bad Request:** A requisição veio "torta" ou malformada.
* **401 Unauthorized:** Você esqueceu de fazer login.
* **403 Forbidden:** Eu sei quem você é, mas você não tem permissão para entrar aqui.
* **404 Not Found:** O clássico! O servidor não encontrou o que você pediu.

---

### 🔴 5xx: Erro de Servidor
> **Significado:** *"Eu (servidor) falhei ao processar seu pedido."* 🔥

Aqui o problema não é com o usuário, mas sim com a infraestrutura ou o código que roda no servidor.
* **500 Internal Server Error:** O código deu erro e o servidor não sabe explicar o porquê.
* **502 Bad Gateway:** O servidor recebeu uma resposta inválida de outro servidor acima dele.
* **503 Service Unavailable:** Estamos em manutenção ou o servidor está sobrecarregado.
* **504 Gateway Timeout:** O tempo de espera acabou e o servidor não respondeu.

---

<p align="center">
  <b>💡 Dica Pro:</b> Se o erro começa com <b>4</b>, o problema costuma ser no seu código/app. Se começa com <b>5</b>, o problema é no servidor/API!
</p>

---
# 📦 Entendendo o Formato JSON
<img width="203" height="167" alt="image" src="https://github.com/user-attachments/assets/7e1a8afa-b79f-4602-a436-f29a472c0b45" />

## 📋 1.5) O que é JSON?
**JSON** é a sigla para *JavaScript Object Notation* (Notação de Objeto JavaScript). 

É um formato leve e padronizado para **organizar e trocar dados** entre sistemas. Imagine o JSON como um "formulário inteligente" que os computadores usam para conversar, sendo muito fácil de ler tanto por humanos quanto por máquinas. 🤖💬

---

## 🏗️ Como o formato funciona?
O JSON utiliza uma estrutura baseada em **pares de chave e valor**:
* **Chave:** É o nome do campo (ex: `"temperatura"`).
* **Valor:** É a informação guardada (ex: `26.5`).

### 📊 Exemplo de leitura do nosso projeto:
No nosso sistema de monitoramento, o **ESP32** envia os dados para a API exatamente assim:

```json
{
  "temperatura": 26.5,
  "umidade": 72,
  "data": "2026-05-15T14:30:00"
}
```
🚀 Por que o JSON é o padrão das APIs?
Existem quatro motivos principais para o JSON dominar o mundo das APIs REST:

🚀 Leveza: Ocupa pouquíssimo espaço na transmissão, tornando a comunicação entre o sensor e o servidor muito rápida.

🧠 Simplicidade: É fácil de entender e escrever, o que evita erros de programação.

🌎 Universalidade: É compatível com praticamente todas as linguagens de programação (Python, JavaScript, C++, PHP, etc.).

⚡ Conversão Direta: As linguagens modernas conseguem transformar um texto JSON em um objeto de código instantaneamente.


# 📚 DOCUMENTAÇÃO DOS ENDPOINTS / ROTAS [parte 2 ]

---

# 🌐 API de Sensores

Esta API permite consultar, cadastrar, atualizar e remover dados de sensores de temperatura e umidade.

---

# 📥 1. GET `/api/sensores`

## 📝 Descrição
Retorna todo o histórico de sensores cadastrados.

---

## 📌 Parâmetros
Nenhum.

---

## 🚀 Exemplo de Requisição

```http
GET http://localhost:3000/api/sensores
```

---

## ✅ Resposta de Sucesso

**Status Code:** `200 OK`

```json
[
  {
    "id": 1,
    "temperatura": 28,
    "umidade": 53,
    "hora": "09:12"
  },
  {
    "id": 2,
    "temperatura": 31,
    "umidade": 46,
    "hora": "13:46"
  }
]
```

---

## ❌ Resposta de Erro

**Status Code:** `500 Internal Server Error`

```json
{
  "erro": "Erro ao buscar os dados dos sensores."
}
```

---

# 🔍 2. GET `/api/sensores/:id`

## 📝 Descrição
Retorna os dados de um sensor específico.

---

## 📌 Parâmetros

| Parâmetro | Tipo | Descrição |
|:---|:---|:---|
| `id` | Number | ID do sensor |

---

## 🚀 Exemplo de Requisição

```http
GET http://localhost:3000/api/sensores/1
```

---

## ✅ Resposta de Sucesso

**Status Code:** `200 OK`

```json
{
  "id": 1,
  "temperatura": 28,
  "umidade": 53,
  "hora": "09:12"
}
```

---

## ❌ Resposta de Erro

**Status Code:** `404 Not Found`

```json
{
  "erro": "Sensor não encontrado."
}
```

---

# ➕ 3. POST `/api/sensores`

## 📝 Descrição
Cadastra um novo sensor no sistema.

---

## 📌 Body JSON

| Campo | Tipo | Descrição |
|:---|:---|:---|
| `temperatura` | Number | Temperatura registrada |
| `umidade` | Number | Umidade registrada |
| `hora` | String | Horário da medição |

---

## 🚀 Exemplo de Requisição

```http
POST http://localhost:3000/api/sensores
Content-Type: application/json
```

```json
{
  "temperatura": 26,
  "umidade": 60,
  "hora": "15:30"
}
```

---

## ✅ Resposta de Sucesso

**Status Code:** `201 Created`

```json
{
  "mensagem": "Sensor cadastrado com sucesso.",
  "sensor": {
    "id": 4,
    "temperatura": 26,
    "umidade": 60,
    "hora": "15:30"
  }
}
```

---

## ❌ Resposta de Erro

**Status Code:** `400 Bad Request`

```json
{
  "erro": "Dados inválidos. Verifique os campos enviados."
}
```

---

# ✏️ 4. PUT `/api/sensores/:id`

## 📝 Descrição
Atualiza as informações de um sensor existente.

---

## 📌 Parâmetros

| Parâmetro | Tipo | Descrição |
|:---|:---|:---|
| `id` | Number | ID do sensor |

---

## 📌 Body JSON

| Campo | Tipo | Descrição |
|:---|:---|:---|
| `temperatura` | Number | Nova temperatura |
| `umidade` | Number | Nova umidade |
| `hora` | String | Novo horário |

---

## 🚀 Exemplo de Requisição

```http
PUT http://localhost:3000/api/sensores/2
Content-Type: application/json
```

```json
{
  "temperatura": 29,
  "umidade": 50,
  "hora": "16:00"
}
```

---

## ✅ Resposta de Sucesso

**Status Code:** `200 OK`

```json
{
  "mensagem": "Sensor atualizado com sucesso.",
  "sensor": {
    "id": 2,
    "temperatura": 29,
    "umidade": 50,
    "hora": "16:00"
  }
}
```

---

## ❌ Resposta de Erro

**Status Code:** `404 Not Found`

```json
{
  "erro": "Sensor não encontrado."
}
```

---

# 🗑️ 5. DELETE `/api/sensores/:id`

## 📝 Descrição
Remove um sensor do sistema.

---

## 📌 Parâmetros

| Parâmetro | Tipo | Descrição |
|:---|:---|:---|
| `id` | Number | ID do sensor |

---

## 🚀 Exemplo de Requisição

```http
DELETE http://localhost:3000/api/sensores/3
```

---

## ✅ Resposta de Sucesso

**Status Code:** `200 OK`

```json
{
  "mensagem": "Sensor removido com sucesso."
}
```

---

## ❌ Resposta de Erro

**Status Code:** `404 Not Found`

```json
{
  "erro": "Sensor não encontrado."
}
```

---

# 📖 Resumo das Rotas

| Método | Rota | Função |
|:---|:---|:---|
| `GET` | `/api/sensores` | Listar sensores |
| `GET` | `/api/sensores/:id` | Buscar sensor por ID |
| `POST` | `/api/sensores` | Cadastrar sensor |
| `PUT` | `/api/sensores/:id` | Atualizar sensor |
| `DELETE` | `/api/sensores/:id` | Remover sensor |

---
# PARTE 3
<img width="715" height="409" alt="image" src="https://github.com/user-attachments/assets/4f6c2a36-8cf5-4b49-bbc4-4b04061f15a6" />

---

<img width="831" height="388" alt="image" src="https://github.com/user-attachments/assets/4508ef32-a2f9-42e5-a77f-84381403319f" />


---
<img width="796" height="387" alt="image" src="https://github.com/user-attachments/assets/084eb540-f449-478a-b5a6-cd63a21de7e7" />

---
# 🚀 PARTE 4 — COMO RODAR E REFLEXÃO

---

## ▶️ 4.1) Como Rodar o Projeto

### 📋 Pré-requisitos

Antes de iniciar o projeto, é necessário ter instalado:

- **Node.js** (versão 18 ou superior)
- **npm** (gerenciador de pacotes do Node.js, já vem junto)

Para verificar se está instalado corretamente, use no terminal:

```bash
node -v
npm -v
```

Se aparecerem números de versão, está tudo funcionando. ✅

---

### 📥 Instalação do Projeto

Clone o projeto ou baixe os arquivos e abra a pasta no terminal.

Depois execute:

```bash
npm install
```

Esse comando instala todas as dependências necessárias da API.

---

### ▶️ Como Rodar a API

No terminal, execute:

```bash
node server.js
```

Se tudo estiver correto, aparecerá uma mensagem parecida com:

```bash
Servidor rodando em http://localhost:3000
```

Isso significa que a API está funcionando corretamente. ✅

---

### 🧪 Como Testar a API

Para testar os endpoints utilizamos o **Postman**.

---

#### 🔹 Requisição GET

##### URL

```bash
http://localhost:3000/api/sensores
```

##### ✅ Exemplo de resposta

```json
[
  {
    "id": 1,
    "temperatura": 28,
    "umidade": 53,
    "hora": "09:12"
  }
]
```

---

#### 🔹 Requisição POST

##### URL

```bash
http://localhost:3000/api/sensores
```

##### Body (JSON)

```json
{
  "temperatura": 30,
  "umidade": 45,
  "hora": "14:20"
}
```

##### ✅ Resposta esperada

```json
{
  "mensagem": "Dado cadastrado com sucesso!"
}
```

---

# 🛠️ 4.2) Tecnologias Utilizadas

| Tecnologia | Função |
|---|---|
| **Node.js** | Ambiente que executa JavaScript no servidor |
| **Express.js** | Framework utilizado para criar as rotas e organizar a API |
| **Postman** | Ferramenta usada para testar os endpoints |
| **JavaScript** | Linguagem principal utilizada no projeto |
| **JSON** | Formato usado para enviar e receber dados |
| **CORS** | Middleware utilizado para permitir comunicação entre aplicações |
| **GitHub** | Plataforma utilizada para versionamento do código |

---

# 💭 4.3) Reflexão Sobre a Atividade

O que mais gostamos nessa atividade foi aprender como funciona uma API na prática e perceber como os dados podem ser enviados e recebidos entre aplicações. 

Também foi interessante utilizar o Postman (apesar dele me odiar), porque conseguimos visualizar o funcionamento real do sistema.🧑‍🔧

Outra parte muito legal foi organizar as rotas e ver o servidor funcionando corretamente no navegador e no terminal. Isso mostra como funciona a comunicação entre cliente e servidor.

---

## ⚠️ Principais Dificuldades  para mim 😑


- esquecer algum ponto e vírgula ou chave;🤦‍♀️
- Postman.☠️




