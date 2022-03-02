# Testes de mutação com Stryker.NET

Um pouco sobre a biblioteca
----
Stryker.NET é uma biblioteca que oferece testes de mutação para .NET, ele permite que você teste seus testes inserindo bugs temporariamente, é importante lembrar que a biblioteca só pode ser usado para aplicações .net 5 e adiante

Sobre os testes
----
O testes de mutação ou testes mutantes são feitos para avaliarem a bateria de testes do seu código. O conceito é modificar uma parte do seu código, implementando bugs ou "mutantes" fazendo com que seus testes quebrem e encontrando possíveis falhas ou erros. Seus testes são executados para cada mutante. Se seus testes falharem, o mutante sobrevive. Se seus testes passarem, o mutante é morto. Quanto maior a porcentagem de mutantes mortos, mais eficazes serão seus testes.

Os mutantes tem alguns estados como:
* Morto: Quando pelo menos um teste falhou enquanto este mutante estava ativo, o mutante é morto
* Sobreviveu: Quando todos os testes passaram enquanto este mutante estava ativo, o mutante sobreviveu.
* Sem cobertura: O mutante não é coberto por um de seus testes e sobreviveu como resultado. 

Iniciando o projeto
----
Neste exemplo utilizaremos o xunity para nossos testes, você poderá estar utilizando este [Template](https://github.com/Eliandro-Freitas/Template_Testes_de_mutacao/tree/main) com as classes e os testes ja implementados para adiantar o processo ou clonando o projeto diretamente pelo link https://github.com/Eliandro-Freitas/Template_Testes_de_mutacao.git
