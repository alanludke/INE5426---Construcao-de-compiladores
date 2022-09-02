# Construção de compiladores

## Fundamentos para  construção de compiladores

- Geradores de analisadores léxicos: geram automaticamente analisadores léxicos, dado a especificação do token (através de expr. regular ou automato finito.) Ex: Lex. PLY, etc

- Geradores de analisadores sintáticos: geram automaticamente analisadores sintáticos, dado uma gramática livre de contexto. Ex: Yacc, PLY

- Dispositivos de tradução dirigido por sintaxe: percorrer uma árvore de derivação

- Gerador automático de código: tradução de código intermediário para código já 
