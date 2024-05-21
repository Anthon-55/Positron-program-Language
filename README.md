# POSITRON PROGRAM LANGUAGE
![Positron](https://redis.io/wp-content/uploads/2020/06/blog-async-scaled.jpeg)

Link da documentação: https://ton-jose.gitbook.io/positron-program-language/

Positron é uma linguagem de programação simples e flexível criada em Python. Ela foi projetada para ser fácil de aprender e usar, 
enquanto ainda oferece recursos poderosos o suficiente para aplicações do mundo real.

## Características
Sintaxe limpa e fácil de entender.
Suporte para operações matemáticas básicas e avançadas.
Manipulação eficiente de strings e arrays.
Funcionalidades de entrada e saída para interação com o usuário e o sistema de arquivos.
Capacidade de criar e importar bibliotecas personalizadas.
Linguagem em portugues
Para começar a usar MyLang, você só precisa clonar este repositório:

bash
Copiar código
git clone https://github.com/Anthon-55/Positron-program-Language.git

## Como Usar
Escreva seu código Positron em um arquivo com extensão .pos.
Execute o interpretador positron com o arquivo como argumento:

positron seu_programa.pos
Exemplo
Aqui está um exemplo simples de código Positron que calcula o fatorial de um número:

n = 5;
resultado = 1;
i = 0;

loop i em [1, 2, 3, 4, 5] {
    resultado = resultado * i;
}

saida("Fatorial de ", n, " é: ", resultado);


saida("O fatorial de 5 é: ", fatorial(5));

## EXEMPLOS DE CODIGO POSITRON
### Sequencia de Fibbonaci
a = 0;
b = 1;

loop i em [0, 1, 2, 3, 4, 5, 6, 7, 8, 9] {
    saida(a);
    c = a + b;
    a = b;
    b = c;
}



### RECOLHA DE DADOS PESSOAIS
#Recolher dados pessoais
saida("Digite seu Nome ");
recebe(nome);

saida("Digite seu EMail ");
recebe(email);

saida("Digite sua Idade ");
recebe(idade);

saida("seu Nome: ", nome);
saida("seu email: ", email);
saida("sua idade: ", idade, " Anos de idade");

se idade > 18 {
    saida("Voce é um Adulto, Ja pode conduzir");
}senao{
    saida("Voce não possui idade suficiente");
}

### PAR OU IMPAR
#Verificar se numero é Impar ou Par

recebe(valor);
divisivel = valor modulo 2;
se divisivel == 0{
    saida("O Numero é Par");
}senao{
    saida("O numero é impar");
}







