# Flash-Chat

## Objetivo

Um dos componentes mais fundamentais dos aplicativos iOS modernos é a Tabela de Visualização. As Tabelas de Visualização são usadas em todos os lugares, desde o aplicativo de e-mail até o aplicativo de mensagens. É uma parte crucial do cinto de ferramentas de todo desenvolvedor iOS. Familiarizando com as Tabelas de Visualização, criando células personalizadas e criando nosso próprio banco de dados de backend baseado em nuvem.

## O que foi criado

Flash Chat é um aplicativo de mensagens baseado na internet semelhante ao WhatsApp, o popular aplicativo de mensagens que foi comprado pelo Facebook por US $ 22 bilhões. Usaremos um serviço chamado Firebase Firestore como um banco de dados de backend para armazenar e recuperar nossas mensagens da nuvem.

## O que você aprenderá

- Como integrar bibliotecas de terceiros em seu aplicativo usando Cocoapods e Swift Package Manager.
- Como armazenar dados na nuvem usando o Firebase Firestore.
- Como consultar e classificar o banco de dados Firebase.
- Como usar o Firebase para autenticação de usuário, registro e login.
- Como trabalhar com UITableViews e como definir suas fontes de dados e delegados.
- Como criar visualizações personalizadas usando arquivos .xib para modificar componentes de design nativos.
- Como incorporar Controladores de Visualização em um Controlador de Navegação e entender a pilha de navegação.
- Como criar um arquivo de constantes e usar propriedades estáticas para armazenar Strings e outras constantes.
- Aprenda sobre loops Swift e crie animações usando loops.
- Aprenda sobre o Ciclo de Vida do Aplicativo e como usar viewWillAppear ou viewWillDisappear.
- Como criar Segues diretos para navegação.

# Constantes

```
struct K {
    static let cellIdentifier = "ReusableCell"
    static let cellNibName = "MessageCell"
    static let registerSegue = "RegisterToChat"
    static let loginSegue = "LoginToChat"

    struct BrandColors {
        static let purple = "BrandPurple"
        static let lightPurple = "BrandLightPurple"
        static let blue = "BrandBlue"
        static let lighBlue = "BrandLightBlue"
    }

    struct FStore {
        static let collectionName = "messages"
        static let senderField = "sender"
        static let bodyField = "body"
        static let dateField = "date"
    }
}

```

> Este é um projeto complementar ao Bootcamp de Desenvolvimento de Aplicativos Completos da App Brewery, confira o curso completo em [www.appbrewery.co](https://www.appbrewery.co/)

![End Banner](Documentation/readme-end-banner.png)
