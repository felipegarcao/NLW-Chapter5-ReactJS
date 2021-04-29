# O Que Vamos Aprender Durante o Evento ? 🎬

* Configurar nosso Ambiente De Desenvolvimento, As Ferramentas que vamos Trabalhar
* Entender o Fluxo Normal de Uma Api. Vamos Utilizar um "Back-End" fictício.
* Trabalhar com Context Api.
* Como Trabalhar com react com as tag `Audio`, com next, previous, shuffle e repeat.
* Entender os Principais Conceitos Do React.
* Criar o Projeto com `Next.js`

 ## Resumo do Que é o React
 
* É Basicamente uma Biblioteca Feita para construção de Interface que São Altamentes Interativas.


# Aula 1 🚀

* Instalando o `Node.js`
* Inst.. Yarn ( Ele é um Gerenciador De Pacotes Pro Node.js) o Yarn Em Mais Performático e tbm ele tem umas funcionalidade A+ que o Npm

## Explicando Fluxo da Api (21:20)

* Explicou o Que é um Json (JavaScript Object Notation), é a Maneira que  Travega dados entre o Back-End e o Front-End

* Apartir que Desenvolvemos o Back-end e ele fornece dados é chamado de `API RESTful` (Quando a API é RESTful é cheia de "Regrinhas" chatas)

* Spa (Single-Page Aplication) é uma unica pagina que Atualiza os Dados De Forma Necessária, Por Exemplo: Quando Eu For Alterar algum Conteudo Na Minha Aplicação, o Header vai manter, o rodape tbm. So Vai Mudar o Conteudo em Si, Para não Pesar no Carregamento e deixar nosso aplicação em um ritmo lento...

## Iniciando o Projeto React (30:28)

* Com Node.js Ja Instalado.

* Para Inciar o Projeto Com React Vamos utlizar o Pacote do site `create-react-app.dev`, Utilizando o Comando `npx create-react-app NomeDaPastaDoProjeto`.

* `yarn start` para iniciar o Server Do Projeto, Para ver O que Esta Saindo No Browser.

## ❌  Deletando Arquivos Desnecessário (35:50)

* Explicando os Arquivos, que não foram excluidos.

* Um Componente nada mais é do que uma função que Retorna HTML, Muito Usado Para Repetir, Como por Exemplo Um Botão com o mesmo formato de uma Pagina Anterior, é Melhor Criar ele como componente Para Fazer A Manutenção Mais Rapida e Pratica.

* Propriedade é a informação que repassa de um Componente Para o Outro, Simples Assim. Como Por Exemplo no HTML a tag `img` precisa de uma atributo que no caso é o `src`, no React, Chamamos esse Atributo do HTML de Propriedade.

* No React Não Podemos Colocar um Elemento de Baixo do outro, Sempre tem que ter um empacotamento, com por exemplo uma div ou um Fragamento `<> </>`.

* Estado é Basicamente a Forma De Manipular Informações de dentro de um Componente

##### Criando o Primeiro Exemplo de Estado (50:35)

* O Que é SSR(Server-side Rendering) 

## Iniciando o Projeto Com o `next.js` (1:09:20)

* `npx create-next-app NomeDaPasta`

* ❌  Deletando Arquivos Desnecessário !

* Rodando o Yarn Dev, ira abrir um servidor de Desenvolvimento.

 <hr/>
 
 # Aula 2 🚀

### O Que Vamos Ver ? 🎬

* Criar Estilos Globais
* o Por que De Esta Utilizando TypeScript ?
* Criar os Componentes de Header e Player.
* Configurar Api com Json.
* SPA vs SSR vs SSG.
* Gerar Home De Forma Estatica.
* Criando Build do Projeto.
* Executando Build Do Projeto.


#### Explicação Sobre o TypeScript (8:55)

* Ele é usado Muito em Questão parar fazer Manutenção Nos Codigos
* As Tipagem Geralmente Começar Com Letras Maisculas.

![Screenshot_18](https://user-images.githubusercontent.com/78617974/116110495-1ef5f580-a68c-11eb-898f-4119d87e5673.jpg)

* Chamar A Função Que Estiver Com Tipagem, em outro Lugar ira dar Erro se não passar Parametro.
*  Criando a Pastar `src`, a pasta pages tem que existir dentro da raiz do projeto ou dentro da pasta do  `src`.
* Instalando o Sass e convertendo os css para Sass.
* Adicionando Variaveis de Cores (25:15)
* Explicando A Medida Rem (27:10)
* Pegando fontes do google Lexend para titulos e inter para textos.
* o Arquivo App é o principal, fica por volta de todas nossas paginas.
* Criando A Pagina de Componentes  (37:35)
* Criando a Estrutura do Header (39:20)
* Adicionando as Imagens Svg no `Public`, Apos colocar as  img na Pasta Public posso passar no `src` da tag img `/nomedaimagem.tipo` que ja vai buscar na pasta public

# Continuar 41:12
