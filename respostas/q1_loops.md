// Implementação em Java
int j = 20; 
int k = (j + 13) / 27;
int i = 0;


while (k <= 10) {
    k = k + 1;
    i = 3 * k - 1;
}

// Implementação em Python
j = 20
k = (j + 13) // 27
i = 0

while k <= 10:
    k += 1
    i = 3 * k - 1

// Implementação em Haskell
let j = 20
let k_inicial = (j + 13) `div` 27

let loop k i =
    if k > 10
    then (k, i)
    else let k_prox = k + 1
         in loop k_prox (3 * k_prox - 1)

let (k_final, i_final) = loop k_inicial 0

// Implementação em Swift
var j = 20
var k = (j + 13) / 27
var i = 0

while k <= 10 {
    k += 1
    i = 3 * k - 1
}


Discussão Técnica:

Qual foi mais fácil de escrever?
O Java foi o mais fácil pra mim porque já é a linguagem que eu uso no dia a dia. Como já estou acostumado com o jeito dele, nem precisei pensar muito, o código saiu direto e sem erro.

Qual ficou mais fácil de ler?
Java como é bem organizado e eu já tenho o olho treinado pra ele, consigo bater o olho e entender tudo o que está acontecendo na hora, sem precisar decifrar a sintaxe.

Qual a melhor combinação de ambas?
Para o meu caso, o Java é a melhor combinação. É o que eu tenho mais prática e o que eu leio mais rápido. O Python é legal por ser curto, mas o Java me passa mais segurança. Já o Haskell achei bem chatinho, porque ter que inventar uma função que chama ela mesma só pra fazer um loop simples dá um trabalho desnecessário.