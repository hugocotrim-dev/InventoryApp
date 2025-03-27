# Inventory App

## Visão Geral

O Inventory App é um aplicativo móvel desenvolvido com React Native e Expo, projetado para ajudar os usuários a gerenciar seus inventários de forma eficiente. Ele permite adicionar, editar, excluir e pesquisar itens no inventário, além de oferecer funcionalidades de filtragem por categoria, marca e quantidade. O aplicativo utiliza um banco de dados SQLite para armazenar os dados localmente.

## Funcionalidades Principais

*   **Gerenciamento de Inventário:** Adicione, edite e exclua itens do seu inventário.
*   **Pesquisa:** Encontre itens rapidamente usando a função de pesquisa por nome, marca ou categoria.
*   **Filtragem:** Filtre os itens por categoria, marca e quantidade.
*   **Interface Amigável:** Interface de usuário intuitiva e fácil de usar.
*   **Armazenamento Local:** Utiliza um banco de dados SQLite para armazenar os dados localmente no dispositivo.
*   **Configurações:** Permite alterar o nome do aplicativo.

## Tecnologias Utilizadas

*   **React Native:** Framework para construção de aplicativos móveis multiplataforma.
*   **Expo:** Plataforma para desenvolvimento, construção e publicação de aplicativos React Native.
*   **SQLite:** Banco de dados leve para armazenamento local dos dados.
*   **React Navigation:** Biblioteca para navegação entre telas no aplicativo.
*   **React Native Paper:** Biblioteca de componentes de interface do usuário que seguem as diretrizes do Material Design.
*   **@react-native-picker/picker:** Componente para selecionar valores de uma lista (usado para filtros).
*   **expo-updates:** Biblioteca para atualizar o app remotamente.

## Pré-requisitos

Antes de começar, você precisará ter o seguinte instalado:

*   [Node.js](https://nodejs.org/) (versão 14 ou superior)
*   [npm](https://www.npmjs.com/) ou [Yarn](https://yarnpkg.com/)
*   [Expo CLI](https://docs.expo.dev/get-started/expo-cli/)

## Instalação

Existem duas maneiras de instalar o Inventory App:

1.  **A partir do arquivo APK (se disponível):**

    Se você já possui um arquivo APK do aplicativo, siga estas etapas:

    *   **Android:**
        1.  Copie o arquivo APK para o seu dispositivo Android.
        2.  No seu dispositivo, vá em "Configurações" > "Segurança" e habilite a opção "Fontes desconhecidas" (ou "Instalar aplicativos de fontes desconhecidas").
        3.  Use um gerenciador de arquivos para encontrar o arquivo APK e toque nele para iniciar a instalação.
        4.  Siga as instruções na tela para concluir a instalação.

    *   **Observação:** A instalação a partir de fontes desconhecidas pode apresentar riscos de segurança. Certifique-se de obter o arquivo APK de uma fonte confiável.

2.  **A partir do código fonte (para desenvolvedores):**

    Se você é um desenvolvedor e deseja executar o aplicativo a partir do código fonte, siga estas etapas:

    1.  Clone o repositório:

        ```bash
        git clone <URL do seu repositório>
        ```

    2.  Navegue até o diretório do projeto:

        ```bash
        cd inventory-app
        ```

    3.  Instale as dependências:

        ```bash
        npm install
        # ou
        yarn install
        ```

## Configuração

1.  **Configuração do Banco de Dados:**

    *   O aplicativo utiliza o SQLite para armazenar os dados localmente. A configuração do banco de dados é gerenciada no arquivo `src/database/simple_db.ts`.
    *   As tabelas `inventory` e `app_settings` são criadas automaticamente na primeira vez que o aplicativo é executado.

2.  **Variáveis de Ambiente:**

    *   Nenhuma variável de ambiente é necessária para executar o aplicativo.

## Execução

Para executar o aplicativo, siga estas etapas:

1.  Inicie o servidor Expo:

    ```bash
    npm start
    # ou
    yarn start
    ```

2.  Use o aplicativo Expo Go no seu dispositivo móvel para escanear o código QR exibido no terminal.
