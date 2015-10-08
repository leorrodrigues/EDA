Trabalho de Estrutura de Dados sobre a implementação de um sistema que realiza a leitura de um arquivo TXT, realizando a separacao de cada palavra e organizando um Arvore Binaria de Busca. 
Esta arvore conta em cada no, com uma lista que é utilizada para guardar a posição da linha e coluna em que esta palavra foi encontrada no arquivo TXT fornecido.
----------------------------------------------------------------------
No menu do comprama são encontradas as opções:

1- Realizar a busca de uma palavra, nesta opção é realizada a busca da ocorrencia da palavra no arquivo TXT, caso seja encontrado alguma ocorrência, a opção retorna uma mensagem descrevendo todas as ocorrencias da palavra pedida (mostrando sua linha e coluna).

2- Exibir a árvore, nesta opção é exibido todos os nós da árvore, em seguencia "em ordem", vale lembrar que não será mostrado nos nós as palavras lidas no texto, porém seus valores inteiros desenvolvidos atrvés de uma formula implementada no sistema. 
	Sendo esta formula o somatório do produtório do valor ASCII de cada letra pela sua posição na palavra. Exemplo: Ola téra o valor em seu nó de: 586.

3- Realiza a exclusão de uma ocorrência de determinada palavra da árvore, sendo primeiramente excluida da lista a sua ocorrência, quando a exclusão acarretar em uma lista vazia, a lista é desfeita e seu respectivo nó é retirado da árvore.

4- O arquivo é salvo com as edições feitas, o arquivo Original é salvo com a extensão OLD no final de seu nome e o arquivo editado apresenta o nome do arquivo original. Ex: Arquivo.txt(Arquivo Original) -> Salvar -> Arquivo.txt(Arquivo Editado) e ArquivoOLD.txt(Arquivo Original).

0- Para sair do programa.
----------------------------------------------------------------------

As bibliotecas utilizadas foram:
Padrões da linguagem C: <stdlib.h> <stdio.h>;
Bibliotecas desenvolvidas para realizar a utilização da árvore: "ABB.h" "ABB_priv.h" "cliente.h";
Bibliotecas desenvolvidas para realizar a utilização da lista:
"cliente.h" "LDDE.h" "LDDE_priv.h"

Foram desenvolvidos também dois arquivos .c para auxiliar na organização do código e facilitar a utilização das chamadas das bibliotecas acima citadas, sendo estas:
"ABB.c" "ABB_priv.c" "LDDE.c".

O arquivo principal do sistema é o Main.c, neste arquivo consta os codigos para chamar as funções e demais arquivos que constam no projeto do sistema.
----------------------------------------------------------------------

Para executar o sistema, é necessário possuir o programa CodeBlocks intalado em seu computador, disponível em: http://www.codeblocks.org/downloads 
Após instalar o CodeBlocks em seu computador, basta abrir o projeto TrabalhoFinalEDA.cbp em seu Code Blocks e clicar no botão Build and Run.

----------------------------------------------------------------------
Desenvolvido por:
Leonardo Rosa Rodrigues;
Rafael Rizzatti.