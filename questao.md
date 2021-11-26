# Atividade 07

## Correção: 0,5. Por que parou na metade?

## Saulo Bruno de Freitas Lino

### Questão 01

**id * (id + id)**

Pilha  | Entrada  | Ação
------ | -------- | -----
0      | id*(id+id)$| Deslocar 5
0id5   | *(id+id)$  | Reduzir 6
0F3    | *(id+id)$    | Reduzir 4
0T2    | *(id+id)$    | Deslocar 7
0T2*7  | (id+id)$     | Deslocar 4
0T2*7(4 | id+id)$     | Deslocar 5
0T2*7(4id5 | +id)$    | Reduzir 6
0T2*7(4F3  | +id)$    | Reduzir 4
0T2*7(4T2  | +id)$    | Reduzir 2
0T2*7(4E8  | +id)$    | Deslocar 6
0T2*7(4E8+6 | id)$    | Deslocar 5
0T2*7(4E9+6id5 | )$   | Reduzir 6
0T2*7(4E9+6F3  | )$   | Reduzir 4 
0T2*7(4E9+6T9  | )$   | Reduzir 1
0T2*7(4E8      | )$   | Deslocar 11
0T2*7(4E8)11   | $    | Reduzir 5
0T2*7F10       | $    | Reduzir 3
0T2            | $    | Reduzir 2
0E1            | $    | Aceitar
