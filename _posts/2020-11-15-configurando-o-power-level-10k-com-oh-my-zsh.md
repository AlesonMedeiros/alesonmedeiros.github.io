---
title: Configurando o Power Level 10k com Oh My Zsh
---

![Imgur](https://i.imgur.com/GJFnCyo.png)

Que tal dar uma personalizada no seu terminal? Uma maneira de fazê-lo é usando Oh My Zsh juntamente com o tema Power Level 10k! No meu caso, estou utilizando o Deepin que vem com o bash por padrão, assim como a maioria das distros, e nós vamos instalar o **zsh**

>
>sudo apt install zsh zsh-autosuggestions
>

![Imgur](https://i.imgur.com/hyE4IWy.png)

Apos a instalação do zsh, vamos definí-lo como o nosso shell padrão e fazer essa mudança é algo muito simples! Eu cheguei até fazer um vídeo no [Canal do Pinguim Criativo](https://www.youtube.com/pinguimcriativo) fazendo essa personalização e na ocasião eu usei o tutorial do [Blog Diolinux](https://diolinux.com.br/2017/03/alterar-o-terminal-padrao-bash-zsh.html) que na ocasião me parecia a melhor forma de realizar essa mudança no shell, mas um inscrito deixou uma dica muito útil:

![Imgur](https://i.imgur.com/iCnej9Q.png)

E nesse artigo vou seguir essa dica porque é muito mais simples! Vamos no terminal e colocar o comando:

>chsh -s /bin/zsh

![Imgur](https://i.imgur.com/JYEbRkH.png)

Vamos conferir se a mudança foi realizada com sucesso?

>cat passwd

![Imgur](https://i.imgur.com/6PItQ8f.png)

Podemos notar que deu certo, o shell do meu usuário foi alterado com sucesso, e como eu quero utilizar também no usuário root do sistema, vou entrar com o comando

>sudo su

![Imgur](https://i.imgur.com/VYuXoyg.png)

E depois eu repito o mesmo comando da mudança do Shell em modo **Root**. Para efetivar a mudança e da próxima vez que abrirmos o terminal já com zsh, é só fazer um logout no sistema. 

![Imgur](https://i.imgur.com/2qy8uld.png)

Quando entrarmos novamente no terminal após o Login, vamos ter um pequena configuração do .zshrc e temos a opção de utilizar uma configuração simples do zsh.

## Instalando o Oh My Zsh
![Imgur](https://i.imgur.com/Kee6D6n.png)

Vamos entrar no [Github do projeto](https://github.com/ohmyzsh/ohmyzsh) e na parte de baixo da página temos as instruções de como realizar a instalação do **Oh My Zsh**.

>**curl:** sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
>
>**wget:** sh -c "$(wget -O- https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
>
>**fetch:** sh -c "$(fetch -o -https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
>

![Imgur](https://i.imgur.com/ordNN2f.png)

É só aguardar a instalação e configuração básica do script, e no meu caso como eu quero que o usuário root tenha as mesmas configurações, vou repetir esses passos como super-usuário.
<br>

## Instalando as fontes para o nosso terminal

Uma coisa que precisamos fazer é instalar fontes que tenham suporte aos ícones que vamos ter em nosso terminal customizado com o **Oh My Zsh + PowerLevel10k**.

Uma fonte que 

## Instalando o Powerlevel10k
![Imgur](https://i.imgur.com/0YSGEcn.png)
Vamos entrar no [Github do projeto](https://github.com/romkatv/powerlevel10k) e na parte de baixo teremos instruções para quem já utiliza o **Oh My zsh**

![Imgur](https://i.imgur.com/SDhGdj8.png)

Clicando na parte no link, seremos levados até o comando que vamos copiar e colar em nosso terminal

![Imgur](https://i.imgur.com/y2MWfdX.png)
