# Servidor apache com SSL

Este projeto são apenas os arquivos mudados da instalação de um servidor Apache2 com SSL configurado, o restante dos arquivos continua o padrão da instalação. As chaves geradas sao diferentes em cada servidor e não se deve torna-las públicas. 

## Integrantes
Bruno Ferro,
Leonardo Tamanhão,
Mauro Toshiuki,
Yasmin Araujo,

## Objetivo

O objetivo deste projeto é tornar segura a troca de imagens entre servidor e cliente. Utiliza-se o SSL para garantir criptografia e confiabilidade do servidor.

## Visão Geral
O OpenSSL é um kit de ferramentas robusto, de nível comercial e com todos os recursos para os protocolos Transport Layer Security (TLS) e Secure Sockets Layer (SSL). É também uma biblioteca de criptografia de uso geral, usada em conjunto com o Apache que é um servidor web gratuito, compatível com o protocolo HTTP.

## Installation

```bash
apt-get install apache2 openssl
```

# Obfuscação 

Esta parte do projeto é a maneira de obfuscar código em python usando o pyarmor

## Instalação

```python
pip install pyarmor
```
## Obfuscando

Para obfuscar um arquivo em python basta usar o comando

```bash
pyarmor obfuscate arquivo.py
```
O arquivo obfuscado irá para pasta dist e para rodar o código basta usar 

```bash
python arquivo.py
```

Caso queira obfuscar todos os arquivos de uma pasta basta usar a flag --recursive em um script da pasta


```bash
pyarmor obfuscate --recursive arquivo.py
```

Para obfuscar apenas um arquivo de um pacote se usa a flag --exact

```bash
pyarmor obfuscate --exact arquivo.py
```
