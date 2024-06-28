# DesafioControleFluxo
# Descrição
Este projeto foi desenvolvido para praticar o controle de fluxo em Java. Ele solicita dois parâmetros inteiros do usuário e imprime uma sequência de números com base na diferença entre os dois parâmetros. Se o primeiro parâmetro for maior que o segundo, uma exceção customizada (ParametrosInvalidosException) será lançada, informando ao usuário que o segundo parâmetro deve ser maior que o primeiro.

# Funcionalidades
Recebe dois números inteiros como entrada via terminal.
Imprime uma sequência de números a partir de 1 até a diferença entre os dois números fornecidos.
Lança uma exceção customizada (ParametrosInvalidosException) se o primeiro número for maior que o segundo, exibindo uma mensagem de erro.
Estrutura do Projeto
O projeto contém as seguintes classes:

Contador.java

Classe principal que executa a lógica do programa.
Lê os parâmetros do usuário.
Chama o método contar para realizar a contagem e impressão dos números.
Trata a exceção ParametrosInvalidosException quando o segundo parâmetro é menor que o primeiro.
ParametrosInvalidosException.java

Define uma exceção customizada que é lançada quando o primeiro parâmetro é maior que o segundo.
# Exemplo de Uso
Ao executar o programa, o usuário deverá fornecer dois números inteiros:

Copiar código
Digite o primeiro parâmetro
12
Digite o segundo parâmetro
30
A saída será:

python
Copiar código
Imprimindo o número 1
Imprimindo o número 2
...
Imprimindo o número 18
