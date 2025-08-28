# 🚗 Estacionamento - Desafio de Projeto DIO

## 📖 Sobre o Projeto
Este projeto foi desenvolvido como parte da **Trilha .NET - Fundamentos** da [Digital Innovation One (DIO)](https://www.dio.me).  
O objetivo é criar um sistema simples de **gestão de estacionamento**, utilizando conceitos básicos da linguagem **C#** e da **Programação Orientada a Objetos (POO)**.

---

## 🎯 Funcionalidades Implementadas
A classe **Estacionamento** possui os seguintes atributos:
- **precoInicial**: valor cobrado ao estacionar um veículo.
- **precoPorHora**: valor cobrado por hora adicional.
- **veiculos**: lista de placas dos veículos cadastrados.

E os seguintes métodos:

- **AdicionarVeiculo()**
  - Solicita a placa do veículo e adiciona à lista de veículos estacionados.
  
- **RemoverVeiculo()**
  - Exibe os veículos cadastrados para o usuário.
  - Solicita a placa do veículo a ser removido.
  - Solicita a quantidade de horas que o veículo permaneceu.
  - Calcula o valor total:  
    ```
    valorTotal = precoInicial + (precoPorHora * horas)
    ```
  - Remove o veículo da lista e exibe o valor a ser pago.

- **ListarVeiculos()**
  - Lista todos os veículos estacionados no momento.
  - Caso não existam veículos, informa ao usuário que o estacionamento está vazio.

---

## 🛠️ Tecnologias Utilizadas
- **.NET 9 / C#**
- **Programação Orientada a Objetos (POO)**
- **Coleções (List<string>)**
- **Laços de repetição e condicionais**

---

## 📌 Exemplo de Uso
```text
Digite a opção desejada:
1 - Cadastrar veículo
2 - Remover veículo
3 - Listar veículos
4 - Encerrar

Digite a placa do veículo para estacionar:
ABC-1234

Os veículos estacionados são:
Nº 1 - ABC-1234

Digite a placa do veículo para remover:
ABC-1234
Digite a quantidade de horas que o veículo permaneceu estacionado:
3
O veículo ABC-1234 foi removido e o preço total foi de: R$ 28
