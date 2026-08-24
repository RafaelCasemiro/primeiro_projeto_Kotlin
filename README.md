# 📱 Primeiro Projeto Kotlin — Contador

Projeto desenvolvido em **Kotlin** utilizando **Android Studio**, com o objetivo de criar um aplicativo simples de contador, permitindo ao usuário **adicionar e subtrair valores** através de uma interface interativa.

## 🎯 Objetivo

O projeto tem como principal objetivo praticar conceitos básicos do desenvolvimento de aplicativos Android utilizando Kotlin, especialmente a criação de interfaces, interação com botões e gerenciamento de valores exibidos na tela.

O aplicativo possui uma funcionalidade principal de contador, permitindo ao usuário:

* ➕ Adicionar valores ao contador;
* ➖ Subtrair valores do contador.

## 🏗️ Estrutura do Projeto

O projeto possui dois arquivos principais relacionados à construção e funcionamento da aplicação:

### `MainActivity.kt`

Arquivo responsável por iniciar a aplicação e exibir o conteúdo desenvolvido no `ContadorScreen`.

O `MainActivity.kt` realiza a chamada da tela principal do aplicativo.

### `ContadorScreen.kt`

Arquivo responsável pela criação da interface do contador.

Nele foram desenvolvidos os componentes visuais e a lógica de interação dos botões, incluindo:

* Exibição do valor atual do contador;
* Botão para adicionar valores;
* Botão para subtrair valores;
* Funcionalidades extras descritas abaixo.

## ⭐ Bônus — Desafios Extras

Além da funcionalidade principal de adicionar e subtrair valores, foram implementados **dois desafios extras**.

### 🚫 Impedir valores negativos

Foi implementada uma condição para impedir que o contador fique abaixo de `0`.

Dessa forma, quando o contador estiver em `0`, o usuário não poderá diminuir seu valor para um número negativo.

### 🔄 Botão de Reset

Foi criado um botão adicional para **resetar o contador**.

Ao pressioná-lo, o valor atual do contador retorna imediatamente para `0`.

## 🛠️ Tecnologias utilizadas

* **Kotlin**
* **Android Studio**
* **Jetpack Compose**

## 📂 Principais arquivos

```text
PrimeiroProjeto/
│
├── MainActivity.kt
└── ContadorScreen.kt
```

## 📌 Funcionalidades

| Funcionalidade            | Tipo      | Status |
| ------------------------- | --------- | :----: |
| ➕ Adicionar valor         | Principal |    ✅   |
| ➖ Subtrair valor          | Principal |    ✅   |
| 🚫 Impedir valor negativo | **Bônus** |    ✅   |
| 🔄 Resetar contador       | **Bônus** |    ✅   |

---

## 👨‍💻 Projeto

**Primeiro Projeto Kotlin**

Projeto desenvolvido como atividade prática para aprendizado e aplicação de conceitos básicos de desenvolvimento de aplicativos Android utilizando **Kotlin, Android Studio e Jetpack Compose**.
