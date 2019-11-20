# Servidor apache com SSL

Este projeto são os arquivos mudados da instalação de um servidor Apache2 com SSL configurado. As chaves geradas sao diferentes em cada 
servidor e não se deve torna-las públicas. 

## Visão Geral
O OpenSSL é um kit de ferramentas robusto, de nível comercial e com todos os recursos para os protocolos Transport Layer Security (TLS) e Secure Sockets Layer (SSL). É também uma biblioteca de criptografia de uso geral, usada em conjunto com o Apache que é um servidor web gratuito, compatível com o protocolo HTTP.

## Objetivo

O objetivo deste projeto é tornar segura a troca de imagens entre servidor e cliente. Utiliza-se o SSL para garantir criptografia e confiabilidade do servidor.


## Installation

```bash
apt-get install apache2 openssl
```
