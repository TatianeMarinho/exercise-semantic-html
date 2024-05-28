# Trybe

Este repositório contém atividades de aprendizagem desenvolvidas por Tatiane Marinho [linkedin](https://www.linkedin.com/in/marinhotatiane/) enquanto estudava na [Trybe](https://www.betrybe.com/).

_"A Trybe é uma escola do futuro para qualquer pessoa que queira melhorar de vida e construir uma carreira de sucesso em tecnologia, onde a pessoa só paga quando conseguir um bom trabalho."_

O programa conta com mais de 1.500 horas de aulas presenciais e online, aborda introdução ao desenvolvimento de software, front-end, back-end, ciência da computação, engenharia de software, metodologias ágeis e habilidades comportamentais.<br>

<details>
  <summary><strong>O que foi desenvolvido</strong></summary><br />

Foi desenvolvido uma página HTML usando as principais tags semânticas.

</details>

<details>
<summary><strong>Dependências</strong></summary><br />
Para instalar as dependências :  - `npm install`

</details>

<details>
<summary><strong>Testes</strong></summary><br />
**Testes desenvolvidos pela Trybe**

Todos os requisitos do projeto foram testados **automaticamente** por meio do `Cypress`. 

## Observações técnicas

Alguns requisitos seguiram um padrão pré-estabelecido para que os testes automáticos funcionem corretamente. 
- Os requisitos do projeto foram avaliados automaticamente, sendo utilizada a resolução de tela de `1366 x 768` (1366 pixels de largura por 768 pixels de altura).

</details>

<details>
<summary><strong>Estrutura do projeto</strong></summary>

Foram criados os arquivos **index.html** e **style.css** que contém o meu código HTML e CSS, respectivamente. Observe que os seus arquivos **devem** possuir esses nomes para que o meu projeto fosse testado corretamente pelo avaliador automático.

</details>

# Requisitos
## 01 - Adicione um cabeçalho na página

Você deve criar um cabeçalho na página e adicionar um título nele com o seguinte conteúdo:`Soco a 80km/h: Conheça o Stomatopoda`.

<details>
  <summary><strong>O que será testado:</strong></summary>

- Existe um cabeçalho na página com a tag adequada;
- Existe um título dentro do cabeçalho;
- O texto do título é `"Soco a 80km/h: Conheça o Stomatopoda"`.

</details>

## 02 - Adicione um conjunto de links que representam a área de navegação do site

Você deve criar uma área de navegação contendo três links chamados `Página Inicial`, `Sobre` e `Contato`.

<details>
  <summary><strong>O que será testado:</strong></summary>

- Existe uma área de navegação no site com a tag adequada;
- O primeiro link está com o texto `"Página Inicial"`;
- O segundo link está com o texto `"Sobre"`;
- O terceiro link está com o texto `"Contato"`.

</details>

## 03 - Crie um artigo que vai conter os fatos interessantes sobre o `Stomatopoda`

O artigo deve ter um subtítulo (h2) com o texto `Fatos sobre o Stomatopoda`. Segue [um site animal](https://theoatmeal.com/comics/mantis_shrimp) de inspiração para pegar fatos.

<details>
  <summary><strong>O que será testado:</strong></summary>

- Existe um artigo na página com a tag adequada;
- Existe um subtítulo com a tag `h2` dentro do artigo;
- O texto do subtítulo é "Fatos sobre o Stomatopoda".

</details>

## 04 - Divida o artigo em seções

Divida o artigo em seções, organizando-o da seguinte forma:

- Uma primeira seção contendo informações gerais a respeito do animal. O subtítulo (h3) para essa seção fica a seu critério. É necessário que conste nessa seção seu *nome científico*, que é `Odontodactylus scyllarus`, em itálico. Além disso, é preciso que haja informação tabular a respeito de sua classificação científica, em específico: `Reino`, `Filo`, `Subfilo`, `Classe`, `Subclasse` e `Ordem`. Tais informações você consegue obter [na Wikipedia.](https://pt.wikipedia.org/wiki/Stomatopoda)

- As outras seções dizem respeito aos fatos interessantes que você escolheu acerca do animal. Para cada fato escolhido você vai criar uma seção.

- Adicione, para cada seção, um subtítulo referente ao fato escolhido.

<details>
  <summary><strong>O que será testado:</strong></summary>

- `"Odontodactylus scyllarus"` aparece em itálico na primeira seção;
- Existe um subtítulo com a tag `h3` para cada seção.

</details>

## 05 - Adicione mais informações as seções do artigo criado no exercício anterior

Neste exercicio você deve continuar seguindo as regras do requisito anterior.
Ainda dentro do artigo criado no exercicíco 4, também faça:

- A adição, para cada seção, de parágrafo(s) descrevendo o fato escolhido. Destaque características impressionantes referentes ao fato que você escolheu, de forma a reforçar a unicidade do `Stomatopoda`. Por exemplo: se você criar uma seção detalhando o soco potente do animal, seria interessante destacar a velocidade desse soco (80km/h) em negrito.

- A adição, para cada seção, de uma imagem, como forma de ilustrar o fato.

- A adição, de uma seção de referências bibliográficas, contendo uma lista de todos os links que foram usados como base para compilar a página em questão.

<details>
  <summary><strong>O que será testado:</strong></summary>

- Existem pelo menos duas seções no artigo;
- Existe um subtítulo com a tag `h3` para cada seção nova;
- Existe uma imagem para cada seção;
- A última seção contém links dentro de uma lista não ordenada.

</details>

## 06 - Adicione um conteúdo ao lado do artigo

Adicione um conteúdo ao lado do artigo, disponibilizando um link para [este vídeo](https://www.youtube.com/watch?v=E0Li1k5hGBE) que mostra o animal em ação. <br />
:sparkles: Dica: Você pode conferir no conteúdo modular os [elementos semânticos](https://app.betrybe.com/learn/course/5e938f69-6e32-43b3-9685-c936530fd326/module/fc998c60-386e-46bc-83ca-4269beb17e17/section/99759b1d-d4d2-4691-b063-06aafa8ac7cd/day/cdc0f1a4-1922-4e70-b49b-90c69cb5abff/lesson/17adb3c9-55f9-408e-94b5-971d10934743) e ver qual deles é usado para o entorno do conteúdo principal 😉.

<details>
  <summary><strong>O que será testado:</strong></summary>

- Existe um conteúdo ao lado da página com a tag adequada;
- Existe um link dentro do conteúdo ao lado com o endereço `"https://www.youtube.com/watch?v=E0Li1k5hGBE"`.

</details>

## 07 - Adicione um rodapé na página

Adicione um rodapé na página, mostrando a seguinte mensagem:

```html
"Conteúdo compilado por <insere seu nome>, <ano atual>".
```

<details>
  <summary><strong>O que será testado:</strong></summary>

- Existe um rodapé na página com a tag adequada;
- Existe o texto `"Conteúdo compilado por <insere seu nome>, <ano atual>"` no rodapé da página.

</details>

<br>

*Exercicíos criado pela [Trybe](https://www.betrybe.com/)
