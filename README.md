<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&height=220&color=0:0F172A,50:2563EB,100:38BDF8&text=%F0%9F%A7%AE%20Calculadora%20Simples&fontSize=42&fontColor=FFFFFF&fontAlignY=40&desc=Aplicação%20matemática%20criada%20com%20React%20JS&descAlignY=62&descSize=17&animation=fadeIn" width="100%"/>

<br>

# ⚛️ React JS

**Aplicação desenvolvida durante as aulas para colocar em prática conceitos fundamentais do React.**

<br>

![React](https://img.shields.io/badge/React-61DAFB?style=flat-square\&logo=react\&logoColor=111827)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square\&logo=javascript\&logoColor=111827)
![CSS3](https://img.shields.io/badge/CSS3-38BDF8?style=flat-square\&logo=css3\&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square\&logo=vite\&logoColor=white)

</div>

---

## 💻 Sobre a aplicação

A **Calculadora Simples** consiste em uma aplicação web feita utilizando **React JS**, criada para executar cálculos matemáticos básicos de forma prática.

Para utilizar o sistema, basta preencher os dois campos numéricos, selecionar uma das operações disponíveis e pressionar o botão de cálculo. O resultado aparece diretamente na interface.

> 📚 O projeto foi elaborado como uma atividade acadêmica, com a finalidade de exercitar a criação de interfaces utilizando React.

---

## 🎯 Finalidade do projeto

O desenvolvimento da calculadora busca demonstrar como o **React trabalha com informações e interações do usuário**, permitindo que a página seja atualizada de acordo com as ações realizadas.

Entre os principais conhecimentos utilizados estão:

**Componentes** → divisão da aplicação em partes reutilizáveis
**Estado** → controle das informações digitadas
**Eventos** → execução de ações através dos botões
**Formulários** → recebimento dos dados inseridos
**JSX** → criação dos elementos da página
**CSS** → personalização visual da aplicação

---

## ✨ Recursos disponíveis

### 🔢 Inserção dos números

A calculadora possui dois campos para que o usuário possa informar os valores utilizados na operação:

* Primeiro valor
* Segundo valor

### ➕ Operações matemáticas

Um menu de seleção permite escolher qual cálculo será realizado.

```text
+  Adição
-  Subtração
*  Multiplicação
/  Divisão
```

### 🧮 Realização do cálculo

Após informar os valores e selecionar a operação, basta utilizar o botão:

**CALCULAR**

O sistema identifica a operação escolhida, realiza o cálculo e exibe o valor obtido.

### 🧹 Apagar informações

O botão:

**LIMPAR**

é utilizado para retirar os números inseridos e também apagar o resultado atual.

---

## 🧠 Como o sistema funciona

O processo realizado pela aplicação pode ser representado da seguinte maneira:

```text
        👤 USUÁRIO
            │
            ▼
     🔢 Insere os valores
            │
            ▼
      🔽 Seleciona o cálculo
            │
            ▼
       🧮 Pressiona o botão
            │
            ▼
      ⚙️ React executa a lógica
            │
            ▼
       📊 Exibe o resultado
```

O React recebe os dados fornecidos pelo usuário, utiliza a operação selecionada e atualiza a tela com o resultado correspondente.

---

## 📁 Organização dos arquivos

O projeto foi separado em diferentes arquivos para facilitar a manutenção e deixar o código mais organizado.

```text
calculadora-simples/
│
├── 📂 components/
│   └── 📄 FormCalculadora.jsx
│
├── 📄 App.jsx
├── 📄 App.css
├── 📄 index.css
├── 📄 main.jsx
├── 📄 package.json
└── 📄 README.md
```

### `FormCalculadora.jsx`

Esse arquivo contém o principal componente da calculadora.

Nele estão os elementos responsáveis pela entrada dos números, escolha da operação, botões de ação e exibição do resultado.

---

## 🎨 Design da aplicação

A interface foi personalizada utilizando **CSS3**, buscando manter os elementos bem distribuídos e fáceis de utilizar.

A estilização envolve principalmente:

* 🎨 Definição das cores
* 📦 Espaçamento e posicionamento
* 🔘 Aparência dos botões
* 📝 Estilização dos campos
* 🔽 Personalização do seletor
* 📊 Destaque para o resultado

A proposta é manter uma interface simples, organizada e adequada para uma aplicação de cálculos.

---

## 🛠️ Ferramentas utilizadas

<div align="center">

### ⚛️ React JS

Utilizado para desenvolver a interface e estruturar os componentes da aplicação.

### 🟨 JavaScript

Responsável pela lógica utilizada para executar os cálculos.

### 🎨 CSS3

Aplicado na criação do visual e na organização dos elementos da página.

### ⚡ Vite

Ferramenta utilizada para iniciar o projeto e facilitar o processo de desenvolvimento com React.

</div>

---

## 🚀 Executando o projeto

Para testar a aplicação em seu computador, abra a pasta do projeto no **VS Code** e utilize o terminal.

### 1. Baixar as dependências

Execute:

```bash
npm install
```

Esse comando instala os pacotes necessários para o funcionamento da aplicação.

### 2. Iniciar o servidor

Depois da instalação, execute:

```bash
npm run dev
```

O Vite irá iniciar o ambiente de desenvolvimento.

### 3. Abrir a aplicação

Após iniciar o projeto, o terminal apresentará um endereço local. Abra esse endereço no navegador para acessar a calculadora.

---

## 📚 Aprendizados

Com este projeto foi possível praticar conceitos importantes do desenvolvimento com React, principalmente a utilização de **componentes, estados, eventos, formulários e JSX**.

Além disso, a atividade ajudou a compreender melhor como uma aplicação pode receber informações do usuário, processá-las e atualizar a interface de maneira dinâmica.
