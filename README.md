# Portfolio-Denis-Ferreira-Lima

## Projeto 1: 2019-2
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

### Link do git
#### [Projeto Lumen](https://github.com/Denis-Lima/Lumen)

### Tecnologias adotadas na solução

As tecnologias adotadas para a solução foram as seguintes:  
* <img src="https://appinventor.mit.edu/images/logo.png" alt="Logo do MIT AppInventor" width="200" /> [MIT App Inventor](https://appinventor.mit.edu/), uma ferramenta desenvolvida pela Google e atualmente mantida pelo MIT, para confecção do aplicativo, que possui uma interface amigável para pessoas com pouco conhecimento de programação. O App Inventor é uma ferramenta para construção de aplicativos por meio de blocos de programação, tanto na parte lógica quanto na parte visual.  
<br/>
* <img src="https://www.gstatic.com/devrel-devsite/prod/v509a5f4800978e3ce5a1a5f2c1483bd166c25f20fdb759fe97f6131b7e9f1f00/firebase/images/lockup.png" alt="Logo do Firebase" width="200" /> [Firebase Realtime Database](https://firebase.google.com/products/realtime-database?gclsrc=aw.ds&gclid=CjwKCAjw7fuJBhBdEiwA2lLMYcBC2UdWCsUTEdepZcIPR9r3gmOKo94uHC1fBV31fnwWsBQa1INL4xoCJ9UQAvD_BwE), um banco de dados NoSQL hospedado na nuvem, utilizado para armazenar as avaliações dos usuários (1 à 5 estrelas), via Wi-Fi.  
<br/>
* <img src="https://cdn.arduino.cc/header-footer/prod/assets/headerLogo-arduino.svg" alt="Logo do Arduino" width="200" /> [Arduino IDE](https://www.arduino.cc/en/software), para a criação da lógica que acompanha o hardware.  
<br/>
* <img src="https://cdn.shopify.com/s/files/1/0438/4735/2471/products/A000066_03.front_763x573.jpg?v=1629815860" alt="Imagem do Arduino Uno Rev3" width="200" /> [Arduino Uno Rev3](https://store.arduino.cc/products/arduino-uno-rev3/), que é uma placa com um microcontrolador, que ficará responsável pelo controle das peças físicas (LED's e cooler), acompanhado do script criado junto da Arduino IDE.  
* <img src="https://s3-sa-east-1.amazonaws.com/multilogica-files/Modulo_Bluetooth_HC-05_M.jpg" alt="Imagem do módulo Bluetooth" width="200" /> Módulo Bluetooth HC05, para integração entre o equipamento físico (hardware) e o aplicativo. Ideal para comunicação sem fio simples e de média distância. Além de um sensor de umidade e temperatura DHT11 para automação do cooler, resistores e jumpers para conexão eletrônica entre os componentes, LED RGB e um cooler.  
<br/>
* <img src="https://www.alura.com.br/artigos/assets/formacao-linguagem-c-plus-plus/img-01.png" alt="Logo do C++" width="200" /> Linguagem de programação C++, utilizada para criar a lógica do código fonte que acompanha o Arduino.  
<br/>
<figure>
	<img src="/img/Arquitetura.jpeg" alt="Arquitetura da aplicação">
	<figcaption>Arquitetura da aplicação</figcaption>
</figure>

### Contribuições pessoais

Para a construção do projeto, deixei minhas contribuições tanto no software quanto no hardware.  
Foi pensado nessa comunicação Bluetooth, o uso de envio de dados simples, como uma string "B", para informar que a cor azul (Blue) foi acionada (ligada ou desligada), uma string "R" para o vermelho (Red) e assim por diante.  
Realizei a integração do aplicativo com o hardware, para criar uma comunicação entre os mesmos via Bluetooth, utilizando os recursos de Bluetooth que o próprio App Inventor oferece, e os recursos de Bluetooth que o Arduino oferece.  
Também contribui com a montagem física do projeto, onde realizei o processo de montagem do LED na placa do Arduino e no módulo Bluetooth, utilizando corretamente os devidos resistores.

### Aprendizados Efetivos HS

Integração de módulo Bluetooth com software: Sei fazer com ajuda.  
Programação em microinformática: Sei fazer com ajuda.  
Construção de aplicativo usando App Inventor: Sei fazer com autonomia.  
Contrução de circuitos com arduino: Sei fazer com ajuda.
Controle de versão com Git e Github: Sei fazer com ajuda.
