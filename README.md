# 🎀 Pink Oracle

> Aplicação mobile desenvolvida para a disciplina de Programação de Aplicativos Mobile (APMO).

O **Pink Oracle** é um aplicativo mobile desenvolvido em **React Native com Expo**, que implementa um jogo de adivinhação de números.

A aplicação tenta descobrir o número escolhido pelo usuário por meio das respostas fornecidas durante o jogo. A cada tentativa, o usuário informa se o número apresentado pelo aplicativo é **maior**, **menor** ou se o aplicativo **acertou**.

O projeto foi desenvolvido como atividade acadêmica do curso Técnico em Informática Integrado ao Ensino Médio.

---

## 👩‍💻 Autoras

**Manuela Maganha**  
**Nalany Moreira**

🎓 **4º Info 1**

---

## 📱 Sobre o projeto

O Pink Oracle foi desenvolvido com o objetivo de aplicar conceitos de desenvolvimento de aplicações mobile utilizando **React Native** e **Expo**.

Durante o desenvolvimento, foram utilizados conceitos como:

- Componentização;
- Gerenciamento de estados com React;
- Navegação entre telas;
- Componentes `View`, `Text`, `Pressable` e `ImageBackground`;
- Entrada de dados;
- Manipulação de eventos;
- Geração de números aleatórios;
- Armazenamento local;
- Estilização de componentes;
- Execução e testes em emulador Android.

---

## 🎮 Como funciona?

O aplicativo apresenta um número ao usuário e tenta descobrir o número que ele escolheu.

Durante o jogo, o usuário pode informar se o número apresentado pelo aplicativo é:

⬇️ **Maior** — o número escolhido é maior que o apresentado.

⬆️ **Menor** — o número escolhido é menor que o apresentado.

🎯 **Acertou** — o aplicativo encontrou o número.

A cada resposta, o intervalo de possibilidades é atualizado, permitindo que o aplicativo faça novas tentativas até encontrar o número escolhido.

---

## 🛠️ Tecnologias utilizadas

| Tecnologia | Utilização |
|------------|------------|
| ⚛️ React Native | Desenvolvimento da interface mobile |
| 🚀 Expo | Execução e desenvolvimento da aplicação |
| 🟨 JavaScript | Linguagem utilizada no projeto |
| 📱 Android Emulator | Testes da aplicação |
| 💾 AsyncStorage | Armazenamento local de informações |
| 🎨 Expo Linear Gradient | Elementos visuais e gradientes |
| 🔤 Expo Font | Gerenciamento de fontes |

---

# ⚙️ Instalação e execução

## 📋 Pré-requisitos

Antes de começar, é necessário ter instalado:

* [Node.js](https://nodejs.org/)
* [Visual Studio Code](https://code.visualstudio.com/)
* [Android Studio](https://developer.android.com/studio/), para usar o emulador Android
* Expo Go, caso queira testar pelo celular

---

## 1️⃣ Baixar o projeto

Clone o repositório:

```bash
git clone URL_DO_REPOSITORIO
```

Entre na pasta:

```bash
cd Pink-Oracle
```

---

## 2️⃣ Abrir no Visual Studio Code

Abra a pasta do projeto no Visual Studio Code.

Depois, abra o terminal do VS Code.

---

## 3️⃣ Instalar as dependências

No terminal, execute:

```bash
npm install
```

Aguarde a instalação terminar.

---

## 4️⃣ Iniciar o projeto

Execute:

```bash
npx expo start
```

Depois disso, o Expo mostrará as opções para executar o aplicativo.

---

## 5️⃣ Executar no Android

### Emulador Android

Com o emulador aberto, pressione:

```text
a
```

O aplicativo será aberto no emulador.

### Celular

Caso esteja usando um celular, abra o **Expo Go** e escaneie o QR Code que aparecer no terminal ou na página do Expo.

O celular e o computador precisam estar conectados à mesma rede Wi-Fi.

---

## ⚠️ Caso dê algum erro

Se o aplicativo não carregar corretamente, tente iniciar o Expo limpando o cache:

```bash
npx expo start -c
```

Depois tente abrir novamente.

---

## 📌 Resumo

```bash
git clone URL_DO_REPOSITORIO
cd Pink-Oracle
npm install
npx expo start
```

Para abrir no emulador Android, pressione `a`.

