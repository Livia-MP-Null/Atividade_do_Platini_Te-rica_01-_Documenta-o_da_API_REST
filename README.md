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
| <img src="https://img.shields.io/badge/-200-brightgreen"> <img width="750" height="600" alt="image" src="https://github.com/user-attachments/assets/760a5ed8-d0a5-4e92-bac3-42d9e21f5552" />| **OK** | Requisição realizada com sucesso! ✅ | Quando o GET retorna os dados de temperatura e umidade. |
| <img src="https://img.shields.io/badge/-201-green"> | **Created** | Novo recurso criado com sucesso! ✨ | Quando o ESP32 envia um POST e salva uma nova leitura. |
| <img src="https://img.shields.io/badge/-400-orange"> | **Bad Request** | Erro na requisição ou dados inválidos. ⚠️ | Quando enviamos dados de temperatura no formato errado. |
| <img src="https://img.shields.io/badge/-401-yellow"> | **Unauthorized** | Falta de autorização/login. 🔑 | Caso a API passe a exigir uma senha de acesso no futuro. |
| <img src="https://img.shields.io/badge/-404-red"> | **Not Found** | Caminho ou rota não encontrada. 🔍 | Ao tentar acessar uma URL que não existe na nossa API. |
| <img src="https://img.shields.io/badge/-500-darkred"> | **Server Error** | Deu problema no motor do servidor! 🔥 | Quando há um erro no código da API ou falha interna. |

---

### 💡 Dica de Leitura Rápida:
* 🟢 **2xx:** Sucesso (Tudo certo!)
* 🟡 **4xx:** Erro do Cliente (Você fez algo errado)
* 🔴 **5xx:** Erro do Servidor (O sistema quebrou)

---
<p align="center">
  <b><i>Entender os códigos de status é como falar a língua dos servidores! 💻🗣️</i></b>
</p>

  
