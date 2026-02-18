# Como configurar/instalar/usar o `cmatrix` no `Linux Ubuntu`

## Resumo

Neste documento estão contidos os principais comandos e configurações para configurar/instalar/usar o `cmatrix` no `Linux Ubuntu`.

## _Abstract_

_This document contains the main commands and settings for configuring/installing/using the `cmatrix` on `Linux Ubuntu`._


## Descrição [2]

### `cmatrix`

O cmatrix é um programa de linha de comando que simula o efeito visual de código caindo em um terminal, inspirado na interface de computadores vistos em filmes. Ele cria uma matriz de caracteres aleatórios que deslizam pela tela, proporcionando um visual estilizado e retro. O cmatrix é popular entre entusiastas de tecnologia e Linux pela sua estética única e pela capacidade de personalização através de diferentes modos de exibição e opções de configuração.


## 1. Como configurar/instalar/usar o `cmatrix` no `Linux Ubuntu` [1][3]

Para configurar/instalar/usar o `cheese` no `Linux Ubuntu`, você pode seguir estes passos:

1. Abra o `Terminal Emulator`. Você pode fazer isso pressionando:

    ```bash
    Ctrl + Alt + T
    ```

2. Certifique-se de que seu sistema esteja limpo e atualizado.

    2.1 Limpar o `cache` do gerenciador de pacotes `apt`. Especificamente, ele remove todos os arquivos de pacotes (`.deb`) baixados pelo `apt` e armazenados em `/var/cache/apt/archives/`. Digite o seguinte comando: `sudo apt clean` 
    
    2.2 Remover pacotes `.deb` antigos ou duplicados do cache local. É útil para liberar espaço, pois remove apenas os pacotes que não podem mais ser baixados (ou seja, versões antigas de pacotes que foram atualizados). Digite o seguinte comando: `sudo apt autoclean`

    2.3 Remover pacotes que foram automaticamente instalados para satisfazer as dependências de outros pacotes e que não são mais necessários. Digite o seguinte comando: `sudo apt autoremove -y`

    2.4 Buscar as atualizações disponíveis para os pacotes que estão instalados em seu sistema. Digite o seguinte comando e pressione `Enter`: `sudo apt update`

    2.5 **Corrigir pacotes quebrados**: Isso atualizará a lista de pacotes disponíveis e tentará corrigir pacotes quebrados ou com dependências ausentes: `sudo apt --fix-broken install`

    2.6 Limpar o `cache` do gerenciador de pacotes `apt`. Especificamente, ele remove todos os arquivos de pacotes (`.deb`) baixados pelo `apt` e armazenados em `/var/cache/apt/archives/`. Digite o seguinte comando: `sudo apt clean` 
    
    2.7 Para ver a lista de pacotes a serem atualizados, digite o seguinte comando e pressione `Enter`:  `sudo apt list --upgradable`

    2.8 Realmente atualizar os pacotes instalados para as suas versões mais recentes, com base na última vez que você executou `sudo apt update`. Digite o seguinte comando e pressione `Enter`: `sudo apt full-upgrade -y`
    

3. **Instale o pacote cmatrix utilizando o comando**: `sudo apt install cmatrix -y`

Após a conclusão da instalação, você pode executar o `cmatrix` simplesmente digitando `cmatrix` no terminal. Para sair do `cmatrix`, basta pressionar `Ctrl+C`.

Se você quiser ver mais opções e como configurar o comportamento do `cmatrix`, pode consultar a página de manual digitando man `cmatrix` no terminal.

### 2. Código completo para configurar/instalar/usar

Para configurar/instalar/usar o `cheese` no `Linux Ubuntu` sem precisar digitar linha por linha, você pode seguir estas etapas:

1. Abra o `Terminal Emulator`. Você pode fazer isso pressionando:

    ```bash
    Ctrl + Alt + T
    ```

2. Digite o seguinte comando e pressione `Enter`:

    ```
    sudo apt clean                                                            
    sudo apt autoclean
    sudo apt autoremove -y
    sudo apt update
    sudo apt --fix-broken install
    sudo apt clean
    sudo apt list --upgradable
    sudo apt full-upgrade -y
    sudo apt install cmatrix -y
    cmatrix
    ```


## Referências

[1] OPENAI. ***Install Cheese on Ubuntu.*** Disponível em: <https://chatgpt.com/c/9c4f8197-ceac-458e-ae02-695fb7c9d67a> (texto adaptado). Acessado em: 23/04/2023 17:11.

[2] OPENAI. ***Vs code: editor popular.*** Disponível em: <https://chat.openai.com/c/b640a25d-f8e3-4922-8a3b-ed74a2657e42> (texto adaptado). Acessado em: 23/04/2024 17:10.

