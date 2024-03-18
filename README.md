# Python-analise-de-dados
Python analise de dados

Se você não me conhece, me chamo Victor, estou aprendendo e desenvolvendo em diversas linguagens de programação.
Neste repositório, estarei colocando meus materiais de estudo e prática, como nos outros repositórios do meu GitHub.

Aqui está meu LinkedIn caso queira entrar em contato: https://www.linkedin.com/in/v-victor-mota/

Este README tem o intuito de colocar os princípios de Python, as partes mais avançadas ou de analise de dados, estarão presentes nos
seus respectivos códigos


1- SINTAXE BÁSICA

Textos devem ficar dentro de '' (aspas simples) ou "" (aspas duplas).
Para pular linha em um texto, utilizamos \n (contra-barra + n).
Para fazer comentários pertinentes dentro de um código, utilizamos # (hashtag).
Para escrever um texto já com as quebras de linhas e tamanhos corretos, utilizamos '''''' (3 (três) aspas simples).

Para fazermos nosso clássico "Olá Mundo!", podemos utilizar o seguinte comando:

    print("Olá Mundo!")


2- OPERADORES MATEMÁTICOS EM PYTHON

    Soma ---------------------------- + --------------------------- 2 + 2
    Subtração ----------------------- - --------------------------- 2 - 2
    Multiplicação ------------------- * --------------------------- 2 * 2
    Divisão ------------------------- / --------------------------- 2 / 2
    Exponenciação ------------------- ** -------------------------- 2 ** 2
    Resto da divisão ---------------- % --------------------------- 2 % 2
    Divisão de chão ----------------- // -------------------------- 2 // 2
    Priorização --------------------- () -------------------------- (2 + 2) * 2


3- VARIÁVEIS INICIAIS

    str ----------------------------- texto ----------------------- "dois"
    int ----------------------------- número inteiro -------------- 2
    float --------------------------- número quebrado ------------- 2.22
    bool ---------------------------- verdadeiro ou falso --------- True

4- TIPOS DE DADOS

    listas -------------------------- [] -------------------------- [2, 2]
    Tuplas -------------------------- () -------------------------- (2, 2)
    Dicionários --------------------- {} -------------------------- {
        "Index" : 2
    }

Listas podem armazenar valores de vários tipos na mesma instância.
Tuplas são imutáveis.


5- NOMEAÇÃO DE VARIÁVEIS

Para criar várias variáveis em uma única linha, podemos escrever seus nomes separados por uma vírgula, por exemplo:

    laranja, melao, limao = 1, 2, 3


Para atribuir o mesmo valor a várias variáveis em apenas uma linha, usamos:

    morango = uva = kiwi = 100


Para atribuir os valores de uma lista à variáveis, podemos usar:

    lista_carros = ['VW', 'Audi', 'Tesla']

    carro_01, carro_02, carro_03 = lista_carros


Para combinar variáveis dentro de outra, nós usamos o + (mais), caso você queira juntar uma string com um número inteiro, basta definir os dois valores como sendo strings, segue o exemplo:

Exemplo de duas strings:

    nome = "Zé"
    sobrenome = "Latinha"

    nome_completo = nome + sobrenome

Exemplo de uma string com um número inteiro:

    nome = "Zé"
    idade = 2

    id_usuario = str(nome + idade)


6- TIPOS DE INFORMAÇÕES

    data01 = str("2")
    data02 = int(2)
    data03 = float(2.22)
    data04 = complex(1j)
    data05 = list(['2', 'dois'])
    data06 = tuple(('2', 'dois'))
    data07 = range(2)
    data08 = dict(nome = 'Odenir', idade = 2)
    data09 = set(('A', 'B', 'C'))
    data10 = frozenset(('A', 'B', 'C'))
    data11 = bool(5)
    data12 = bytes(5)
    data13 = bytearray(5)
    data14 = memoryview(bytes(5))
    data15 = datetime.today().date()

Para descobrir o tipo de alguma informação, usamos:

    type(data01)

    Output:
    str


7- COMANDO ROUND

Quando trabalhamos com números flutuantes, podemos arredondar e/ou definir o número de casas decimais utilizando por exemplo:

    valor_exemplo = 12.8736498
    print(round(valor_exemplo, 2))
    print(round(valor_exemplo))

    Output:
    12.87
    13


8- COMANDO LEN

A função len() retorna a quantidade de elementos de qualquer lista em Python, por exemplo:




