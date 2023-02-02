# Devellop Labs: Teste prático para Frontend Javascript Developer

Este é o teste usado por nós aqui da [Devellop Labs](http://www.devellop.com.br) para avaliar tecnicamente os candidatos a nossas vagas de Frontend. Se você estiver participando de um processo seletivo para nossa equipe, certamente em algum momento receberá este link, mas caso você tenha chego aqui "por acaso", sinta-se convidado a desenvolver nosso teste e enviar uma mensagem para nós no e-mail `rh@devellop.com.br`. 

## Instruções

Você deverá criar um `fork` deste projeto, e desenvolver em cima do seu fork. Use o *README* principal do seu repositório para nos contar como foi resolver seu teste, as decisões tomadas, como você organizou e separou seu código, e principalmente as instruções de como rodar seu projeto.

Nós não definimos um tempo limite para resolução deste teste, o que vale para nós e o resultado final e a evolução da criação do projeto até se atingir este resultado, mas acreditamos que este desafio pode ser resolvido em cerca de 10 horas de codificação.

## O desafio

O desafio é criar uma aplicação de previsão do tempo, consumindo a [API de consulta da previsão do tempo do OpenWeatherMap](https://openweathermap.org/forecast5). A API é free, mas é necessário se [registrar](https://openweathermap.org/appid) para criar uma chave para usar a API. Favor **não incluir a sua chave no repositório**, por motivos de segurança.


Deve ser possivel pesquisar a previsão do tempo para uma cidade pelo nome da cidade.
Devem ser exibidos os seguintes items na previsão:

* A previsão dos próximos 5 dias (utilizando a API de consulta da previsão)
* Temperatura mínima e máxima de cada dia
* Status da previsão (nublado, ensolarado, etc)
* Umidade (percentual)

O visual e as formas de interação com o webapp também serão utilizados como parte da avaliação.
O mapeamento dos códigos de status da previsão podem ser vistos [aqui](https://openweathermap.org/weather-conditions).

### Requisitos

* A interface deve ser responsiva (desktop e mobile)
* Utilizar algum framework SPA (Single Page Application) ( React, Vue, Angular )
* Você pode fazer sua própria UI ou utilizar LIBS tais como ( Blueprint UI, MUI, React Bootstrap )
* Componentização do código também é um diferencial
* Código com TEST (TDD)
* Subir a aplicação em alguma plataforma (Exemplo Heroku)
* Descrever no README como subir a aplicação

### Diferencial

* Adicionar validações
* Utilizar JavaScript es6+
* Utilizar ES LINT
* Criar um pequeno CI/CD para o TDD e Linter

### Plus
* Salvar cidades favoritas (em memória, não é necessário ser permanente)
* Exibir as informações de tempo atuais utilizando a [API específica](https://openweathermap.org/current)
