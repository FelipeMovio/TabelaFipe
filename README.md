# 🚗 Tabela FIPE - Consulta de Veículos

Projeto desenvolvido em Java com consumo de API REST da Tabela FIPE, permitindo consultar marcas e modelos de veículos diretamente pelo terminal.

A aplicação consome dados da API pública da FIPE utilizando `HttpClient`, converte o JSON com `Jackson` e exibe as informações organizadas no console.

## 🔥 Funcionalidades

* Consulta de:

  * Carros
  * Motos
  * Caminhões
* Listagem de marcas disponíveis
* Busca de modelos por marca
* Ordenação dos resultados por código
* Consumo de API REST
* Conversão de JSON para objetos Java

## 🛠 Tecnologias Utilizadas

* Java 17+
* Spring Boot (estrutura do projeto)
* Jackson
* HTTP Client
* API FIPE

## 🌐 API utilizada

https://parallelum.com.br/fipe/api/v1/

## 📚 Conceitos aplicados

* Programação Orientada a Objetos (POO)
* Consumo de APIs REST
* Records no Java
* Generics
* Streams API
* Manipulação de JSON
* Interfaces
* Organização em camadas

## ▶ Como executar

1. Clone o repositório
2. Abra o projeto na IDE
3. Execute a classe principal
4. Escolha o tipo de veículo
5. Informe o código da marca desejada

## 📌 Exemplo de uso

```bash
*** OPÇÕES ***
Carro
Moto
Caminhão

Digite uma das opções para consulta:
carro

Informe o código da marca para consulta:
21
```

## 👨‍💻 Autor

Felipe Movio
