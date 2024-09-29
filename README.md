# ModPack Server 1 - Guia Completo de Instalação (Windows)

Este guia explica como baixar e instalar um conjunto de mods de Minecraft para rodar em um servidor local ou no seu jogo, com instruções detalhadas para iniciantes que usam Windows.

## O que você vai precisar:

1. **Minecraft Java Edition** já instalado no seu computador.
2. **[Minecraft Forge](https://files.minecraftforge.net/)** - Um carregador de mods que será necessário para rodar os mods.
3. **Git** (opcional) - Usado para clonar o repositório. Caso não queira instalar o Git, você pode fazer o download manualmente do repositório.

### Passo 1: Instalando o Git (Opcional)

Se você quiser usar Git para clonar o repositório, siga as instruções abaixo. Caso contrário, vá para o [Passo 2](#passo-2-baixar-os-arquivos-do-repositório).

1. Acesse o site oficial do Git: [https://git-scm.com/](https://git-scm.com/).
2. Baixe e instale a versão para Windows.
3. Durante a instalação, mantenha as opções padrão e finalize.

### Passo 2: Baixar os Arquivos do Repositório

Você pode baixar os mods diretamente do GitHub de duas maneiras: clonando o repositório com Git ou baixando um arquivo ZIP.

#### Método 1: Clonando o Repositório (com Git)
1. Abra o **Prompt de Comando**:
   - Pressione `Win + R`, digite `cmd` e pressione Enter.
2. No Prompt de Comando, digite o seguinte comando para clonar o repositório:

   ```bash
   git clone https://github.com/kami-note/ModPack-Server-1.git
   ```

Isso baixará todos os arquivos para uma pasta chamada `ModPack-Server-1`.

#### Método 2: Baixando Manualmente
1. Acesse o repositório no GitHub: [https://github.com/kami-note/ModPack-Server-1](https://github.com/kami-note/ModPack-Server-1)
2. Clique no botão `Code` (verde) e depois em `Download ZIP`.
3. Extraia o conteúdo do arquivo ZIP em uma pasta de sua escolha.

### Passo 3: Instalar o Minecraft Forge

O Forge é necessário para que o Minecraft possa carregar os mods. Siga as instruções abaixo para instalá-lo:

1. Acesse o site oficial do Forge: [https://files.minecraftforge.net/](https://files.minecraftforge.net/).
2. Encontre a versão do Forge que seja compatível com a versão do Minecraft que os mods utilizam (verifique isso na documentação do mod ou com o administrador do servidor).
3. Baixe o instalador do Forge clicando em `Installer`.
4. Depois de baixado, clique duas vezes no arquivo `.jar` para iniciar a instalação.
    - Se o Windows pedir como abrir o arquivo, selecione **Java**.
5. Selecione a opção **Install Client** e clique em OK.

### Passo 4: Copiar os Mods para a Pasta do Minecraft

Agora que o Forge está instalado, é hora de adicionar os mods ao Minecraft.

1. Navegue até a pasta `mods` que você baixou do repositório:
    - Se você clonou o repositório, estará dentro da pasta `ModPack-Server-1/mods`.
    - Se você baixou o arquivo ZIP, estará na pasta extraída em `ModPack-Server-1/mods`.
2. Copie todos os arquivos dentro dessa pasta.

3. Agora, você precisa colar esses arquivos na pasta `mods` do Minecraft:
    - Pressione `Win + R`, digite `%appdata%` e pressione Enter.
    - Isso abrirá a pasta **Roaming**. Dentro dela, abra a pasta `.minecraft`.
    - Se não existir, crie uma pasta chamada `mods`.
    - Cole os arquivos copiados dentro dessa pasta `mods`.

### Passo 5: Executar o Minecraft com Forge

Agora que os mods estão no lugar, siga os passos abaixo para rodar o Minecraft com o Forge:

1. Abra o **Minecraft Launcher**.
2. No menu do launcher, abaixo do botão `Play`, você verá um menu de versões. Clique nele e selecione o perfil do **Forge**.
3. Clique em `Play` para iniciar o Minecraft.

Quando o jogo carregar, os mods estarão habilitados. Você pode verificar isso clicando em `Mods` no menu principal do jogo.

### Passo 6: Conectar-se a um Servidor (Opcional)

Se você deseja jogar com esses mods em um servidor, peça ao administrador do servidor o endereço IP e qualquer outra informação necessária. Siga as instruções abaixo para se conectar:

1. Abra o Minecraft e vá para o modo **Multiplayer**.
2. Clique em `Adicionar Servidor`.
3. Insira o endereço IP do servidor e clique em `Concluído`.
4. Selecione o servidor e clique em `Entrar no Servidor`.

## Conclusão

Agora você deve estar pronto para jogar Minecraft com os mods configurados! Se encontrar qualquer problema, você pode abrir uma [issue](https://github.com/kami-note/ModPack-Server-1/issues) no repositório ou pedir ajuda na comunidade do servidor.