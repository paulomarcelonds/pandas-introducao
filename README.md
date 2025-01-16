# Introução inicial

## Que tipo de dados o Pandas manipula

Para carregar o pacote pandas precisa primneiro importar usando o alias `pd`, esse alias é usado pela comunidade e é assumnida como padrão pela documentação.

```python
import pandas as pd
```

## Representação de um DataFrame

![alt text](image.png)

Um dataframe funciona como uma planilha do excel ou uma tabela SQL, em sua estrutura possui uma coluna na vertical e uma linha na sua horizontal.

O data dataframe é uma estrutura de dados bidimensional capaz de armazenar dados dos tipos: caracteres, inteiros, flutuantes, dados categóricos e mais. Esta tabela possui 3 colunas cada uma possui um rotulo que são: ``Name``, ``Age`` e ``Sex``.
1. Coluna `Name` possui dados do tipo string.
2. Coluna ``Age`` possui dados do tipo inteiro.
3. Coluna ``Sex`` possui dados do tipo string.

É um software de planilha como **Excel** ou **LibreOffice Calc** por exemplo a representação da tabela ficaria muito semelhante como na imagem abaixo:

![alt text](image-1.png)

## Cada coluna em um DataFrame é um Series

![alt text](image-2.png)

Exemplo de uma series, trabalhando com a coluna ``Age``

```python
In [4]: df["Age"]
Out[4]: 
0    22
1    35
2    58
Name: Age, dtype: int64
```

s