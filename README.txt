Trabalho de Estrutura de Dados sobre a implementa��o de um sistema que realiza a leitura de um arquivo TXT, realizando a separacao de cada palavra e organizando um Arvore Binaria de Busca. 
Esta arvore conta em cada no, com uma lista que � utilizada para guardar a posi��o da linha e coluna em que esta palavra foi encontrada no arquivo TXT fornecido.
----------------------------------------------------------------------
No menu do comprama s�o encontradas as op��es:

1- Realizar a busca de uma palavra, nesta op��o � realizada a busca da ocorrencia da palavra no arquivo TXT, caso seja encontrado alguma ocorr�ncia, a op��o retorna uma mensagem descrevendo todas as ocorrencias da palavra pedida (mostrando sua linha e coluna).

2- Exibir a �rvore, nesta op��o � exibido todos os n�s da �rvore, em seguencia "em ordem", vale lembrar que n�o ser� mostrado nos n�s as palavras lidas no texto, por�m seus valores inteiros desenvolvidos atrv�s de uma formula implementada no sistema. 
	Sendo esta formula o somat�rio do produt�rio do valor ASCII de cada letra pela sua posi��o na palavra. Exemplo: Ola t�ra o valor em seu n� de: 586.

3- Realiza a exclus�o de uma ocorr�ncia de determinada palavra da �rvore, sendo primeiramente excluida da lista a sua ocorr�ncia, quando a exclus�o acarretar em uma lista vazia, a lista � desfeita e seu respectivo n� � retirado da �rvore.

4- O arquivo � salvo com as edi��es feitas, o arquivo Original � salvo com a extens�o OLD no final de seu nome e o arquivo editado apresenta o nome do arquivo original. Ex: Arquivo.txt(Arquivo Original) -> Salvar -> Arquivo.txt(Arquivo Editado) e ArquivoOLD.txt(Arquivo Original).

0- Para sair do programa.
----------------------------------------------------------------------

As bibliotecas utilizadas foram:
Padr�es da linguagem C: <stdlib.h> <stdio.h>;
Bibliotecas desenvolvidas para realizar a utiliza��o da �rvore: "ABB.h" "ABB_priv.h" "cliente.h";
Bibliotecas desenvolvidas para realizar a utiliza��o da lista:
"cliente.h" "LDDE.h" "LDDE_priv.h"

Foram desenvolvidos tamb�m dois arquivos .c para auxiliar na organiza��o do c�digo e facilitar a utiliza��o das chamadas das bibliotecas acima citadas, sendo estas:
"ABB.c" "ABB_priv.c" "LDDE.c".

O arquivo principal do sistema � o Main.c, neste arquivo consta os codigos para chamar as fun��es e demais arquivos que constam no projeto do sistema.
----------------------------------------------------------------------

Para executar o sistema, � necess�rio possuir o programa CodeBlocks intalado em seu computador, dispon�vel em: http://www.codeblocks.org/downloads 
Ap�s instalar o CodeBlocks em seu computador, basta abrir o projeto TrabalhoFinalEDA.cbp em seu Code Blocks e clicar no bot�o Build and Run.

----------------------------------------------------------------------
Desenvolvido por:
Leonardo Rosa Rodrigues;
Rafael Rizzatti.