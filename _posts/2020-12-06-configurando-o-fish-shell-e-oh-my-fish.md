---
title: Configurando o Fish Shell e Oh My Fish
---

![Imgur](https://i.imgur.com/Wq1YTvX.png)

Se você assim como eu está descobrindo os super poderes do shell e tendo cada vez menos medo de utilizar o terminal, que tal testar o fish e deixar o seu terminal bem mais interativo e muito mais amigável? E se adicionarmos a isso a possibilidade de deixá-lo com o visual ao nosso gosto? Se você gostou da ideia, então siga-me os bons!

### Meu dia a dia com o fish shell

Eu não sei você **amigo internauta**, mas eu tenho uma dificuldade em gravar os comandos e volta e meio me vejo tendo que recorrer ao google ou o guia foca para lembrar ou simplesmente ir errando muito até acertar. 😂

Fazendo meus testes e fuçando no google eu me deparei com o fish shell e ao ir pesquisando e ir testando vi que seria muito interessante utilizá-lo em meu pc em todas as distros que utilizo **(atualmente estou no openSUSE Tumleweed e o Debian Testing)**.

>O fish é um shell de linha de comando inteligente e amigável para macOS, Linux e o resto da família. fish inclui recursos como destaque de sintaxe, autosuggest-as-you-type e preenchimentos de guias sofisticados que simplesmente funcionam, sem a necessidade de configuração.

### Instalando o fish shell

A instalação do fish é super simples em qualquer distro, no meu caso estou fazendo isso no openSUSE e o comando é `sudo zypper in fish`

![Imgur](https://i.imgur.com/Q7rzNm0.png)

Depois de instalar o fish precisamos apenas defini-lo como nosso shell utiliando o comando `chsh -s /usr/bin/fish`. Caso deseje utilizar ele também para o terminal no modo root é repetir os comandos.

![Imgur](https://i.imgur.com/JnrGMVK.png)

Após fazer isso é só reinciar ou encerrar a sessão para que as alterações terão efeito e na próxima vez que você abrir o terminal já será apresentado ao fish!


### Instalando e configurando o Oh My Fish

![Imgur](https://i.imgur.com/qtQdmDq.png)

Para personalizarmos o nosso terminal, vamos instalar o [Oh My Fish](https://github.com/oh-my-fish/oh-my-fish) que já trás uma grande quantidade de temas que podemos utilizar!

Na página do Github do projeto, nós encontramos as instruções de instalação e opções de personalização. Para iniciar é só copiar o comando `curl -L https://get.oh-my.fish | fish` e colar no terminal e aguardar o script trabalhar

![Imgur](https://i.imgur.com/Gf5kNVd.png)

Na parte de baixo da página encontramos as instruções para utilizarmos no nosso Oh My Fish, entre elas temos o plugin para instalação de temas no nosso Shell

![Imgur](https://i.imgur.com/vyFa1n4.png)

Temos a opção de verificar os temas que estão disponíveis para utilizarmos no nosso Shell, é só clicar em [preview available themes](https://github.com/oh-my-fish/oh-my-fish/blob/master/docs/Themes.md) ou utilizar o comando `omf theme`

Eu escolhi o tema [**fishbone**](https://github.com/oh-my-fish/oh-my-fish/blob/master/docs/Themes.md#fishbone)

![Imgur](https://i.imgur.com/lpcqiY4.png)

Para realizar a instalação de qualquer tema é só digitar no terminal `omf install "nome do tema"`, no nosso caso é só digitar no terminal: `omf install fishbone` e aguardar o script trabalhar!

![Imgur](https://i.imgur.com/Jf1VoPV.png)

E pronto! Já temos o tema instalado, e para verificarmos a saudação é só fecharmos o terminal e abrir de novo ou a depender do caso podemos encerrar a sessão e abrir novamente

![Imgur](https://i.imgur.com/quJIMmQ.png)

Para instalar tema para usuário root é só seguir os mesmo passos da instalação do usuário comum

![Imgur](https://i.imgur.com/J8pi7HB.png)

E voilà! Temos o nosso **Oh My Fish** devidamente instalado e personalizado!

![Imgur](https://i.imgur.com/NZYyxbw.png)

Espero que você tenha gostado desse artigo e que seja muito útil nas suas personalizações e prints que você vai enviar para gente postar nas redes sociais do Pinguim Criativo 😋

Aquele abraço e até a próxima!
