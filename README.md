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
    data08 = dict{nome = 'Odenir', idade = 2}
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

    lista = [1, 2, 3, 4, 5, 6, 7, 8, 9, 0]

    dicionario = {
        "Nome" : "Victor",
        "Idade" : 22
        }

    tupla = (1, 2, 3)

    string = "Olá Mundão!"

    len(Lista)
    len(dicionario)
    len(tupla)
    len(string)

    Output:
    10 #retornou a quantidade de elementos dentro da lista.
    2 #retornou a quantidade de index dentro do dicionário.
    3 #retornou a quantidade de elementos dentro da tupla.
    11 #retornou a quantidade de caracteres da string.


9- FATIAMENTO DE STRINGS

Strings são listas de bytes representando caracteres.
Podemos acessar suas posições usando [] (colchetes), por exemplo:

    string[posição inicial, posição final]

Para retornarmos um caractere específico de uma string, podemos usar o seguinte exemplo:

    minha_string = "Aprender Python é top!"

    print(minha_string[0])

    Output:
    'A'

Para retornarmos um caractere específico de uma string, porém, de trás pra frente, utilizamos números negativos, como por exemplo:

    minha_string = "Aprender Python é top!"

    print(minha_string[-1])

    Output:
    '!'

Para retornarmos uma cadeia de caracteres a partir de um index expecífico, utilizamos por exemplo:

    minha_string = "Aprender Python é top!"

    print(minha_string[5:])

    Output:
    'der Python é top!'

Com número negativo:

    minha_string = "Aprender Python é top!"

    print(minha_string[-5:])

    Output:
    ' top!'

Para retornarmos uma cadeia de caracteres no meio de uma string, utilizamos por exemplo:

    minha_string = "Aprender Python é top!"

    print(minha_string[2:20])

    Output:
    'render Python é to'


10- MANIPULAÇÃO DE STRINGS

    string = "Olá Mundo!"

    string.replace('Olá', 'Salve') #substitui o texto sugerido por um novo.
    string.startswith('Olá') #retorna verdadeiro caso a string comece com o/os caracteres sugeridos.
    string.endswith('Mundo!') #retorna verdadeiro caso a string termine com o/os caracteres sugeridos.
    string.count('o') #Conta quantos caracteres ou cadeia de caracteres sugeridos existem dentro da string.
    string.capitalize() #Deixa a string com o primeiro caractere maiúsculo.
    string.isdigit() #Retorna verdadeiro se a string possuir apenas números.
    string.isalnum() #Retorna verdadeiro se a string for alfanumérica | strings alfanuméricas podem possuir apenas letras e números.
    string.upper() #Retorna a string completamente em caixa alta.
    string.lower() #Retorna a string completamente em caixa baixa.
    string.find() #Retorna a posição em que o primeiro caractere da cadeia de caracteres sugeridos está.
    string.strip() #Remove os espaços no começo e no final da cadeia de caracteres.
    string.split() #Retorna a cadeia de caracteres em forma de lista, sendo sua divisão feita por espaços, você pode definir outro caractere como o responsável pela divisão.


11- COMANDO INPUT

Este comando permite que o usuário envie respostas ao prompt, que poderão ser manipuladas posteriormente.

    nome = input("Qual é o seu nome? ")
    idade = input("Qual a sua idade? ")


12- OPERADORES DE COMPARAÇÃO

São usados para comparar dois valores.

    == #Igual a
    != #Diferente de
    > #maior que
    < #menor que
    >= #maior ou igual a
    <= #menor ou igual que


13- OPERADORES LÓGICOS

    and
    or
    not







