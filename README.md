# instalando-flutter

A instalação do Flutter varia um pouco dependendo do sistema operacional que você está usando. Abaixo estão os passos detalhados para instalar o Flutter no Windows, macOS e Linux.

### 1. Instalando no Windows

#### Passo 1: Baixar o SDK do Flutter
1. Acesse o site oficial do Flutter: [flutter.dev](https://flutter.dev)
2. Clique em "Get Started" e então selecione "Windows".
3. Baixe o arquivo `.zip` do SDK do Flutter.

#### Passo 2: Extrair o SDK do Flutter
1. Extraia o arquivo `.zip` baixado para um local desejado, como `C:\src\flutter`.

#### Passo 3: Configurar a Variável de Ambiente
1. Abra o Painel de Controle e navegue até `Sistema e Segurança` > `Sistema` > `Configurações avançadas do sistema`.
2. Na aba `Avançado`, clique em `Variáveis de Ambiente`.
3. Em `Variáveis do sistema`, encontre a variável `Path` e clique em `Editar`.
4. Adicione o caminho do diretório `bin` do Flutter (por exemplo, `C:\src\flutter\bin`) na lista de caminhos.

#### Passo 4: Verificar a Instalação
1. Abra o Prompt de Comando ou PowerShell.
2. Execute `flutter doctor` para verificar a instalação e ver se há dependências adicionais que precisam ser instaladas.

### 2. Instalando no macOS

#### Passo 1: Baixar o SDK do Flutter
1. Acesse o site oficial do Flutter: [flutter.dev](https://flutter.dev)
2. Clique em "Get Started" e então selecione "macOS".
3. Baixe o arquivo `.zip` do SDK do Flutter.

#### Passo 2: Extrair o SDK do Flutter
1. Extraia o arquivo `.zip` baixado para um local desejado, como `~/development/flutter`.

#### Passo 3: Adicionar Flutter ao PATH
1. Abra o Terminal.
2. Adicione o seguinte comando ao seu arquivo de inicialização do shell, como `.bashrc` ou `.zshrc`:
    ```sh
    export PATH="$PATH:`pwd`/flutter/bin"
    ```
3. Reinicie o Terminal ou carregue o arquivo de inicialização:
    ```sh
    source ~/.bashrc
    ```

#### Passo 4: Verificar a Instalação
1. No Terminal, execute `flutter doctor` para verificar a instalação e ver se há dependências adicionais que precisam ser instaladas.

### 3. Instalando no Linux

#### Passo 1: Baixar o SDK do Flutter
1. Acesse o site oficial do Flutter: [flutter.dev](https://flutter.dev)
2. Clique em "Get Started" e então selecione "Linux".
3. Baixe o arquivo `.tar.xz` do SDK do Flutter.

#### Passo 2: Extrair o SDK do Flutter
1. Abra o Terminal.
2. Extraia o arquivo baixado para um local desejado, como `~/development`:
    ```sh
    tar xf flutter_linux_vX.X.X-stable.tar.xz
    ```

#### Passo 3: Adicionar Flutter ao PATH
1. Adicione o seguinte comando ao seu arquivo de inicialização do shell, como `.bashrc` ou `.zshrc`:
    ```sh
    export PATH="$PATH:`pwd`/flutter/bin"
    ```
2. Reinicie o Terminal ou carregue o arquivo de inicialização:
    ```sh
    source ~/.bashrc
    ```

#### Passo 4: Verificar a Instalação
1. No Terminal, execute `flutter doctor` para verificar a instalação e ver se há dependências adicionais que precisam ser instaladas.

### Dependências Adicionais

Independentemente do sistema operacional, você pode precisar instalar algumas dependências adicionais:

- **Java Development Kit (JDK)**: Necessário para desenvolvimento Android.
- **Android Studio**: Inclui o Android SDK.
- **Xcode** (apenas macOS): Necessário para desenvolvimento iOS.

### Conclusão

Após seguir os passos acima para o seu respectivo sistema operacional, você deve ter o Flutter instalado e pronto para uso. O comando `flutter doctor` é muito útil para diagnosticar qualquer problema e garantir que todas as dependências necessárias estão instaladas.
