# Visão Geral

## Pilha de Execução de um programa Java


Erros de programação são denominados bugs e o processo de encontrar e corrigir bugs é chamado de depuração ou debugging.

De forma geral, a depuração é uma tarefa difícil e trabalhosa, e a dificuldade varia de acordo com o ambiente de desenvolvimento, o que inclui a linguagem de programação e as ferramentas disponíveis, como depuradores.

Existem duas grandes categorias que englobam a natureza do erro:

Erros de Sintaxe:
- É um erro nas regras estabelecidas da linguagem:
Parênteses, chaves, colchetes que abrem mas não fecham.
Duas instruções sem um ponto-e-vírgula entre elas;
Uma palavra-chave sendo usada numa posição inesperada.

 
Erros de Semântica:
- É um erro na "lógica do código", em sua semântica, o código está sintaticamente correto, porém não faz o que se esperava dele.
Tentar dividir um número por uma String ou por zero.
Atribuir um valor incoerente a um tipo de dado.
Tentar fechar um arquivo que não foi aberto.

Depuração/Debugging
Linguagens de alto nível tornam a depuração mais fácil, pois fornecem mais ferramentas para identificar erros, como o tratamento de exceções.

Os depuradores funcionam assumindo o controle do tempo de execução de um programa e permitindo que você o observe e controle. Para fazer isso, ele mostra a pilha do programa e permite que você a atravesse em qualquer direção. Quando você está em um depurador, obtém uma imagem mais completa de um quadro de pilha do que quando olha os rastreamentos de pilha em uma mensagem de log.

Pilha de Execução de um Programa Java/Stack Trace
Pilha de Execução:
Toda invocação de método é empilhada em uma estrutura de dados que isola a área de memória de cada um. Quando um método termina (retorna), ele volta para o método que o invocou.
Stack Trace:
É a matriz onde encontramos a pilha de excecução da exceção. Em outras palavras, podemos dizer que o rastreamento da pilha busca (rastreio) para a próxima linha onde a exceção pode surgir.
🔗 Links Úteis
https://confluence.jetbrains.com/display/IntelliJIDEA/14.+Depurador
https://www.eclipse.org/community/eclipse_newsletter/2017/june/article1.php
🔎 Referências
https://www.hostgator.com.br/blog/debug-desenvolvimento-web/
https://www.alura.com.br/conteudo/java-excecoes
https://pt.wikipedia.org/wiki/Depura%C3%A7%C3%A3o
https://www.sentinelone.com/blog/java-stack-trace-understanding/
https://www.caelum.com.br/apostila-java-orientacao-objetos/excecoes-e-controle-de-erros#exercicio-para-comecar-com-os-conceitos
