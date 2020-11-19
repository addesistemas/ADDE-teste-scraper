![logo header](logo_ADDE_header.png)

# Sobre a ADDE

Geramos valor ao negócio​ do nosso cliente através da criação de softwares.

Contamos com um time ​polivalente​ capaz de resolver os problemas do cliente de forma clara​ e organizada ​através do desenvolvimento de software.

Somos uma empresa jovem, funcionamos em ritmo de startup.

Ajudamos o cliente em todas as fases, desde a idealização​ do projeto até a entrega ​em produção.

# Sobre o desafio

Criar um sistema que mostre o clima atual e a previsão do tempo a partir do input de uma cidade e/ou localização do usuário.

## Requisitos

### Backend

* Criar um sistema que se comunique com uma api externa para pegar os dados de clima filtrado por cidade/região.
* Persistir o dados recuperados da API para ser utilizados como cache com tempo limite de 15 minutos.
* Tecnologia: Python 3 ([FastApi](https://fastapi.tiangolo.com/), [Flask](https://flask.palletsprojects.com/en/1.1.x/))

### Frontend

* Exibir os dados recuperados a partir do input do usuário. Por padrão, a previsão do tempo deve vir com a localização do usuário.
* Tecnologia: [Angular](https://angular.io/) (7/8/9/10)

* Após consultar o clima, mostrar
  * Temperatura atual.
  * Cidade.
  * Clima (chovendo, nublado, ensolarado, etc).
  * Indicativo visual para mostrar o status do clima.

### Prazo

O prazo máximo para a entrega do teste será de **5 dias corridos** após o envio destas instruções.

## Forma de Entrega

Faça um repositório em alguma plataforma de controle de versionamento ([github](https://github.com), [gitlab](https://about.gitlab.com/), [bitbucket](https://bitbucket.org/), etc) contendo o projeto e nos mande o link, notificando que a solução está entregue.

## Pontos extras que podem fazer a diferença

* Site responsivo.
* Testes unitários e integrados.
* Clean Code.
* Previsão do tempo para X dias.

## FAQ

>Posso utilizar bibliotecas externas?

Sim.

> Por que um Backend para consultar uma API externa?

Na prática não é muito utilizado, a não ser que precise ter um filtro personalizado (paginação, controle de acesso específico, etc) que a API não forneça. De um modo geral, é mais interessante pois te dá mais controle, mas o intúito na verdade é saber se você é capaz de lidar com microserviços de forma objetiva.

> E se o prazo estourar?

 Entregue o que você fez até aquele momento. Iremos analisar o seu trabalho.

> Que tipo de feedback terei?

 Se você tiver chance de seguir para uma segunda fase, entraremos em contato e te enviaremos um convite para um bate papo remoto. Caso você não seja aprovado nessa fase, te daremos o feedback por e-mail.

> Caso eu tiver alguma dúvida, poderei entrar em contato dentro deo prazo estipulado?

 Sim, se você tiver qualquer dúvida, sinta-se a vontade para entrar em contato conosco através do e-mail tecnologia@addesistemas.com.br

## Dicas

### Exemplos de APIs que podem ser utilizadas

* [Weatherbit](https://www.weatherbit.io/)
* [OpenWeatherMap](https://rapidapi.com/community/api/open-weather-map)
            [(exemplo de retorno)](http://api.openweathermap.org/data/2.5/weather?q=São%20paulo,br&lang=pt_br&units=metric&appid=aaa1129fc07f4aacb6763552a1f84c0b)

***
![logo footer](logo_ADDE_490x90.png)
