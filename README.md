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

* Spa (Single-Page Aplication) é uma unica pagina que Atualiza os Dados De Forma Necessária, Por Exemplo: Quando Eu For Alterar algum Conteudo Na Minha Aplicação, o Header vai manter, o rodape tbm. So Vai Mudar o Conteudo em Si, Para não Pesar no Carregamento e deixar nosso aplicação em um ritmo Rapido...

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


#### Explicação Sobre o TypeScript (8:55) 😵

* Ele é usado Muito em Questão parar fazer Manutenção Nos Codigos
* As Tipagem Geralmente Começam Com Letras Maisculas.

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
* Adicionando as Imagens Svg na pasta `Public`, Apos colocar as  img na Pasta Public posso passar no `src` da tag img `/nomedaimagem.svg` que ja vai buscar na pasta public
* Estilizando o Header
* No React Inves de Utilizar class é utilizado ClassName
* usando o `new Date().toLocaleDateString()` para capturar a data atual, no header
* importando o `format` do `data/fns/format` e importanto o pt-BR do `date-fns/locale/pt-BR`.


### Criando o Componente de Player (48:15) 😵

* Criando os Styles no Player
* Criando As Estruturas Html, Button, e  Adicionando as `img.svg` nos Button
* Depois de Pronto as Estilização
* Vamos começar a Configurar nossa `Api` em `Json`.
* Baixando o Arquivo Json com todos os dados do nosso projeto, sera Adicionado na Raiz do Projeto.
* Utilizando o `json-server` que cria uma API "Fake".
* Instalando o Json server com `yarn add json-server -D`
* Criando um Script no `package.json` que é o comando `"server": "json-server server.json -w  -d 750 -p 3333 "
* Rodando o `yarn server`.
* Explicando o Consumo da API (1:09:10)
* Utilizando a Função de `useEffect`
* iniciando a build do projeto `yarn build`
* Utilizando Geração Estatica no Projeto
* Usando a Função `getStaticProps()`.
* Coletou os Dados de `API`

<hr>

# Aula 3 🚀

### O Que Vamos Ver ? 🎬 

* Vamos Finalizar a Home Page do Projeto
* Converte os dados em Interface

### Tipando A Função `getStaticProps()` (6:10) 😵

* Fazendo A Tipagem `HomeProps` para o Home
* Manipulando o `localhost/3333`colocando limit, ordenando por ordem de publicação, e ordem decrescente.
* Criando a Pasta `services`, colocando dentro um  arquivo `api.ts1`
![Screenshot_30](https://user-images.githubusercontent.com/78617974/116811301-091a8180-ab1f-11eb-90ae-e43e003e699a.jpg)
* Instalando o Axios (é uma Biblioteca Para Fazer Requesição HTTP assim como o fetch, porem com mais funcionalidade.
### Resultado Final Utilizando Axios, como Ficou a Manipulação da `API`
![Screenshot_31](https://user-images.githubusercontent.com/78617974/116811355-4252f180-ab1f-11eb-8187-7f0a8e4ef43c.jpg)


### Formatação Dos Dados 😵

* Importando o `data-fns` e pegando o format e o ParseISO, O ParseISO vai servir para pegar uma data e converter o date no javaScript.


![Screenshot_32](https://user-images.githubusercontent.com/78617974/116811597-9d391880-ab20-11eb-80dd-e21fc697e3bf.jpg)

* Criando uma Pasta `utils`dentro da nossa aplicação, e dentro criando o arquivo `convertDurationString.ts`, essa função vai ser utlizada para converter os dados da duração de segundos para horas e minutos.

![Screenshot_33](https://user-images.githubusercontent.com/78617974/116811792-9a8af300-ab21-11eb-92e4-20fd548e77fd.jpg)

* Resultado Final da Formatação dos dados  na constante `episodes`. 😍😍

![Screenshot_34](https://user-images.githubusercontent.com/78617974/116811883-08371f00-ab22-11eb-9b58-3686322c4ada.jpg)

* Como Mudamos o Formatado dos Dados nossa tipagem vai mudar tbm.

![Screenshot_35](https://user-images.githubusercontent.com/78617974/116811942-6401a800-ab22-11eb-8c15-0c30a01db622.jpg)

### Começando a Parte Estrutural (30:10)  😵😵

* Importanto o Image do Next, é colocado no lugar da tag `img` serve para automatizar as imagens pesadas.
![Screenshot_37](https://user-images.githubusercontent.com/78617974/116812494-631e4580-ab25-11eb-852f-f9d2147bb26e.jpg)
*  Criando um Arquivo na Raiz do Projeto Chamado `next.config.js`
![Screenshot_36](https://user-images.githubusercontent.com/78617974/116812437-22bec780-ab25-11eb-86b1-e2e9f630b27e.jpg)

#### Começando a Estilização (43:30)  😵😵









