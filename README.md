# estrutura-condicional

📝 Projeto: Estrutura Condicional 

Este projeto simples em Python demonstra o uso de listas, entrada de dados pelo usuário e estruturas condicionais (if/elif/else) para fornecer uma saudação personalizada se o nome digitado estiver presente em uma lista predefinida.

🚀 Começando

Pré-requisitos
Para executar este código, você só precisa ter o Python 3 instalado em sua máquina.

🎯 Funcionalidades

O script possui as seguintes funcionalidades principais:

Exibição da Lista: Mostra os nomes válidos disponíveis para o usuário.

Entrada de Dados: Solicita ao usuário que insira um nome.

Saudação Condicional:

Se o nome for "Ana", "Bruno", "Carlos", "Diana", ou "Eva", exibe uma saudação específica.

Se o nome não estiver na lista ou for digitado de forma diferente (ex: "ana" em vez de "Ana"), exibe uma mensagem de erro.

⚙️ Documentação do Algoritmo
A lógica do programa pode ser entendida e representada através das seguintes técnicas:

1. Pseudocódigo
   
O pseudocódigo é uma forma de representação de algoritmos que utiliza uma linguagem estruturada, mas informal, para descrever os passos de um programa.

ALGORITMO SaudarNome

VARIAVEL

  lista: VETOR DE STRING = ["Ana", "Bruno", "Carlos", "Diana", "Eva"]
  nome: STRING
  
INÍCIO

  // 1. Exibir a lista para o usuário
  
  ESCREVER lista
  
  // 2. Solicitar a entrada de um nome
  
  LER nome
  
  // 3. Estrutura de Decisão
  
  SE nome FOR IGUAL A "Ana" ENTÃO
  
    ESCREVER "Olá Ana!"
    
  SENÃO SE nome FOR IGUAL A "Bruno" ENTÃO
  
    ESCREVER "Oi Bruno!"
    
  SENÃO SE nome FOR IGUAL A "Carlos" ENTÃO
  
    ESCREVER "E aí Carlos!"
    
  SENÃO SE nome FOR IGUAL A "Diana" ENTÃO
  
    ESCREVER "Bom dia Diana!"
    
  SENÃO SE nome FOR IGUAL A "Eva" ENTÃO
  
    ESCREVER "Boa tarde Eva"
    
  SENÃO // O nome não está na lista ou foi digitado incorretamente
  
    ESCREVER "O nome informado não está na lista"
    
  FIM SE
  
FIM
  
