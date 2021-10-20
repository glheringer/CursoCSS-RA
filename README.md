# Treinamento CSS Rethink Academy
- 01 • Grid  
- 02 • Propriedade Min e Max 
- 03 • Padding / Margin 
- 04 • Z-index  
- 05 • Flex box 
- 06 • Introdução ao SASS 

## Dia 1(01,02,03)

Bootstrap: Facilitador de de frameworks.

##GRIDS
- Utiliza Bootstrap
- Divisão da tela em 12 colunas, linhas infinitas
- Pode separar a divisão da maneira que preferir
- Separação em divs

class="container" -> Conjunto de linhas 
class="row" -> linha 
class="col" -> coluna


---------------------------------------------------
### Min e Max usado apenas nas propriedades width e height.
 - Propriedade de divs:
bash
.div{max-width:100px; min-heigth: 100px}


- min faz referência  ao tamanho mínimo aceito para a propriedade, assim como o max faz referência  ao tamanho máximo  aceito pela propriedade.

- Ele adapta ao dispositivo, descendo os elementos de acordo com a redução  da resolução. O que possibilita utilização  do mesmo código  pra infitos dispositivo.


Proporção  vw vh:


---------------------------------------------------
### Padding / Margin:

Movimentação  absoluta em ambos, não se difere ao mudar o tamanho da tela, não  usar variável  de tamanho em nenhum dos dois, recomendado usar position

- Padding: A propriedade usada para gerar espaço  em trono de um elemento, dentro de quaisquer bordas definidas de forma absoluta, ou seja a partir das bordas ele empurrará o conteúdo  para dentro. Usa apenas o conteudo, nao leva em consideração  o site.

- Margin: A propriedade usada para gerar espaço por fora de um elemento. Mexe nos conteudos adjacentes. Deve-se usar com cuidado, pois vai superar ou puxar os espaços e conteúdos dos elementos ao adjacentes .

