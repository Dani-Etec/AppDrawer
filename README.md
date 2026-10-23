# AppDrawer

Aplicativo Android desenvolvido em Kotlin com interface baseada em Drawer Navigation (menu lateral). O projeto demonstra o uso de componentes do Material Design e a atualização dinâmica do conteúdo principal da tela conforme a opção selecionada no menu.

Documentação estruturada e assistida por GitHub Copilot.

## Visão geral

O AppDrawer é uma aplicação simples, com uma tela principal contendo:

- Toolbar
- Menu lateral (Navigation Drawer)
- Texto central que muda conforme a opção do menu selecionada

Ao clicar em itens como "Início", "Configurações" e "Perfil", a interface atualiza o conteúdo exibido na tela.

## Funcionalidades

- Menu lateral com navegação
- Atualização dinâmica do texto principal
- Interface moderna com Material Components
- Estrutura básica de projeto Android

## Tecnologias utilizadas

- Kotlin
- Android Studio
- AndroidX
- Material Components
- Gradle Kotlin DSL
- AppCompat
- DrawerLayout
- NavigationView

## Estrutura do projeto

```text
AppDrawer/
├── .gitignore
├── build.gradle.kts
├── settings.gradle.kts
├── gradlew
├── gradlew.bat
├── gradle/
│   └── wrapper/
├── app/
│   ├── .gitignore
│   ├── build.gradle.kts
│   ├── proguard-rules.pro
│   └── src/
│       ├── androidTest/
│       ├── main/
│       │   ├── AndroidManifest.xml
│       │   ├── java/
│       │   │   └── com/example/appdrawer/
│       │   │       └── MainActivity.kt
│       │   └── res/
│       │       ├── drawable/
│       │       ├── layout/
│       │       │   └── activity_main.xml
│       │       ├── menu/
│       │       │   └── navigation_drawer.xml
│       │       ├── mipmap-*/
│       │       ├── values/
│       │       │   └── strings.xml
│       │       ├── values-night/
│       │       └── xml/
```

## Requisitos

Antes de executar o projeto, certifique-se de que você possui:

- Android Studio
- JDK 11 ou superior
- Android SDK
- Emulador Android ou dispositivo físico com depuração habilitada

## Instalação

1. Clone o repositório:

```bash
git clone https://github.com/Dani-Etec/AppDrawer.git
```

2. Acesse a pasta do projeto:

```bash
cd AppDrawer
```

3. Abra o projeto no Android Studio.

4. Sincronize o Gradle:

- Clique em `Sync Project with Gradle Files`

## Como executar

### Opção 1: no Android Studio

1. Conecte um emulador ou dispositivo Android
2. Selecione o dispositivo em execução
3. Clique em `Run`
4. Escolha a configuração `app`

### Opção 2: via terminal

Para compilar o projeto em modo debug:

```bash
./gradlew assembleDebug
```

Para instalar diretamente no dispositivo/emulador conectado:

```bash
./gradlew installDebug
```

No Windows, use:

```bash
gradlew.bat assembleDebug
```

## Build do projeto

Para gerar o build completo:

```bash
./gradlew build
```

## Observações

- O projeto é uma aplicação Android simples e didática.
- A lógica principal está centralizada na `MainActivity`.
- A navegação é feita por um `Navigation Drawer` com opções do menu lateral.
- A aplicação não utiliza arquitetura avançada como MVVM ou Clean Architecture; seu foco é demonstrar o uso de componentes de UI Android.

## Autor

Dani-Etec

## Documentação

Este README foi elaborado com apoio do GitHub Copilot para apresentar uma visão geral clara do projeto, sua estrutura e instruções de execução.

## Licença

Este projeto não informa uma licença específica no repositório. Caso deseje utilizar o código em outros contextos, verifique a política do repositório antes de distribuir ou reutilizar.

---

Se quiser, também posso criar uma segunda versão do README com:
- visual mais profissional
- badges do GitHub
- seção de screenshots
- instruções específicas para Windows/macOS/Linux
- estilo mais moderno e elegante
