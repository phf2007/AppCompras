# App Compras

> Um aplicativo Android simples que funciona como uma calculadora que soma os itens selecionados para sua compra.

## 📱 Descrição

O **App Compras** permite ao usuário calcular quanto custaria caso comprasse cada item que estava sendo mostrado nas CheckBox.

## 🔧 Funcionalidades

- [x] 1 Tela que fará toda a conta
- [x] Um TextView abaixo do botão que exibe o resultado
- [x] Fácil de entender
- [x] Interface simples e intuitiva
- [ ] Tema claro e escuro (planejado para futuras versões)

## 🚀 Tecnologias Utilizadas

- [x] **Android Studio** (Bumblebee | 2021.1.1)
- [x] **Kotlin+Java** para desenvolvimento
- [x] **ConstraintLayout** para interface responsiva
- [x] **TextView**, **Button** e **EditText**

## 🛠️ Como Rodar o Projeto

Siga os passos abaixo para rodar o projeto localmente:


1. Clone este repositório:
    ```bash
    git clone https://github.com/phf2007/AppCompras/mercado.zip
    ```

2. Abra o projeto no Android Studio.

3. Compile e execute o projeto em um emulador ou dispositivo físico.

## 📂 Estrutura do Projeto

MyApplication
├── app
│   ├── main
│   │   ├── java/com.example.myapplication
│   │   │   ├── MainActivity.java                  # Atividade principal onde está o mercado
│   │   ├── res
│   │   │   ├── layout
│   │   │   │   ├── activity_main.xml              # Layout da tela principal
│   │   │   └── values
│   │   │       ├── strings.xml                    # Strings usadas no app
│   │   │       ├── colors.xml                     # Cores definidas no projeto
│   └── build.gradle                               # Configuração do Gradle
└── README.md                                      # Este arquivo



## 🎨 Design e Prototipagem 

A interface do app foi criada usando **ConstraintLayout** para manter a responsividade em diferentes tamanhos de tela. 

O design é minimalista e fácil de usar, com foco na simplicidade.

 ## 🖥️ Telas do Aplicativo

**Tela Principal** 

Na tela principal, teremos 5 CheckBox, cada uma com um item e um preço especifico, a cada CheckBox que você marca vai somando o preço até dar o preço final de sua compra.

## 👨‍💻 Desenvolvedores – 
Pedro Henrique Fontes - Desenvolvedor - [GitHub](https://github.com/phf2007)
