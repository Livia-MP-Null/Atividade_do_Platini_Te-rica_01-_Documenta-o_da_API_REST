# Atividade Teórica 01 - Documentação da API REST

  <img width="500" height="241" alt="image" src="https://github.com/user-attachments/assets/f31ebd0f-4ae3-4830-8f29-3168bc33cc83" />


1.1) O que é uma API? Expliquem a sigla, pra que serve, por que é importante. Tentem usar uma analogia do dia a dia.

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

## 📑 1.2) O que é REST?
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


1.3) O que é CRUD?

  CRUD é uma sigla usada para representar as quatro operações básicas realizadas em sistemas que trabalham com dados. Cada letra corresponde a uma ação importante: [C] Create (criar), [R] Read (ler), [U] Update (atualizar) e [D] Delete (deletar). Isso aparece em praticamente qualquer aplicação, como redes sociais, lojas online e entre outros. Em APIs REST, cada operação normalmente é associada a um método HTTP específico.. O Create (C) foi adicionado usando o método POST, responsável por enviar novos dados para a API.O Read (R) foi adicionado usando o método GET,utilizado para buscar ou visualizar os dados já armazenados na API. O Update (U) serve para atualizar ou modificar dados que já existem. Em APIs REST, essa operação normalmente utiliza os métodos PUT ou PATCH.O método PUT geralmente substitui todas as informações do registro, enquanto o PATCH atualiza apenas parte dos dados.O Delete (D) é usado para remover informações do sistema e normalmente utiliza o método HTTP DELETE.


  
