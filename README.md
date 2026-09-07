# DanMachi Infinite Combate — Tradução PT-BR v1.0

Tradução para português do Brasil de **Is It Wrong to Try to Pick Up Girls in a
Dungeon? Infinite Combate** (PC / Steam).

<img width="2048" height="768" alt="nexus" src="https://github.com/user-attachments/assets/92021fb6-7d3c-4dd3-9209-34f46ca21992" />


O jogo inteiro: a história, o menu e a arte.

> ⚠️ **O jogo precisa estar em INGLÊS.** Esta tradução ocupa o lugar do idioma
> inglês — ela não acrescenta um idioma novo.

---

## O que está traduzido

| | |
|---|---|
| Falas da história — as duas rotas, do prólogo ao final | 12.604 |
| Textos de menu — itens, equipamentos, habilidades, missões | 1.449 |
| Peças de arte nos atlas — janelas, botões, rótulos, medalhões | 311 |
| Imagens de tela cheia — 137 cartões, 133 cartas, 35 dicas | 305 |
| Glifos acentuados acrescentados à fonte do jogo | 69 |

---

## Traduzida do japonês, não do inglês do jogo

O inglês oficial é a base mais fácil, e é também onde moram erros que a
tradução copiaria sem perceber.

| Japonês | Aqui | O inglês do jogo |
|---|---|---|
| `ジャガ丸くん` | **Jaga Maru-kun** | "Cheesy Fried Potatoes" — apagou a marca |
| `リヴィラ` | **Rivira** | "Livira" — leitura errada do katakana |
| `インファントドラゴン` | **Infant Dragon** | "Baby Dragon" — invenção |
| `ボールス` | **Bors** | "Voles" |

E há erro de sentido, não só de nome: na descrição de um item o japonês diz
`少しだけ` — "só um pouco" — e o inglês escreveu *"vastly increases defence"*,
copiando a linha do item seguinte.

Os termos da série seguem a legenda oficial da Crunchyroll: **Dungeon**,
**Falna** e **Família** ficam, e **Valis** também, que é o nome da moeda. As
alcunhas saem na forma da franquia (**Nine Hell**, **Braver**, **Thousand
Elf**); a da Aiz sai traduzida (**Princesa da Espada**) porque é assim que ela
aparece na campanha.

---

## A arte

Boa parte do que se lê no DanMachi não é texto: é palavra desenhada dentro da
imagem. Trocar isso não é editar uma string — é apagar a letra sem estragar o
que está por baixo e redesenhar por cima. Em muitas peças a letra fica sobre
ornamento: a trepadeira dourada dos títulos de janela passa **por trás** das
palavras.

Cada peça foi medida contra a original — altura de maiúscula, condensação,
espessura do contorno, cor do degradê — com tudo amostrado da própria arte do
jogo em vez de arbitrado.

---

## Verificação

Cada peça instalada é relida do arquivo do jogo e comparada com o que se mandou
gravar. O pacote não é montado do que estava instalado: sai de uma reconstrução
completa a partir dos arquivos originais, numa passada só.

```
texto      48.615 strings conferem, 0 falham
menu       1.449 de 1.449, 0 erros
CSV        as 3 tabelas PT batem, as outras 12 intactas
atlas      images 254 · prefabs 1 · resources 46 · sharedassets0 5 ·
           sharedassets2 5  = 311 peças, byte a byte
bundles    title 137 · tips 35 · quest_title 133 = 305 imagens, byte a byte
```

---

## Instalação

1. Feche o jogo.
2. Deixe o idioma do jogo em **inglês**.
3. Copie a pasta `danmachi_Data` do zip para dentro da pasta do jogo, por cima
   da que já existe, aceitando substituir.

```
...\steamapps\common\Is It Wrong to Try to Pick Up Girls in a Dungeon Infinite Combate\
```

**Desinstalar:** na Steam, botão direito no jogo → Propriedades → Arquivos
instalados → Verificar integridade dos arquivos. São 12 arquivos, e a Steam
devolve os originais.

Versão pirata, de outra loja ou de console não é suportada.

---

## O que ficou em inglês, e por quê

- **As 52 fichas de personagem.** O texto ali fica sobre a cena, e apagá-lo
  exige reconstruir o brasão da Família que está por trás. O que dava para
  recuperar não ficou bom o bastante — e ficha com defeito visível é pior que
  ficha em inglês. Fica para uma versão futura.
- **O manual** (26 páginas) e **o tutorial** (50 telas), que são imagens de
  texto corrido e captura de tela.
- O **`Yes`/`No`** das caixas de confirmação, que mora dentro do executável.

## Sobre o tamanho

Um giga é bastante para uma tradução, e a razão é a arte: as cartas de missão e
os cartões de capítulo são 275 imagens de tela cheia em PNG sem perda, e
sozinhas somam 800 MB. Mandar menos exigiria recomprimir com perda a arte que o
jogo desenha.

---

*A extração e a remontagem dos pacotes Unity usam a biblioteca **UnityPy**. Os
acentos foram construídos a partir da fonte do próprio jogo, que é da
**Fontworks Inc.***

*©Fujino Omori-SB Creative Corp./Sword Oratoria Project ©MAGES. Publicado por PQube. Todos os direitos reservados. Projeto de fã, gratuito e sem fins lucrativos, sem vínculo com MAGES., PQube, SB Creative ou os detentores da obra.*
