# code-challenge

## Cálculo da Média Total Anual
**Requisitos**
- O ano letivo é dividido em 4 bimestres;
- Cada bimestre terá 4 notas avaliativas;
- O programa deve:
  - Calcular a média de cada bimestre;
  - Calcular a média anual baseada nas médias dos 4 bimestres;
- O programa deve validar que todas as notas estão no intervalor de 0 a 10;
- As médias devem ser arredondadas para 2 casas decimais;
- Exiba as médias de cada bimistre e a média anual ao final;
- As notas devem estar pré-definiadas no código


Ponto de partida:

```js
const MEDIAS = {
  "1-BIMESTRE": [10, 8.5, 7, 9],
  "2-BIMISTRE": [9, 8.5, 7, 6],
  "3-BIMISTRE": [7.5, 8.5, 7, 9],
  "4-BIMISTRE": [1, 8.5, 7, 10],
};
```

Saída esperada:

```js
mediaGeral 7.72
media por bimestre {
  '1-BIMESTRE': 8.63,
  '2-BIMISTRE': 7.63,
  '3-BIMISTRE': 8,
  '4-BIMISTRE': 6.63
}
```
   
