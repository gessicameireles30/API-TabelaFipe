# 🚗 API Tabela FIPE - Consumo da API Pública em Java

Este projeto é uma aplicação **Java** que realiza o consumo da **API pública da Tabela FIPE**, permitindo ao usuário consultar informações atualizadas de **carros, motos e caminhões**.

## 📌 Objetivo

Este projeto tem como objetivo demonstrar na prática como consumir APIs REST em Java utilizando recursos como:

- HTTP Client do Java 11+
- Manipulação de JSON com Gson
- Boas práticas de organização de código com **modelos**, **serviços** e **aplicação principal**

## 🧰 Tecnologias Utilizadas

- **Java 17**
- **Gson** para desserialização de JSON
- **API FIPE Pública** - [https://parallelum.com.br/fipe/api/v1/](https://parallelum.com.br/fipe/api/v1/)
- **HTTP Client (java.net.http.HttpClient)**

  ## 💻 Como Executar

1. Clone o repositório:

git clone https://github.com/seu-usuario/seu-repositorio.git

Abra o projeto em sua IDE preferida (IntelliJ IDEA, Eclipse, VSCode).

Certifique-se que você tem o Java 17 instalado.


Instale a dependência do Gson no seu projeto. Exemplo para Maven:

<dependency>
    <groupId>com.google.code.gson</groupId>
    <artifactId>gson</artifactId>
    <version>2.10.1</version>
</dependency>

  ## 🎮 Funcionalidades da Aplicação
✅ Escolha de categoria: Carro, Moto ou Caminhão

✅ Listagem das marcas disponíveis via API FIPE

✅ Busca filtrada por modelos usando parte do nome

✅ Exibição de valores médios para anos de fabricação disponíveis

✅ Exemplo de uso de Streams, Comparator, Listas e boas práticas no Java

## 📝 Exemplo de fluxo da aplicação:


*** OPÇÕES ***

Carro

Moto

Caminhão

Digite uma das opções para consulta:

O usuário escolhe a categoria, o sistema lista as marcas;

Após selecionar a marca, lista os modelos;

Permite buscar por nome de modelo e consultar preços médios por ano.

🔗 Link da API Pública
A API utilizada é disponibilizada gratuitamente pelo projeto Parallelum:
https://parallelum.com.br/fipe/api/v1/


👩‍💻 Autor
Desenvolvido por Géssica Meireles 🚀
