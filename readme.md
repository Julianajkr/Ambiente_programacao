# Preparação de ambiente
### Vamos preparar o ambiente para desenvolvimento de aplicações

#### Nesta ambiente iremos instalar e configurar os seguintes recursos:
- Máquina virtual (virtual box)
- Distribuição linux (ubuntu server)
- Nasm 
- Copilador da linguagem C
- Configurar o ip e a porta de comunicação entre a máquina real e a virtual
- Configurar o acesso via ssh entre o Vscode e o servidor linux
- Instalar as extensões: Material Icon, Nasm, SSH e Linguagem C/C++

#### Máquina Virtual (Virtualbox)

!["Logo Virtualbox"](virtualbox.png)


Máquina virtual é uma ferramenta que permite a criação de novos "computadores" e a instalação de sistemas operacionais, para estudo ou trabalho.

Para o nosso estudo iremos usar o Virtualbox da Oracle.
Para instalar basta fazer o download no link a seguir:

<a href="https://www.virtualbox.org/wiki/Downloads" target="-blank">Virtualbox </a>

##### Criando a Máquina virtual para o nosso estudo

- Configuração:
 > - Nome da máquina: Servidor
 > - Memória: 4gb(4096)
 > - Processador: 2
 > - Disco: 100GB 
 > - IP e Porta do Host: 127.0.0.1 e 22
 > - IP e Porta do Convidado: 10.0.2.15 e 22

 - Tela inicial de configuração
 <img src=telaconfiguracao.png width=500 height=250>

 - Tela configuração do Hardware
 <img src=telaconfiguracao2.png width=500 height=250>

 - Tela de configuração do disco
 <img src=telaconfiguracao3.png width=500 height=250>

 - Tela final de configuração 
 <img src=telaconfiguracao4.png width=500 height=250>

 - Tela inicial de configuração de rede
 <img src=telaconfiguracao5.png width=500 height=250>

 - Tela de configuração de Portas e IP
 <img src=telaconfiguracao6.png width=500 height=250>



 #### Distribuição Ubuntu Server
  Para o nosso estudo iremos utilizar uma distribuição Linux para servidores chamada Ubuntu.
  Acompanhe o processo de instalação
  Faça o download aqui:
  <a href="https://ubuntu.com/download/server" target="_blank"> Ubuntu Server </a>

  <img src=logoubuntu.png width=600 height=200>

  - Acompanhe a instalação

- Tela de Início de instalação
  <img src=telainicio.png>

- Tela de seleção de Idioma
   <img src=telaidioma.png>

- Tela de seleção de teclado
    <img src=idiomaport.png>

- Tela de tipo de instalação
<img src=tipoinsta.png>

- Tela configuração de rede
   <img src=configuracaorede.png>

 - Tela configuração de proxy
  <img src=configuracaodoproxy.png>

 - Tela pacotes de atualização
 <img src=configuracaorede.png>

 - Tela configuração do disco
 <img src=configdodisco.png>

- Tela layout do disco
 <img src=layoutconfigdisco.png>

 - Tela configuração do usuário
 <img src=telausuario.png>

 - Tela configuração o ssh
 <img src=telassh.png>

 - Tela do fim da instalação
 <img src=telafinal.png>












#### Instalação do compilador NASM
O compilador NASM é uma ferramenta que nos permite programar 
em Assembly. Assim é possível criar programas que manipulam
dados que estão nos registradores de processador.

Para instalar o NASM no Ubuntu, usamos o comando:
...
sudo apt install nasm -y
...

#### Instalação do compilador da linguagem C

Em linux, o compilador da Linguagem C é o GCC. Ele é uma
ferramenta importante para o desenvolvimento de programas
em C.

Para instalar use o comando:
...
sudo apt install gcc -y
...


#### Conexão Servidor e VSCode via SSH
Precisamos instalar uma extensão no VSCode para acessar o nosso servidor de forma remota.



!["Extensão SSH"](telassh.png)

Configuração do acesso remoto.

!["Configuração"](configurarextensao.png)
