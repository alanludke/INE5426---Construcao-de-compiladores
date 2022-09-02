# Construção de compiladores

## Conteúdo Programático

    - A estrutura de um compilador [1 hora-aula]
    - Linguagens de programação [1 horas-aula]
        - Características principais
    - Especificação e projeto de uma linguagem [6 horas-aula]
    - Análise léxica [2 horas-aula]
    - Construção de um analisador léxico [8 horas-aula]
    - Análise sintática e correção de erros [6 horas-aula]
    - Construção de um analisador sintático [12 horas-aula]
    - Análise semântica [6 horas-aula]
    - Implementação da análise semântica [12 horas-aula]
    - Geração de código intermediário e otimização [6 horas-aula]
    - Implementação do gerador de código [12 horas-aula]

## Primeira aula

O compilado tem como input um código fonte, output um código alvo ou talvez uma mensagem de erro.

A construção consiste em duas fases:

1. Fase de análise
    - Análise linear (análise léxica)

        O código fonte é lido da esquerda para a direita agrupando conjunto de caracteres em conjuntos (ou tokens).
        
        Exemplo: montante = depósito + taxa * 60

        - Id : montante, depósito, taxa
        - At : "="
        - Ad : "+"
        - Mu : "*"
        - Nu : "="


    - Análise hierárquica (análise gramátical)

        Os tokens são agrupados hierarquicamente em coleções aninhadas com significado coletivo.

    - Análise semântica

        Realização de algumas verificações:

        - Tipos;
        - Parâmetros da função;

        

2. Fase de síntese
    - Geração de código intermediário
    - Otimização de geração de código;



* Tabela de símbolos: é uma estrutura de dados contendo uma entrada para cada identificador com os campos contendo atributos deste identificador

- Detecção de erros:
    - Análise léxica - quando tempos um conjunto de caracteres que não é agrupado e ququalquer token.
ex. 1abc

    - Análise sintática: quando uma sequencia de tokens não atende à regras estruturais da linguagem
    Ex: a+*b

    - Análise semântica: quand aplicamos uma operaçã sobre tipos incompatíveis