# Sumário

* [Sobre o autor](#introdução)
* [Primeiro Semestre - Lumen](#em-2019-2)
* [Segundo Semestre - AlgoPositivo](#em-2020-1)
* [Meus Principais Conhecimentos](#meus-principais-conhecimentos)
* [Contatos](#contatos)

# Denis Ferreira Lima

## Introdução  
<div>
	<img src="/img/me.jpg" alt="Foto de perfil" width=150 height=150 />
	<p>Estudante de Análise e Desenvolvimento de Sistemas na FATEC Jessen Vidal, atualmente cursando o 5º semestre, estagiário de desenvolvimento de scripts para automação RPA tanto desktop quanto web. Curto bastante a área de desenvolvimento web, com foco principal em ReactJS, VueJS, NodeJS, tanto em Javascript quanto em Typescript, porém sempre buscando novos aprendizados! </p>
</div>

### Em 2019-2
![Logo do projeto](/img/capa.png)

### Parceiro Acadêmico

A [Faculdade de Tecnologia de São José dos Campos — Prof. Jessen Vidal](https://fatecsjc-prd.azurewebsites.net/) que pertence ao Centro Paula Souza, oferece cursos de graduação para formar tecnólogos.  
Para acompanhar o crescimento da chamada indústria 4.0, a instituição propôs adotar uma estratégia de Aprendizado por Projeto Integrador (chamado API), e nesse segundo semestre de 2019, iniciou esse projeto e se disponibilizou como empresa parceira.

### Visão do Projeto

O projeto desenvolvido pelo grupo, denominado Lumen, tem o objetivo de criar uma solução de IoT (Internet das Coisas) acessível que seja capaz de atender a demanda de todas as categorias de clientes, sejam clientes residenciais ou a própria indústria 4.0.  
O projeto surgiu da necessidade de acompanhar a evolução da tecnologia, com a crescente quantidade de dispositivos inteligentes no mercado. A proposta do projeto integrador era do desenvolvimento de um sistema de automação residencial, no qual há um hardware integrado à um aplicativo de celular, que controla o mesmo.  
O principal diferencial do produto é a facilidade de manuseio com uma interface intuitiva, além de contar com um custo baixo no preço do hardware.  
![Tela do aplicativo](/img/tela.png)  
A aplicação foi desenvolvida com a proposta de criar uma automação residencial, controlando uma luz LED RGB a partir de qualquer ponto da sua casa, utilizando uma comunicação Bluetooth, além de ter a opção de controlar um cooler como adicional.  
Também foi adicionado ao produto uma opção de realizar um feedback através de avaliação por estrelas, numeradas de 1 (não gostei) à 5 (adorei), para que assim possamos verificar possíveis melhorias futuras.

### Link do Github
<a href="https://github.com/Denis-Lima/Lumen" target="_blank"><img src="https://pbs.twimg.com/profile_images/1414990564408262661/r6YemvF9_400x400.jpg" alt="Logo do Github" width="40" style="margin: 0px 15px 0px 0px;" /><span>&nbsp;&nbsp;&nbsp;</span><span>Lumen</span></a>

#### Tecnologias adotadas na solução

As tecnologias adotadas para a solução foram as seguintes:  
* <img src="https://appinventor.mit.edu/images/logo.png" alt="Logo do MIT AppInventor" width="200" /> [MIT App Inventor](https://appinventor.mit.edu/), uma ferramenta desenvolvida pela Google e atualmente mantida pelo MIT, para confecção do aplicativo, que possui uma interface amigável para pessoas com pouco conhecimento de programação. O App Inventor é uma ferramenta para construção de aplicativos por meio de blocos de programação, tanto na parte lógica quanto na parte visual.  

* <img src="https://www.gstatic.com/devrel-devsite/prod/v509a5f4800978e3ce5a1a5f2c1483bd166c25f20fdb759fe97f6131b7e9f1f00/firebase/images/lockup.png" alt="Logo do Firebase" width="200" /> [Firebase Realtime Database](https://firebase.google.com/products/realtime-database?gclsrc=aw.ds&gclid=CjwKCAjw7fuJBhBdEiwA2lLMYcBC2UdWCsUTEdepZcIPR9r3gmOKo94uHC1fBV31fnwWsBQa1INL4xoCJ9UQAvD_BwE), um banco de dados NoSQL hospedado na nuvem, utilizado para armazenar as avaliações dos usuários (1 à 5 estrelas), via Wi-Fi.  

* <img src="https://cdn.arduino.cc/header-footer/prod/assets/headerLogo-arduino.svg" alt="Logo do Arduino" width="200" /> [Arduino IDE](https://www.arduino.cc/en/software), para a criação da lógica que acompanha o hardware.  

* <img src="https://cdn.shopify.com/s/files/1/0438/4735/2471/products/A000066_03.front_763x573.jpg?v=1629815860" alt="Imagem do Arduino Uno Rev3" width="200" /> [Arduino Uno Rev3](https://store.arduino.cc/products/arduino-uno-rev3/), que é uma placa com um microcontrolador, que ficará responsável pelo controle das peças físicas (LED's e cooler), acompanhado do script criado junto da Arduino IDE.  

* <img src="https://s3-sa-east-1.amazonaws.com/multilogica-files/Modulo_Bluetooth_HC-05_M.jpg" alt="Imagem do módulo Bluetooth" width="200" /> Módulo Bluetooth HC05, para integração entre o equipamento físico (hardware) e o aplicativo. Ideal para comunicação sem fio simples e de média distância. Além de um sensor de umidade e temperatura DHT11 para automação do cooler, resistores e jumpers para conexão eletrônica entre os componentes, LED RGB e um cooler.  

* <img src="https://www.alura.com.br/artigos/assets/formacao-linguagem-c-plus-plus/img-01.png" alt="Logo do C++" width="200" /> Linguagem de programação C++, utilizada para criar a lógica do código fonte que acompanha o Arduino.  
<br/>
<p align="center">
	<img src="/img/Arquitetura.jpeg" alt="Arquitetura da aplicação">
	<p align="center"><strong>Arquitetura da aplicação</strong></p>
</p>


#### Contribuições pessoais

Para a construção do projeto, deixei minhas contribuições tanto no software quanto no hardware.  
Foi pensado nessa comunicação Bluetooth, o uso de envio de dados simples, como uma string "B", para informar que a cor azul (Blue) foi acionada (ligada ou desligada), uma string "R" para o vermelho (Red) e assim por diante.  
Realizei a integração do aplicativo com o hardware, para criar uma comunicação entre os mesmos via Bluetooth, utilizando os recursos de Bluetooth que o próprio App Inventor oferece, e os recursos de Bluetooth que o Arduino oferece.  
Também contribui com a montagem física do projeto, onde realizei o processo de montagem do LED na placa do Arduino e no módulo Bluetooth, utilizando corretamente os devidos resistores.

#### Hard Skills

* Integração de módulo Bluetooth com software: Sei fazer com ajuda.  
* Programação em microinformática: Sei fazer com autonomia.  
* Construção de aplicativo usando App Inventor: Sei fazer com autonomia.  
* Contrução de circuitos com arduino: Sei fazer com ajuda.  
* Controle de versão com Git e Github: Sei fazer com ajuda.  
* Integrações com Firebase: Sei fazer com ajuda  
* Documentação do projeto: Sei fazer com ajuda  
* Desenvolvimento por programação em blocos: Sei fazer com autonomia

#### Soft Skills  

* Empatia - Para entender o problema que o cliente queria que fosse resolvido, necessário durante toda a construção do projeto.  
* Trabalho em equipe - Fundamental para que o projeto chegue até o cliente dentro do prazo e funcionando.  
* Perseverança - Por mais que a equipe havia tido pouco contato com o mundo da programação e tudo parecia difícil, nunca desistir foi essencial para o sucesso da equipe.  
* Gerenciamento de tempo - Todos os membros tiveram que aprender a gerenciar melhor o tempo próprio para não deixar a equipe na mão.  
* Autodidatismo - Fundamental para a nossa área, buscando aprender novas ferramentas e linguagens afim de solucionar o problema da melhor forma.
##

### Em 2020-1

### Parceiro Acadêmico

O [SPC Brasil](https://www.spcbrasil.org.br/) está junto com os brasileiros há mais de 60 anos, prestando serviços especializados a toda a sociedade. Oferecem soluções aos consumidores e empresários com o objetivo de facilitar a realização de negócios.  
Mais do que auxiliar as empresas na concessão de crédito, o SPC Brasil apoia os processos de tomada de decisão com informações, inteligência, soluções de negócio e identidade digital.  

<p align="center">
	<img src="/img/Previa.gif" alt="Prévia da solução">
	<p align="center"><strong>Prévia da solução</strong></p>
</p>

### Visão do Projeto

Com a mudança do modelo de operação do Cadastro Positivo, surgiu a necessidade de realizar uma gestão da informação mais eficaz para garantir a qualidade, uso adequado e gerar valor através dos dados.  
A partir desta necessidade, surgiu este projeto, denominado AlgoPositivo (Algoritmo Positivo) que tem o objetivo de analisar os dados pagamentos dos clientes de forma anônima, respeitando a LGPD. A partir destes dados, o programa irá gerar informações e indicadores de negócios, que avaliará os clientes com base nesse perfil de pagamentos traçado. Os indicadores criados poderão ser utilizados para auxiliar a tomada de decisões de oferecer ou não produtos e serviços para determinado público, além de ajudar a analisar a criação de novos produtos com base na região dos clientes.

#### Link do Github
<a href="https://github.com/Denis-Lima/PI_ADS_2Sem" target="_blank"><img src="https://pbs.twimg.com/profile_images/1414990564408262661/r6YemvF9_400x400.jpg" alt="Logo do Github" width="40" style="margin: 0px 15px 0px 0px;" /><span>&nbsp;&nbsp;&nbsp;</span><span>AlgoPositivo</span></a>

#### Tecnologias adotadas na solução

As tecnologias adotadas para a solução foram as seguintes:  
* <img src="https://www.python.org/static/img/python-logo.png" alt="Logo do Python" width="200" /> [Python](https://www.python.org/), uma linguagem de programação simples, intuitiva e de fácil aprendizado, escolhida pela equipe para que o foco da solução seja a geração dos indicadores de negócios.  

* <img src="https://www.sqlite.org/images/sqlite370_banner.gif" alt="Logo do SQLite3" width="200" /> [SQLite3](https://www.sqlite.org/index.html), um banco
de dados relacional independente, por conta de sua leveza e velocidade, já que o projeto não necessitaria de algo muito mais robusto, uma vez que serviria apenas para guardar os endereços de emails que seriam enviados.  
* Para o envio de email foi usado a biblioteca embutida no Python chamada smtplib, simples de configurar e utilizar.  

<br/>
<p align="center">
	<img src="/img/Arquitetura de aplicação2.png" alt="Arquitetura da aplicação">
	<p align="center"><strong>Arquitetura da aplicação</strong></p>
</p>

#### Contribuições pessoais

Para a construção do projeto, minha contribuição foi focada na construção do módulo de envio de emails, para que pudesse ser facilmente utilizado pelo restante da equipe, além de auxiliar na definição dos indicadores de negócios que seriam criados.

#### Hard Skills

* Programação de scripts em python: Sei fazer com ajuda.  
* Controle de versão com git e Github: Sei fazer com ajuda.
* Entendimento do protocolo de envio de e-mails: Sei fazer com autonomia.  
* Análise de dados: Sei fazer com ajuda.  

#### Soft Skills  

* Empatia - Para entender a necessidade do cliente e construir uma aplicação que possa ajudá-lo e sanar essa necessidade.  
* Trabalho em equipe - Fundamental para que o projeto chegue até o cliente dentro do prazo e funcionando.  
* Perseverança - Na época foi um projeto difícil de ser desenvolvido.  
* Gerenciamento de tempo - Do início ao fim do projeto, afinal, analisar dados e transformar em informação leva tempo que não pode ser desperdiçado.  
* Autodidatismo - Buscando conhecimento sobre o cadastro positivo para conseguir gerar os indicadores de negócios, além da praticidade com o envio de e-mail.

## Meus Principais Conhecimentos

Minhas tecnologias e frameworks com maior conhecimento são na área de desenvolvimento web, onde se destacam o Javascript, sendo toda a parte de backend aliado ao NodeJS com Express. Já na parte de banco de dados, a utilização do MySql e do PostgreSQL. Para o frontend, segue a utilização de frameworks Javascript, como ReactJS e VueJS. Também possuo conhecimento de scripts com Python.

## Contatos
* [GIT](https://github.com/Denis-Lima)
* [LinkedIn](https://www.linkedin.com/in/felelima/)
