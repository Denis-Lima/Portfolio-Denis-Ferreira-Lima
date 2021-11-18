# Sumário

* [Sobre o autor](#introdução)
* [Primeiro Semestre - Lumen](#em-2019-2)
* [Segundo Semestre - AlgoPositivo](#em-2020-1)
* [Terceiro Semestre - ShapeTP](#em-2020-2)
* [Quarto Semestre - Project Sisatas](#em-2021-1)
* [Quinto Semestre - Bureauto/Bureauto Mobile](#em-2021-2)
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

##

### Em 2020-2

### Parceiro Acadêmico

A [Visiona Tecnologia Espacial](https://www.visionaespacial.com.br/quem-somos) é a empresa brasileira integradora de sistemas espaciais. Resultante de uma iniciativa única do Governo brasileiro de estimular a criação de uma empresa integradora na indústria espacial, a Visiona é uma joint-venture entre a Telebras, empresa de economia mista do setor de telecomunicações, e a Embraer, empresa privada líder nos setores aeroespacial e de defesa.  

<p align="center">
	<img src="/img/3sem/post2shape.gif" alt="Prévia da solução Postgresql para Shapefile">
	<p align="center"><strong>Prévia da solução Postgresql para Shapefile</strong></p>
</p>
<hr/>
<p align="center">
	<img src="/img/3sem/shape2post.gif" alt="Prévia da solução Shapefile para Postgresql">
	<p align="center"><strong>Prévia da solução Shapefile para Postgresql</strong></p>
</p>

### Visão do Projeto

Buscando cortes de custos e soluções open source, a empresa propôs o desenvolvimento de uma aplicação web local "mini-ETL" (Extract, Transform, Load), que converta arquivos em formato Shapefile para uma tabela existente do banco de dados PostgreSQL/PostGIS e que faça também o caminho inverso, ou seja buscar no banco de dados e devolver ao usuário um arquivo Shapefile. O Shapefile é um formato de armazenamento de dados de vetor da Esri para armazenar a posição, forma e atributos de feições geográficas. Shapefiles espacial descrevem geometrias: pontos, linhas, e polígonos, e entre outras coisas, essas geometrias podem representar Poços, Rios, e Lagos por exemplo.  
Atualmente na empresa, é utilizado uma aplicação paga para tal operação, portanto a necessidade de reduzir custos com um "mini-ETL" open source, que seja pensado para as necessidades especificas desta empresa, como realizar operações no banco de dados com dados providos de um arquivo Shapefile, ou para fácil manuseio dos dados por meio da transformação do mesmo em Shapefile.

#### Link do Github
<a href="https://github.com/Denis-Lima/ShapeTP" target="_blank"><img src="https://pbs.twimg.com/profile_images/1414990564408262661/r6YemvF9_400x400.jpg" alt="Logo do Github" width="40" style="margin: 0px 15px 0px 0px;" /><span>&nbsp;&nbsp;&nbsp;</span><span>ShapeTP</span></a>

#### Tecnologias adotadas na solução

As tecnologias adotadas para a solução foram as seguintes:  
* <img src="https://s2.glbimg.com/5Iz4ZzSACXeBMQACRQmPliuTERw=/696x390/top/smart/s2.glbimg.com/vME2Bq4OSpm6f6IE16BhcVLR98U=/695x0/s.glbimg.com/po/tt2/f/original/2014/11/14/java-logo.jpg" alt="Logo do Java" width="200" /> [Java](https://www.java.com/pt-BR/), uma linguagem de programação orientada a objetos, poderosa e confiável, escolhida pela equipe para que o foco da solução seja na qualidade do resultado final, pela integração simples usando a extensão PostGIS provida pelo PostgreSQL.  

* <img src="https://repository-images.githubusercontent.com/184428875/67e25300-6c06-11e9-9570-44fa547e425a" alt="Logo do PostgreSQL e PostGIS" width="200" /> [PostgreSQL](https://www.postgresql.org/) um banco
de dados relacional open source poderoso, robusto e perfomático, super simples de utilizar e com muitas ferramentas e extensões poderosas. Aliado ao PostgreSQL, temos também a extensão [PostGIS](https://postgis.net/), utilizada para manipulação e armazenamento de dados geoespaciais.  
* 
<p align="left">
	<img src="https://image.flaticon.com/icons/png/512/29/29540.png" alt="Logo do JSP" width="200" height="150" />
<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRLyS4H0iLtlxoej41uIdXkQ6e563aIIxucFZQqpa5uumVUOOsp-bZexe7t_g0tMpD00gw&usqp=CAU" alt="Logo do JSP" width="300" height="150" />
 Java Server Pages, em conjunto com HTML5, CSS3 e JavaScript, para a construção da parte WEB da solução, visando a facilidade no manuseio da ferramenta ETL e disponibilidade para toda a equipe.   
</p>

<br/>
<p align="center">
	<img src="/img/3sem/Arquitetura de aplicação.png" alt="Arquitetura da aplicação">
	<p align="center"><strong>Arquitetura da aplicação</strong></p>
</p>

#### Contribuições pessoais

Para a construção do projeto, minha contribuição foi focada na construção da parte WEB do projeto, utilizando o JSP. Toda a construção do HTML da página, CSS e Javascript foram meu foco para ajudar a equipe a entregar com sucesso o projeto proposto.

#### Hard Skills

* Programação em Java: Sei fazer com ajuda.  
* Controle de versão com git e Github: Sei fazer com autonomia.  
* Criação de páginas WEB com JSP: Sei fazer com autonomia.  
* Utilizar tecnologias WEB (HTML, CSS e JavaScript): Sei fazer com autonomia.  
* Utilizar banco de dados PostgreSQL: Sei fazer com ajuda.  
* Utilizar extensão PostGIS: Sei fazer com ajuda.  
* Construção de mini-ETL: Sei fazer com ajuda.

#### Soft Skills  

* Empatia - Para entender a necessidade do cliente e construir uma aplicação que possa ajudá-lo a resolver o problema.  
* Trabalho em equipe - Para divisão de tarefas para realizar as entregas no prazo.  
* Gerenciamento de tempo - Do início ao fim do projeto, afinal, analisar dados e transformar em informação leva tempo que não pode ser desperdiçado.  
* Autodidatismo - Buscando conhecimento essa nova área de processamento de dados geoespaciais, além de conhecer a extensão PostGIS para a manipulação dos mesmos.  

##

### Em 2021-1

### Parceiro Acadêmico

A [IACIT](https://www.iacit.com.br/) é uma empresa brasileira, fundada em 1986, e com sede em São José dos Campos (SP), um importante polo da indústria aeroespacial do Brasil.
A empresa possui capacitação tecnológica para o desenvolvimento de produtos e sistemas aplicados ao Auxílio do Controle e do Tráfego Aéreo e Marítimo; Defesa e Segurança Pública; Fábrica de Software; Meteorologia; Pesquisa, Desenvolvimento e Inovação e Telemetria.
Certificada como Empresa Estratégica de Defesa (EED), a IACIT deposita seu conhecimento técnico e o desenvolvimento tecnológico em produtos e sistemas de alta tecnologia, no mais puro estado da arte.

<p align="center">
	<img src="/img/4sem/Aplicacao.gif" alt="Prévia da solução">
	<p align="center"><strong>Prévia da solução e funcionalidades</strong></p>
</p>

### Visão do Projeto

O tema do projeto era um CRUD Sistema Web com regra de negócio complexa em ambiente de produção (Deploy), e o desafio consiste em desenvolver um sistema de Gestão de Atas de Reunião visando as funcionalidades de cadastro,
controle de acesso, logs de execução, geração e monitoramento de ata de reunião e assinatura digital.
Adicionalmente, relatórios analíticos são pontos interessantes de agregação de valor ao projeto.  
Com isso foi desenvolvido o Sisatas, um sistema web para gerenciar suas atas de qualquer lugar com acesso a internet, visando a praticidade na hora da criação, adição de membros participantes da Ata, além de contar com funcionalidades como exportação em PDF ou Excel, criação de revisões e comentários, e envio por e-mail.

#### Link do Github
<a href="https://github.com/Denis-Lima/ProjectSisatas" target="_blank"><img src="https://pbs.twimg.com/profile_images/1414990564408262661/r6YemvF9_400x400.jpg" alt="Logo do Github" width="40" style="margin: 0px 15px 0px 0px;" /><span>&nbsp;&nbsp;&nbsp;</span><span>Project Sisatas</span></a>

#### Tecnologias adotadas na solução

As tecnologias adotadas para a solução foram as seguintes:  
* <img src="https://s2.glbimg.com/5Iz4ZzSACXeBMQACRQmPliuTERw=/696x390/top/smart/s2.glbimg.com/vME2Bq4OSpm6f6IE16BhcVLR98U=/695x0/s.glbimg.com/po/tt2/f/original/2014/11/14/java-logo.jpg" alt="Logo do Java" width="200" /> [Java](https://www.java.com/pt-BR/), uma linguagem de programação orientada a objetos, poderosa e confiável, escolhida pela equipe para que o foco da solução seja na qualidade do resultado final, além de usar todo o poder da orientação a objetos, para melhor definição das regras de negócio da aplicação.  

* <img src="https://spring.io/images/spring-logo-9146a4d3298760c2e7e49595184e1975.svg" alt="Logo do Java" width="200" /> [Spring](https://spring.io/) é um framework open source para a plataforma Java. Trata-se de um framework não intrusivo, baseado nos padrões de projeto inversão de controle e injeção de dependência. Faz com que a programação em Java seja mais rápida, fácil e segura, focando na regra de negócio da solução.  

* <img src="https://maven.apache.org/images/maven-logo-black-on-white.png" alt="Logo do Maven" width="200" /> [Maven](https://maven.apache.org/) uma ferramenta de gerenciamento e compreensão de projetos de software, para controle de dependências do projeto e fácil réplica do mesmo.  

* <img src="https://i1.wp.com/www.savepoint.blog.br/wp-content/uploads/2015/01/postgresql-logo.png?fit=610%2C280&ssl=1" alt="Logo do PostgreSQL e PostGIS" width="200" /> [PostgreSQL](https://www.postgresql.org/) um banco
de dados relacional open source poderoso, robusto e perfomático, super simples de utilizar e com muitas ferramentas e extensões poderosas.  

* <img src="https://res.cloudinary.com/practicaldev/image/fetch/s---bw3ly0q--/c_imagga_scale,f_auto,fl_progressive,h_420,q_auto,w_1000/https://dev-to-uploads.s3.amazonaws.com/i/iy5mgq1ptnakllmrk6hp.png" alt="Logo do ReactJS" width="300" height="150" /> Para o frontend, foram escolhido o [ReactJS](https://reactjs.org/), um framework para desenvolvimento de interfaces simples e interativas, baseadas em componentização, aliado com a biblioteca [MaterialUI](https://mui.com/pt/), que conta com diversos componentes estilizados pré-prontos, facilitando o desenvolvimento.  

<br/>
<p align="center">
	<img src="/img/4sem/contexto.png" alt="Diagrama de contexto">
	<p align="center"><strong>Diagrama de contexto</strong></p>
</p>
<p align="center">
	<img src="/img/4sem/implantacao.png" alt="Diagrama de implantação">
	<p align="center"><strong>Diagrama de contexto</strong></p>
</p>

#### Contribuições pessoais

Para a construção do projeto, minha contribuição foi focada na construção da parte da visão do cliente, utilizando o ReactJS e MaterialUI. Realizei a estruturação do projeto frontend, exportação de atas em PDF, assim como criação de algumas páginas, componentes personalizados, integração entre frontend e backend, salvamento de sessão. Já no lado do servidor, realizei pequenas contribuições na criação de algumas rotas, serviços de modelos.  

#### Hard Skills

* Programação em Java: Sei fazer com ajuda.  
* Utilização do Spring Boot: Sei fazer com ajuda.  
* Gerenciamento de dependências com Maven: Sei fazer com ajuda.  
* Controle de versão com git e Github: Sei fazer com autonomia.  
* Criação de páginas WEB com ReactJS: Sei fazer com autonomia.  
* Utilizar biblioteca MaterialUI: Sei fazer com autonomia.  
* Utilizar banco de dados PostgreSQL: Sei fazer com autonomia.  

#### Soft Skills  

* Empatia - Para entender a necessidade do cliente e construir uma aplicação que possa ajudá-lo a resolver o problema.  
* Trabalho em equipe - Para divisão de tarefas para realizar as entregas no prazo.  
* Gerenciamento de tempo - Do início ao fim do projeto, por conta do projeto ter uma regra de negócio bem complexa.  
* Autodidatismo - Buscando novos frameworks e bibliotecas, para melhor gestão do projeto e desenvolvimento simplificado do projeto.  
* Autocontrole e paciência - Por ser tratar de um projeto muito complexo em  regra de negócio, foi necessário ter um bom autocontrole e ser calmo para que a conclusão do mesmo pudesse ser feita da melhor forma possível.  

##

### Em 2021-2

### Parceiro Acadêmico

A [GSW](http://www.gsw.com.br/) é uma empresa especializada em desenvolvimento e implantação de soluções inteligentes em Tecnologia da Informação para gestão empresarial, gestão tributária, operações em comércio exterior e CRM.

Com 25 anos de experiência em projetos globais de TI e mais de 400 colaboradores espalhados por 6 unidades, a GSW oferece portfólio abrangente, construído através de sólidas alianças com empresas de soluções globais em TI, como Thomson Reuters, SAP, Microsoft, IBM, Oracle e Salesforce.

A GSW tem maturidade para atender praticamente todas as demandas de seus clientes, desde desenvolvimento de software, implantação de ERP e sistemas satélites, até alocação de profissionais técnicos e funcionais.

<p align="center">
	<img src="/img/previa.gif" alt="Prévia da solução web">
	<p align="center"><strong>Prévia da solução web</strong></p>
</p>
<p align="center">
	<img src="/img/previa-m.gif" alt="Prévia da solução mobile">
	<p align="center"><strong>Prévia da solução mobile</strong></p>
</p>

### Visão do Projeto

O tema do projeto desse segundo semestre de 2021 foi um sistema back e front com grandes volumes de dados, com front mobile. O desafio era criar um portal de vendas de veículos, no qual há métricas tanto para o administrador quanto para o anunciante, além de ter um chat em tempo real e a segurança dos dados na plataforma.

#### Link do Github
<a href="https://github.com/BureauTech/BureAuto" target="_blank"><img src="https://pbs.twimg.com/profile_images/1414990564408262661/r6YemvF9_400x400.jpg" alt="Logo do Github" width="40" style="margin: 0px 15px 0px 0px;" /><span>&nbsp;&nbsp;&nbsp;</span><span>Bureauto</span></a>
<a href="https://github.com/BureauTech/BureAutoMobile" target="_blank"><img src="https://pbs.twimg.com/profile_images/1414990564408262661/r6YemvF9_400x400.jpg" alt="Logo do Github" width="40" style="margin: 0px 15px 0px 0px;" /><span>&nbsp;&nbsp;&nbsp;</span><span>Bureauto Mobile</span></a>

#### Tecnologias adotadas na solução

As tecnologias adotadas para a solução foram as seguintes:  
* <img src="https://nodejs.org/static/images/logos/nodejs.png" alt="Logo do Java" width="200" /> [Node JS](https://nodejs.org/en/), uma ferramenta para execução de código Javascript fora do navegador, para construção do servidor da aplicação.  

* <img src="https://vuejs.org/images/logo.svg" alt="Logo do Java" width="200" height="100" /> [Vue JS](https://vuejs.org/) é um framework open source para o desenvolvimento de interfaces com foco no SPA (Single Page Application). Muito simples e intuitivo de se utilizar.  

* <img src="https://i1.wp.com/www.savepoint.blog.br/wp-content/uploads/2015/01/postgresql-logo.png?fit=610%2C280&ssl=1" alt="Logo do PostgreSQL e PostGIS" width="200" /> [PostgreSQL](https://www.postgresql.org/) um banco
de dados relacional open source poderoso, robusto e perfomático, super simples de utilizar e com muitas ferramentas e extensões poderosas.  

* <img src="https://cdn.vuetifyjs.com/docs/images/logos/vuetify-logo-light-text.svg" alt="Logo do ReactJS" width="200" height="150" /> Para o frontend, aliado ao Vue JS, foi escolhido a biblioteca [Vuetify](https://vuetifyjs.com/en/), que conta com diversos componentes estilizados e responsivos pré-prontos, facilitando o desenvolvimento.  

* <img src="https://d33wubrfki0l68.cloudfront.net/554c3b0e09cf167f0281fda839a5433f2040b349/ecfc9/img/header_logo.svg" alt="Logo do ReactJS" width="100" height="150" /> Para o mobile foi escolhido o framework [React Native](https://reactnative.dev/), que conta com código Javascript para desenvolvimento Nativo de apps mobile, que serve igualmente para Android e iOS.  

#### Contribuições pessoais

Para a construção do projeto, minha contribuição foi bem distribuida entre frontend web e backend. Realizei a estruturação do projeto web, construção de algumas páginas web, criação de alguns componentes, regra de acesso de rotas web, comunicação do chat com websocket (web e servidor), criação de alguns endpoints do servidor, auxiliar na modelagem do ORM, criação de serviço para compressão de imagem, criação de relatórios para anunciante e administrador.  

#### Hard Skills

* Programação em Node JS: Sei fazer com autonomia.  
* Programação web com Vue JS: Sei fazer com autonomia.  
* Programação mobile com React Native: Sei fazer com ajuda.  
* Desenvolvimento backend com ORM: Sei fazer com ajuda.  
* Envio de e-mails com Nodemailer: Sei fazer com autonomia.  
* Compressão de imagem com sharp: Sei fazer com autonomia.  
* Utilizar biblioteca Vuetify: Sei fazer com autonomia.  
* Utilizar banco de dados PostgreSQL: Sei fazer com autonomia.  
* Configuração e integração de websocket: Sei fazer com autonomia.  

#### Soft Skills  

* Empatia - Para entender a necessidade do cliente e construir uma aplicação que possa ajudá-lo a resolver o problema.  
* Trabalho em equipe - Para divisão de tarefas para realizar as entregas no prazo.  
* Gerenciamento de tempo - Do início ao fim do projeto, pois havia muita coisa para ser desenvolvida, além de ser um caminho obscuro o desenvolvimento mobile, já que a equipe nunca havia feito antes.  
* Autodidatismo - Buscando novos frameworks e bibliotecas, para melhor gestão do projeto e desenvolvimento simplificado do projeto.  
* Autocontrole e paciência - Por ser tratar de um projeto com complexidade média em  regra de negócio, mas com muitas partes a serem desenvolvidas foi necessário ter um bom autocontrole e ser calmo para que a conclusão do mesmo pudesse ser feita da melhor forma possível.  

## Meus Principais Conhecimentos

Minhas tecnologias e frameworks com maior conhecimento são na área de desenvolvimento web, onde se destacam o Javascript, sendo toda a parte de backend aliado ao NodeJS com Express. Já na parte de banco de dados, a utilização do MySql e do PostgreSQL. Para o frontend, segue a utilização de frameworks Javascript, como ReactJS e VueJS. Também possuo conhecimento de scripts com Python.

## Contatos
* [GIT](https://github.com/Denis-Lima)
* [LinkedIn](https://www.linkedin.com/in/felelima/)
