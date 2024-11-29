# Sobre o que é o repositorio

esse repositorio contém as atividades em java resolvidas do capitulo 6 e 8, do livro fundamentos da programação de computadores.

[<img src ="https://m.media-amazon.com/images/I/81HITrV4GXL._AC_UF894,1000_QL80_.jpg" width="300">](https://drive.google.com/file/d/1MWTShjGeyGTPoeVImLhxFDcUYBNt2bAB/view?usp=classroom_web&authuser=0)

### Fundamentos da programação de computadores

O livro Fundamentos da Programação da Computadores aborda os conceitos básicos da programação, oferecendo uma base sólida para iniciantes. Ele explica os princípios fundamentais da computação, como estruturas de dados, algoritmos e lógica de programação, ensinando como resolver problemas de forma eficiente. O conteúdo inclui introdução ao funcionamento dos computadores, elementos essenciais das linguagens de programação (variáveis, tipos de dados, operadores e controle de fluxo), além de explorar estruturas de dados como listas, pilhas, filas e árvores. O livro também cobre análise de algoritmos, complexidade computacional e boas práticas, com exemplos e exercícios práticos.

## CAP06

### Estrutura de dados vetor unidimensional

Um vetor unidimensional em Java é uma estrutura de dados que armazena uma sequência de elementos do mesmo tipo, organizados em uma única dimensão. Também é conhecido como array.

#### Caracteristicas
- **Tipo fixo**: Todos os elementos do vetor devem ser do mesmo tipo.
- **Tamanho fixo**: Uma vez declarado, o tamanho do vetor não pode ser alterado.
- **Acesso indexado**: Os elementos do vetor são acessados por um índice, que começa em 0.

## CAP08

### sub-rotina

Blocos de código organizados para realizar uma tarefa específica, que podem ser reutilizados ao longo do programa.

- **Estrutura**: Contêm um tipo de retorno, um nome, parâmetros opcionais e um corpo com instruções.

- **Objetivo**: Melhorar a organização, reutilização e legibilidade do código.

- **Parâmetros**: São usados para passar dados aos métodos durante a execução.

- **Modularidade**: Facilitam a separação do código em partes menores e independentes.

- **Chamada**: Podem ser invocados diretamente ou através de objetos, dependendo do contexto.
- 
#### Tipos

- **Métodos com retorno**: Devolvem um valor ao final da execução.

- **Métodos sem retorno**: Executam uma tarefa sem devolver valores.


## IDE utilizada

- eclipse 🌙

## Como Instalar o Eclipse para Desenvolvimento Java

### Passo 1: Baixar o Eclipse IDE 🌙

- Acesse o site oficial do Eclipse [🌙](https://www.eclipse.org/downloads/).
   
- Na página principal, você verá uma opção para baixar a versão mais recente do **Eclipse IDE for Java Developers**. Clique no botão **Download** para a versão que você deseja.
   
   - O **Eclipse IDE for Java Developers** é a versão mais adequada para quem vai programar em Java.

- O arquivo será baixado como um arquivo compactado (geralmente um arquivo `.zip` no Windows ou `.tar.gz` no Linux).

### Passo 2: Instalar o Eclipse

#### No Windows:

- **Descompacte o arquivo**:
   - Após o download, localize o arquivo `.zip` que foi baixado.
   - Clique com o botão direito e escolha **Extrair tudo...**.
   - Selecione o diretório onde você deseja extrair o Eclipse.

- **Executar o Eclipse**:
   - Vá até a pasta onde o Eclipse foi extraído.
   - Clique duas vezes no arquivo `eclipse.exe` para iniciar o Eclipse.

#### No Linux:

- **Descompacte o arquivo**:
   - Abra o terminal e navegue até a pasta onde o arquivo `.tar.gz` foi baixado.
   - Execute o comando:
     ```bash
     tar -xvzf eclipse-inst-linux64.tar.gz
     ```
   - Isso irá extrair o Eclipse na pasta atual.

- **Executar o Eclipse**:
   - Vá até a pasta extraída e execute o Eclipse com o comando:
     ```bash
     ./eclipse
     ```

#### No macOS:

- **Montar o arquivo `.dmg`**:
   - Clique no arquivo `.dmg` que você baixou.
   - Isso abrirá uma janela onde você poderá arrastar o ícone do Eclipse para a pasta **Aplicativos**.

- **Executar o Eclipse**:
   - Vá até a pasta **Aplicativos** e clique duas vezes no ícone do **Eclipse** para abri-lo.

### Passo 3: Configurar o Workspace

- Ao abrir o Eclipse pela primeira vez, ele solicitará que você escolha um **workspace**. O workspace é o diretório onde você armazenará seus projetos Java.
- Você pode aceitar o caminho padrão ou escolher uma nova pasta para armazenar seus projetos.

### Passo 4: Instalar o JDK (Java Development Kit)

Para programar em Java no Eclipse, você precisa ter o **JDK (Java Development Kit)** instalado no seu computador. O Eclipse utiliza o JDK para compilar e executar seus programas Java.

#### No Windows:

- **Baixar o JDK**:
   - Acesse o site oficial da Oracle para baixar o JDK [aqui](https://www.oracle.com/java/technologies/javase-downloads.html).
   - Escolha a versão do JDK que você deseja (recomendo a versão mais recente ou o JDK 11).

- **Instalar o JDK**:
   - Execute o arquivo do instalador e siga as instruções de instalação.

- **Configurar o JDK no Eclipse**:
   - Se o Eclipse não detectar automaticamente o JDK, abra o Eclipse e vá para **Window > Preferences**.
   - Em seguida, vá para **Java > Installed JREs**.
   - Se o JDK não aparecer, clique em **Add** e escolha o diretório onde o JDK foi instalado.

#### No Linux (Ubuntu/Debian):

- **Instalar o JDK**:
   - Abra o terminal e execute o comando para instalar o JDK:
     ```bash
     sudo apt install openjdk-11-jdk
     ```

- **Verificar a instalação**:
   - Após a instalação, você pode verificar se o JDK está corretamente instalado com o comando:
     ```bash
     java -version
     ```

#### No macOS:

- **Baixar e instalar o JDK**:
   - O macOS já inclui uma versão do JDK, mas você pode baixar a versão mais recente no site da Oracle ou usar o Homebrew:
     ```bash
     brew install openjdk@11
     ```

- **Configurar o JDK no Eclipse**:
   - O Eclipse normalmente detecta o JDK automaticamente, mas se necessário, você pode configurar manualmente em **Eclipse > Preferences > Java > Installed JREs**.

### Passo 5: Começar a Programar em Java

- Abra o Eclipse, e na tela inicial, clique em **File > New > Java Project** para criar um novo projeto Java.
   
- Defina um nome para o seu projeto e clique em **Finish**.

- Para adicionar uma classe Java, clique com o botão direito no projeto e selecione **New > Class**.
   
- No editor de código do Eclipse, você pode escrever seu código Java. Para rodá-lo, basta clicar com o botão direito na classe principal (a que contém o método `public static void main(String[] args)`) e escolher **Run As > Java Application**.

### Passo 6: Atualizar o Eclipse (Opcional)

Se você já tem o Eclipse instalado e deseja atualizá-lo:

- Vá em **Help > Check for Updates**.
- O Eclipse verificará se há atualizações disponíveis e, se houver, você poderá instalá-las.

## dowload do diretorio 
