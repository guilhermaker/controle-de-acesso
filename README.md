# Controle de Acesso

**Toda documentação do projeto encontra-se em fase de desenvolvimento!**

![img](https://raw.githubusercontent.com/douglaszuqueto/controle-de-acesso/master/.github/images/print-dashboard.png)

## Índice

- [Introdução](#introdução)
- [Objetivo](#objetivo)
- [Materiais](#materiais)
- [Tecnologias](#tecnologias)
- [Organização](#organização)
- [Fluxo](#fluxo)
- [Rodando o projeto](#rodando-o-projeto)
- [Resultados](#resultados)
- [Referências](#referências)


## Introdução

Depois de completar quase 1 ano que lancei o primeiro 'projeto' de envolvendo controle de acesso, eis que foi desenvolvido uma versão mais completa.

Para quem ainda não conhece, o projeto [Controle de acesso utilizando NodeMCU, RFID, MQTT e Banco de Dados MySQL](https://github.com/douglaszuqueto/esp8266-rfid-banco-de-dados) foi desenvolvido em Julho de 2017, onde tinha como objetivo desenvolver um projeto simples e direto ao ponto para sanar muitas dúvidas que membros da comunidade tinham, principalmente no que tange integração, arquitetura e comunicação com banco de dados. Portanto, para quem ainda não viu, eu recomendo dar uma olhada no projeto antigo para já ter um embasamento do que se trata - [link](https://github.com/douglaszuqueto/esp8266-rfid-banco-de-dados).

Como o objetivo era desenvolver um projeto mais completo, e como também, eu sempre estou em busca de testar e validar novas tecnologias, neste projeto não foi diferente - Utilizei **Go(golang)** como linguagem de programação para o *Back-end* e **VueJS** como biblioteca para construção do *Front-end*. No embarcado fiquei com as mesmas tecnologias pois é a que mais domino no momento.

## Objetivo

Desenvolver tal projeto que seja de fácil implementação - tanto no que tange **Embarcado** como também **Arquitetura** e **Software** e também oferecer uma boa experiência através de networking e troca de ideias - sendo os 2 últimos itens mencionados, os fatores que mais levo em consideração no desenvolvimento de algum projeto :)

## Materiais

Abaixo segue uma seção resumida dos materiais principais que foram utilizadas no decorrer do desenvolvimento do projeto.

* Embarcado
    * NodeMCU
    * Rfid Mfrc522 Mifare
* Servidor
    * Raspberry Pi 3
    * Raspberry Pi Zero W
    * Servidor em Nuvem

**Observação:** No que tange servidor, apenas um item citado acima basta! Detalharei com mais calma em outro tópico.

## Tecnologias

* Firmware
    * [PubSubClient](https://github.com/knolleary/pubsubclient)
    * [MFRC522](https://github.com/miguelbalboa/rfid/)
* Back-end - Go
    * [pq - A pure Go postgres driver for Go's database/sql package](https://github.com/lib/pq)
    * [gorilla/handlers](https://github.com/gorilla/handlers)
    * [gorilla/mux](https://github.com/gorilla/mux)
    * [Eclipse Paho MQTT Go client](https://github.com/eclipse/paho.mqtt.golang)
    * [jwt-go](https://github.com/dgrijalva/jwt-go)
    * [statik](https://github.com/rakyll/statik)
* Front-end - VueJS
    * [VueJS](https://github.com/vuejs/vue)
    * [Vue Router](https://github.com/vuejs/vue-router)
    * [Bootstrap 4](https://github.com/twbs/bootstrap)
    * [Axios](https://github.com/axios/axios)
    * [MQTT.js](https://github.com/mqttjs/MQTT.js)
    * [Font-Awesome](https://github.com/FortAwesome/Font-Awesome)
    * [Sweet Alert 2](https://github.com/sweetalert2/sweetalert2)

## Organização

## Fluxo

## Rodando o projeto

## Resultados

## Referências

- [Controle de acesso utilizando NodeMCU, RFID, MQTT e Banco de Dados MySQL](https://github.com/douglaszuqueto/esp8266-rfid-banco-de-dados)

# Gostou do projeto?

Se você curtiu o projeto e quer trocar uma ideia, foi criado um grupo no **Telegram** para debate! - [clique aqui para participar](https://t.me/joinchat/BPOe2hAc3mNcw_y7f0qipg).