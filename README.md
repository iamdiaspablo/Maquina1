<h1 align="center"># INSTALAÇÃO ORACLE LINUX </h1>

## Realize o download da ISO do sistema em: 
```bash
https://yum.oracle.com/oracle-linux-isos.html
``` 
e baixe a última versão estável disponível.

## Realize o download da VM Box para rodar seu sistema Linux no windows, acesse:
```bash
https://www.virtualbox.org/wiki/Downloads
```
e baixe a versão Windows hosts.

## Configurando a VM
Após baixado e instalado o VM Box, na tela inicial clique em "novo" e nomeei sua máquina.

Em seguida clique em "next" e selecione o tamanho da memória e clique em "next".

Clique em criar um novo disco rígido virtual agora.

Selecione VDI (VirtualBox Disk Image) e clique em "próximo".

Selecione Dinamicamente alocado e clique em "próximo(n)".

Selecione o tamanho do disco da VM e clique em "criar".


## Instalando Linux

Deixe o idioma de instalação em English e clique em "Done"

## Keybord

Para o uso do teclado em português basta clica na opção "+" e selecionar "Portuguese (Brazil)". Em seguida clique em cima do idioma e selecione a opção "^" para movê-lo para a primeira posição de idiomas. E clique em "done"

## Configuração de data & hora
Em City selecione a cidade que contenha seu fuso horário local e clique em done

## Selecionando software de instalação
Em Software Selection selecione a opção de software desejada. Nessa documentação será citada a minimal install a qual seria o instalação do sistema linux sem interface gráfica. 

## Installation Destination
Selecione o disk e clique em "automactic"

## Network & Hostname
Para manter conexão com a internet, clique ligue o botão "off" e deixe em "on" e clique em done.

## Definir senha para usuário root
Em Root Password defina uma senha root, repita e clique em done. 

## Criando usuários
Para criar um usuário clique em Create User e preencha nome de usuário.
Marque a opção "make this user admistrator" para conceder acesso de admistrador ao usuário caso necessário.
Crie uma senha e clique em done.

## Após todos os ajustes:
Clique em begin installation e após instalação de todos os itens, clique em "reboot system" para o sistema reiniciar e ficar pronto para uso.
