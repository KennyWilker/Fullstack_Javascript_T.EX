# Fullstack_Javascript_T.EX
## Diretório destinado a resolução dos desafios propostos em aula.
- Consegui completar todo o desafio na reta final.
- 
    Desafio de lógica
    #Fase 1
    - [x]crie um array dinâmico com três posições
    - [x]crie uma iteração que retorne números aleatórios entre 1 e 3
    - [x]a cada retorno, altere o valor do array respectivamente

    #Fase 2
    - [x]utilize as linhas codificadas e insira uma função
    - [x]crie uma verificação que identifica se os números do array são iguais
    - [x]se sim: escreva 'Porta aberta'
    - [x]se não: escreva 'Tente de novo!'

    #Fase 3
    - [x]crie uma variável de controle para acumular a quantidade de vezes que os números se repetem
    - [x]crie uma variável que armazene o valor do útimo sorteio
    - [x]compare o valor do último sorteio com o valor do sorteio atual
    --[x]Se os valores forem iguais: escreva 'Porta (x)' : aberta
    --[x]Se os valores forem diferentes: escreva 'Tente de novo' (Com a execução do resultado ser de números iguais)
    
    As portas serão abertas quando:
        - os números do array forem iguais 
        - a sequência de números do array for igual a sequência de números do útimo sorteio

    [1,2,3] 1° //ant - porta fechada
    [3,2,2] 2° // sorteio = porta fechada
    [3,2,2] 3° //porta1 aberta - variavelControle++
    [2,2,2] 4° //porta2 aberta - variavelControle++
    [1,2,3] 5° //porta fechada
    [3,2,1] 6° //porta fechada
    [3,3,3] 7° //porta3 aberta - variavelControle++
    
    Fim do jogo acontece quando a terceira porta for aberta.
