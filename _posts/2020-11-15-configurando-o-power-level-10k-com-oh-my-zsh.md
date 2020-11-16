---
title: Configurando o Power Level 10k com Oh My Zsh
---

![Imgur](https://i.imgur.com/GJFnCyo.png)

Que tal dar uma personalizada no seu terminal? Uma maneira de fazê-lo é usando Oh My Zsh juntamente com o tema Power Level 10k! No meu caso, estou utilizando o Deepin que vem com o bash por padrão, assim como a maioria das distros, e nós vamos instalar o **zsh**

>sudo apt install zsh zsh-autosuggestions

<br>
![Imgur](https://i.imgur.com/hyE4IWy.png)

Apos a instalação do zsh, vamos definí-lo como o nosso shell padrão e fazer essa mudança é algo muito simples! Eu cheguei até fazer um vídeo no [Canal do Pinguim Criativo](https://www.youtube.com/pinguimcriativo) fazendo essa personalização e na ocasião eu usei o tutorial do [Blog Diolinux](https://diolinux.com.br/2017/03/alterar-o-terminal-padrao-bash-zsh.html) que na ocasião me parecia a melhor forma de realizar essa mudança no shell, mas um inscrito deixou uma dica muito útil:

![Imgur](https://i.imgur.com/iCnej9Q.png)

E nesse artigo vou seguir essa dica porque é muito mais simples! Vamos no terminal e colocar o comando:

>chsh -s /bin/zsh

<br>
![Imgur](https://i.imgur.com/JYEbRkH.png)

Vamos conferir se a mudança foi realizada com sucesso?

>cat passwd

<br>
![Imgur](https://i.imgur.com/6PItQ8f.png)

Podemos notar que deu certo, o shell do meu usuário foi alterado com sucesso, e como eu quero utilizar também no usuário root do sistema, vou entrar com o comando

>sudo su

<br>
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

<br>
![Imgur](https://i.imgur.com/ordNN2f.png)

É só aguardar a instalação e configuração básica do script, e no meu caso como eu quero que o usuário root tenha as mesmas configurações, vou repetir esses passos como super-usuário.
<br>

## Instalando as fontes para o nosso terminal

Uma coisa que precisamos fazer é instalar fontes que tenham suporte aos ícones que vamos ter em nosso terminal customizado com o **Oh My Zsh + PowerLevel10k**, do contrário ficaremos com um terminal meio bugado.

![Imgur](https://i.imgur.com/bEMdcef.png)

Uma fonte que eu recomendo é Hack, que pode ser facilmente baixada no repositório do Nerd Fonts
![Imgur](https://i.imgur.com/LfjlrIi.png)

Após o download é só instalar no sistema!

![Imgur](https://i.imgur.com/BJhx1Mt.png)

## Instalando o Powerlevel10k
![Imgur](https://i.imgur.com/0YSGEcn.png)
Vamos entrar no [Github do projeto](https://github.com/romkatv/powerlevel10k) e na parte de baixo teremos instruções para quem já utiliza o **Oh My zsh**

![Imgur](https://i.imgur.com/SDhGdj8.png)

Clicando na parte no link, seremos levados até o comando que vamos copiar e colar em nosso terminal
![Imgur](https://i.imgur.com/y2MWfdX.png)

![Imgur](https://i.imgur.com/72kcjgQ.png)

Após a instalação, vamos abrir o arquivo .zshrc conforme indicado no manual

![Imgur](https://i.imgur.com/RhtArTc.png)

para isso é só usar o seguinte comando

>nano ~/.zshrc

<br>
![Imgur](https://i.imgur.com/wRJSPuT.png)

E na linha indicada `ZSH_THEME=` é só colocar o nome do tema **"powerlevel10k/powerlevel10k"**

![Imgur](https://i.imgur.com/TVj5STV.png)

Após realizar a alteração é só salvar com o atalho `Ctrl + S` e fechar. No meu caso eu vou entrar como Root e realizar também o mesmo procedimento para que quando eu entrar como superusuário também tenha a mesma personalização.

## Configurando o tema

Depois de salvar as alterações e fecharmos o terminal, quando for aberto novamente ele iniciará os scripts e apresentará as opções de personalização com detalhes que podemos escolher

![Imgur](https://i.imgur.com/BEsvnuY.png)

![Imgur](https://i.imgur.com/dlgmBMI.png)

![Imgur](https://i.imgur.com/k05L963.png)

![Imgur](https://i.imgur.com/hKkeoO0.png)

![Imgur](https://i.imgur.com/lEVwmUw.png)

![Imgur](https://i.imgur.com/rzoTpj1.png)

![Imgur](https://i.imgur.com/8AQUsGi.png)

![Imgur](https://i.imgur.com/clT6QnM.png)

![Imgur](https://i.imgur.com/rxEpa0G.png)

![Imgur](https://i.imgur.com/rsmVX7I.png)

![Imgur](https://i.imgur.com/80bnMh7.png)

![Imgur](https://i.imgur.com/T2GLT7D.png)

![Imgur](https://i.imgur.com/cpdg5EO.png)

![Imgur](https://i.imgur.com/HKCMZDF.png)

![Imgur](https://i.imgur.com/bw59RR3.png)

![Imgur](https://i.imgur.com/3Ruj7mZ.png)

![Imgur](https://i.imgur.com/HSk2pgO.png)

![Imgur](https://i.imgur.com/mMP4gmN.png)

![Imgur](https://i.imgur.com/BFqYLJH.png)

![Imgur](https://i.imgur.com/bqrUWPx.png)

Em cada tela temos as opções de como teremos o terminal no final da configuração e também onde o arquivo gerado foi salvo. Caso você enjoe da aparência do terminal e queira mudar algum detalhe da sua configuração é só digitar `p10k configure` e ele vai iniciar o script de configuração e ao final irá gerar um novo arquivo.

Espero que você tenha gostado desse artigo e que seja muito útil nas suas personalizações e prints que você vai enviar para gente postar nas redes sociais do [Pinguim Criativo](https://linktr.ee/pinguimcriativo).

Aquele abraço e até a próxima!
