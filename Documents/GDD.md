# Take over the castle

Jogo de uma página feito para treinamento, onde você desafia ou coopera com outros jogadores pela posse do castelo dos monstros.

## Indice

- [Documentação](#documentação)
  - [Highconcept](#highconcept)
    - [Enredo](#enredo)
    - [Gameplay](#gameplay)
      - [Ações](#acoes)
      - [Regras](#regras)
      - [Elementos](#elementos)
      - [Caminhos](#caminhos)
    - [Interface](#interface)
    - [Cronograma](#cronograma)
    - [Ideias](#ideias)
    - [Meios](#meios)

<a name="documentação"></a>

## Documentação

Todas as informações de criação do projeto estão amntidas aqui, todas as informações estão sujeitas a modificações.

<a name="highconcept"></a>

## Highconcept

O jogador controla um guerreiro de Zathar, progredindo por um tabuleiro, lutado contra monstros e se tornando mais forte, para então derotar o rei Fertos e com isso a tomar o seu castelo.

<a name="enredo"></a>

## Enredo

Você um nobre guerreiro de Zathar, é convoncado para lutar em uma investida as terras do rei Fernos. Seu objetivo é o derrota-lo e tomar os castelo, mas para isso você deve aprender com sua jornada e estar preparado para a grande luta final.

<a name="gameplay"></a>

## Gameplay

Com o auxílio do recurso chamado de Estamina, o jogador podera fazer quantas jogadas quiser respeitando as regras que circulam esse elemento, entre as diversas ações podemos nomiar aqui a de se mover, pegar, fugir, descansar e atacar onde nessa podera um dado para uma tentativa de dublicar o dano.

<a name="acoes"></a>

## Ações

- Pegar
  - Custa um de estamina.
  - Pegar um item e colocalo no seu inventario.
- Atacar
  - Custa um de estamina.
  - Atacar um inimigo que esteja no mesmo quadrado que você.
- Tentar dano dublo
  - Custa um de energia.
  - Caso caia 1 ou 6 jogador dá o dobro de ataque.
- Fugir
  - Custa três de estamina.
  - Dá a chance do jogador sair do quadrado de combate.
- Descansar
  - Recupera um de estamina.
  - Só se pode desancas uma vez por jogada e se tiver manos de três de estamina.


<a name="regras"></a>

## Regras

 - Inicia com dez de vida.
 - Inicia com cinco de estamina.
 - Inicia com um de ataque.
 - Inicia com zero de defesa.
 - Três de estamina resulta em menos um de vida por ação, Dois de estamina, menos dois por ação, Um de estamnia, menos 3 por ação, 0 de estamina, menos 5 por ação.
 - Não anda na diagonal.
 - Entra em modo combate, quando estiver em um quadrado de inimigo.
 - Só sai de um combate com a ação fugir.
 - Apenas três elementos podem ser postos no inventário.
 - Montros a serem mortos dão ao jogador a opção de ganhar Ataque ou Defesa equivalente a metade do poder do ataque do inimigo morto.
 - Jogo jogável em uma, duas ou quatro pessoas.
 - Monstros tem poder de ataque duplicado caso jogue em cooperativo.
 - Número maximo cooperativo 2.
 - Jogadores não cooperantes, não atacam o mesmo inimigo. 
 - Quadrados de inimigos atacados sem jogadores e que tenham duas fugas se regeneram.
 - Todos os elementos consumiveis do jogo reaparecem depois de que todos do mesmo tipo forem pegos. 
 - Ganha quem derotar o rei do castelo.
 - Perde quem morrer.

<a name="elementos"></a>

## Elementos

- ![Attack](https://github.com//Dilumo/Morin-s-test/blob/master/Documents/Assets/Attack.png?raw=true "Attack") <br> 
**Attack:** Jogador recebe um ponto de ataque.
- ![Defense](https://github.com//Dilumo/Morin-s-test/blob/master/Documents/Assets/Defense.png?raw=true "Defense") <br> 
**Defense:** Jogador recebe um ponto de defesa.
- ![Apple](https://github.com//Dilumo/Morin-s-test/blob/master/Documents/Assets/Apple.png?raw=true "Apple") <br> 
**Apple:** Jogador recebe um ponto de estamina e um de vida.
- ![Health](https://github.com//Dilumo/Morin-s-test/blob/master/Documents/Assets/Health.png?raw=true "Health") <br> 
**Health:** Jogador recebe três pontos de vida.

<a name="caminhos"></a>

## Caminhos

- ![Empty](https://github.com//Dilumo/Morin-s-test/blob/master/Documents/Assets/Empty.png?raw=true "Empty") <br> 
**Empty:** Mover-se sobre ele consome um de estamina.
- ![Rough ](https://github.com//Dilumo/Morin-s-test/blob/master/Documents/Assets/Rough.png?raw=true "Rough ") <br> 
**Rough :** Mover-se sobre ele consome dois de estamina.
- ![Hills ](https://github.com//Dilumo/Morin-s-test/blob/master/Documents/Assets/Hills.png?raw=true "Hills ") <br> 
**Hills :** Mover-se sobre ele consome três de estamina.
- ![Walls ](https://github.com//Dilumo/Morin-s-test/blob/master/Documents/Assets/Walls.png?raw=true "Walls ") <br> 
**Walls :** Mover-se sobre ele consome quatro de estamina.

<a name="interface"></a>

## Interface

>![Explicação da interface](https://github.com/Dilumo/GetTheCastle/blob/master/Documents/Assets/interface.png?raw=true "Explicação da interface") <br> 
 > **Fonte:** Acervo pessoal.

<a name="cronograma"></a>

## Cronograma


| Dias          | Função        |  Data  |
| ------------- |:-------------:| -----: |
| Segunda       | Protótipo     | 15/05  |
| Terça         | Teste 01      | 16/05  |
| Quarta        | Interface     | 17/05  |
| Quinta        | Arte          | 18/05  |
| Sexta         | Arte          | 19/05  |
| Sábado        | Revisão       | 20/05  |
| Domingo       | Teste 02      | 21/05  |
| Segunda       | Texto post    | 22/05  |
| Quarta        | Postagem      | 24/05  |

<a name="ideias"></a>

## Ideias

Conforme o processo de criação idias para expação desse jogo dever ser postas aqui.

<a name="meios"></a>

## Meios

Usei as dependências da minha casa para produzir esse jogo.

- Inkscape
- Visual Studio Code
- GitHub