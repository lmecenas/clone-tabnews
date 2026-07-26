# Dia 2
Dia de instalação:
- instalação do nvm install lts/hydrogen
- default alias do lts/hydrogen
- criação do arquivo .nvmrc e o comando nvm install que identifica esse arquivo (RC vem de Run commands):
    1. Run Commands (Comandos de Execução) – A explicação mais técnica e moderna.
    Significa que o arquivo contém uma lista de comandos que serão executados automaticamente quando um programa ou shell é iniciado.

    .bashrc → Comandos executados toda vez que um terminal interativo Bash é aberto.

    .npmrc → Configurações que o npm lê e aplica antes de executar seus comandos.

    .nvmrc → Não é um arquivo de comandos, mas sim um arquivo de configuração que o NVM (Node Version Manager) lê para saber qual versão do Node usar (a lógica é a mesma: ele é "lido" para configurar o ambiente).

# Dia 3
    Ferramentas utilizadas:
    - Next.js
    - React
criação do manifesto( lista de depedencias do projeto, parecido com o requirements.txt em python):
    - npm init
    - npm install next@13.1.6
    - npm install react@18.2.0
    - npm install react-dom@18.2.0

# Dia 4

## O Que é de fato um Serviço Web?
Como a internet funciona de fato? e por trás disso, existem os protoclos.
HTTP -> HYPERTEXT TRANSFER PROTOCOL, FTP -> FILE TRANSFER PROTOCOL, SMTP -> SIMPLE MAIL TRANSFER PROTOCOL.

Protocolo é um acordo, que definem regras de como será a regra da comunicação.
Exemplo simples, "Telefone sem Fio" brincadeira de criação.

TCP - Error Recovery
Podemos montar um protocolo em cima do outro.
HTTP -> TCP-> IP(Internet Protocol)
Em cima do protocolo IP, não necessariamente você vai querer usar o protocolo TCP, porque para garantir o Erro Discovery, essa mensagem tem um "custo", deixa a transmissão mais devagar. E em alguns casos, você não quer pagar por esse seguro, para ter uma comunicação mais rápida, por exemplo: Vídeo em ZOOM.
geralmente nesses casos, são utilizados o UDP -> User Datagram Protocol.

-> Criação da pasta "pages" e do arquivo index.js

Next -> Entrega a Conexão, os objetos são entregues pelo React.

Desafio: 
