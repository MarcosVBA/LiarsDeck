# Baralho do Mentiroso

Um jogo de cartas e blefe em que cada aposta diz quantas cartas de certos naipes estão nas mãos dos jogadores. Aumente a aposta, use figuras com poderes ou pague pra ver — e tente terminar a partida com o menor número de derrotas.

O projeto inclui um simulador para **2 a 6 jogadores**, com **4 a 6 cartas por pessoa** e adversários automáticos. Funciona no navegador, adapta-se a celulares e pode ser instalado como aplicativo web para jogar offline após o primeiro acesso.

## Como jogar

1. Faça uma aposta dizendo um naipe e a quantidade mínima de cartas desse naipe que acredita existir em todas as mãos.
2. Na sua vez, aumente a aposta ou pague pra ver. Ao duvidar, todas as mãos são reveladas: se a aposta se confirmar, quem duvidou perde; caso contrário, quem apostou perde.
3. Use Rei, Rainha e Valete para mudar o rumo da rodada. Coringas contam para qualquer naipe.
4. A partida termina quando alguém acumula três derrotas. Vence quem tiver menos derrotas, com desempate conforme as regras.

Consulte as [regras completas](regras-finais.md) para os poderes, as penalidades e o desempate.

## Jogar localmente

Abra `simulador.html` no navegador para jogar. Para testar a instalação e o modo offline, sirva a pasta localmente, por exemplo:

```sh
python -m http.server 8000
```

Acesse `http://localhost:8000/`. Os nomes dos jogadores são salvos no armazenamento local do navegador.

## Publicar no GitHub Pages

Envie os arquivos para o repositório e, em **Settings → Pages**, escolha **Deploy from a branch**, a branch `main` e a pasta `/ (root)`. No GitHub Free, o repositório precisa ser público. Para o repositório `MarcosVBA/LiarsDeck`, o endereço esperado é <https://marcosvba.github.io/LiarsDeck/>.

A instalação em celulares exige acesso ao site por HTTPS. No iPhone, use o menu de compartilhamento do navegador e escolha **Adicionar à Tela de Início**.

## Arquivos principais

- `simulador.html` — interface e lógica do jogo.
- `index.html` — entrada do site, que abre o simulador.
- `manifest.webmanifest`, `service-worker.js` e `icons/` — instalação e funcionamento offline.
- `regras-finais.md` — regras e convenções do simulador.

O projeto é estático e não precisa de servidor de aplicação nem de dependências para funcionar.
