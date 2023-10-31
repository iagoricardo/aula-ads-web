# AULA ADS- 02 - CÓDIGO PARA GEOLOCALIZAÇÃO DO USUÁRIO
Código de web para rastrear a geolocalização dos usuários

Aula de Geolocalização
Objetivo
Nesta aula, você vai aprender como usar uma API de geolocalização para obter a posição atual do seu dispositivo e mostrar no mapa. Você também vai aprender como manipular dados geográficos e criar aplicações interativas com mapas.

Linguagem de Programação
Vamos usar a linguagem Python para desenvolver nossa aplicação. Python é uma linguagem simples, versátil e poderosa, que permite criar programas para diversas finalidades. Para usar a API de geolocalização, vamos precisar instalar uma biblioteca chamada geopy, que facilita o acesso a vários serviços de geocodificação e geolocalização.
Conceitos Básicos
Geolocalização é o processo de determinar a posição geográfica de um objeto ou pessoa. A posição geográfica é representada por um par de coordenadas: latitude e longitude. Latitude é a distância angular entre um ponto e o equador, variando de -90° (polo sul) a +90° (polo norte). Longitude é a distância angular entre um ponto e o meridiano de Greenwich, variando de -180° (oeste) a +180° (leste).

Para mostrar a posição no mapa, precisamos usar um sistema de referência que define como as coordenadas são projetadas em uma superfície plana. Existem vários sistemas de referência, mas um dos mais usados é o WGS 84 (World Geodetic System 1984), que é baseado em um modelo elipsoidal da Terra.

Para acessar os dados de geolocalização, precisamos usar uma API (Application Programming Interface), que é uma interface que permite a comunicação entre diferentes programas ou serviços. Uma API define um conjunto de regras e formatos para trocar informações. Existem várias APIs de geolocalização disponíveis na internet, mas vamos usar uma chamada Nominatim, que é um serviço gratuito de geocodificação e reversa oferecido pelo projeto OpenStreetMap
