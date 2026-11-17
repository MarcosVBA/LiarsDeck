# Baralho do Mentiroso

## Objetivo

Faça apostas sobre quantas cartas de determinados naipes estão nas mãos de todos os jogadores. Aumente as apostas, use os efeitos das cartas e decida quando duvidar.

A partida termina quando um jogador acumula **três derrotas**. Vence quem tiver **menos derrotas** nesse momento.

## Material e preparação

- Um baralho de **54 cartas**: 52 cartas comuns, divididas igualmente entre copas, ouros, espadas e paus, mais dois coringas.
- Para uma partida com **quatro jogadores**, distribua **quatro cartas para cada pessoa**.
- As cartas restantes ficam fora da rodada, sem que os jogadores vejam seu conteúdo.
- Cada jogador pode olhar a própria mão. As cartas dos adversários permanecem ocultas, exceto quando uma regra determinar sua revelação.

Os números das cartas não importam para as apostas: contam os **naipes**, os coringas e os efeitos de rei, rainha e valete.

## Como jogar uma rodada

O jogador que embaralhou começa. Depois de olhar sua mão, ele anuncia um naipe e uma quantidade. Por exemplo, **“quatro copas”** significa que acredita haver **pelo menos quatro cartas que contam como copas** somando todas as mãos.

O jogo segue em sentido horário. Na sua vez, o jogador deve **aumentar a aposta** ou **pagar pra ver**, isto é, duvidar da aposta anterior. As cartas com poderes podem alterar uma jogada conforme as regras abaixo.

### Aumentar

Enquanto a aposta envolver um único naipe:

- Para manter o mesmo naipe, aumente a quantidade em **pelo menos uma carta**. Exemplo: de quatro copas para cinco copas.
- Para trocar de naipe, aumente a quantidade em **pelo menos duas cartas**. Exemplo: de quatro copas para seis espadas.

Quando um Valete tiver acrescentado um segundo naipe, a aposta passa a ter **um único total para os dois naipes**. Nas jogadas seguintes, mantenha esses naipes e aumente o total em pelo menos uma carta.

### Pagar pra ver

Quando alguém duvida, todos revelam suas mãos e contam as cartas que atendem à aposta:

- Se houver **pelo menos** a quantidade apostada, a aposta se confirma e **quem duvidou perde**.
- Se houver menos que a quantidade apostada, a aposta falha e **quem fez a aposta perde**.

Para uma aposta com dois naipes, some as cartas de ambos e os coringas disponíveis. Cada coringa conta **uma única vez** no total.

Exemplo: para a aposta “sete copas e espadas”, quatro copas, duas espadas e um coringa totalizam sete cartas. A aposta se confirma.

## Derrotas e próximas rodadas

Cada derrota faz o jogador manter **uma carta a mais revelada** nas rodadas seguintes. Portanto, uma derrota significa uma carta revelada; duas derrotas, duas cartas reveladas. **Antes de olhar a mão**, separe aleatoriamente a quantidade necessária e deixe essas cartas abertas. O jogador não escolhe quais serão reveladas.

As cartas abertas por derrota continuam na mão e contam normalmente para as apostas, mas **seus efeitos não podem ser usados**. A quantidade de cartas distribuídas ao jogador **não diminui**.

Se ninguém tiver chegado a três derrotas, **o jogador que perdeu o desafio embaralha e distribui as novas mãos**. Ele também faz a primeira aposta da próxima rodada. As penalidades continuam valendo na nova mão.

## Cartas especiais

Cada jogador pode usar **no máximo um efeito de figura por turno**. Isso inclui rei, rainha e valete. Figuras abertas por derrota não podem ativar seus efeitos.

### Rei — troca de mãos

Todas as mãos passam ao próximo jogador em sentido horário, ao mesmo tempo. As cartas já reveladas continuam públicas após a troca. O jogador que usou o Rei continua na vez, mas não pode usar outra figura nesse turno, inclusive da mão recebida.

### Rainha — revelar e bloquear um naipe

A Rainha só pode ser usada quando já existe uma aposta; não pode ser usada para abrir a rodada.

O jogador escolhe um naipe que ainda não esteja bloqueado e que não faça parte da aposta atual. Todos revelam as cartas desse naipe em suas mãos, e ele fica **bloqueado para novas apostas até o fim da rodada**.

Depois de ver as cartas reveladas, quem usou a Rainha pode aumentar a aposta ou pagar pra ver.

### Valete — somar dois naipes

O Valete só pode ser usado **ao aumentar uma aposta existente**, no máximo **uma vez por rodada**. O jogador acrescenta um segundo naipe disponível e anuncia um novo **total**, maior que o da aposta anterior. A vez passa ao próximo jogador.

Exemplo: após “quatro copas”, um jogador pode usar o Valete e apostar “sete copas e espadas”. Para confirmar essa aposta, somam-se as cartas de copas, as de espadas e os coringas, cada um contado uma vez. Não há uma quantidade mínima separada para cada naipe.

### Coringa — qualquer naipe

O coringa conta para qualquer naipe apostado. Ele não tem outro poder. Em uma aposta com dois naipes, **cada coringa conta apenas uma vez**, não uma vez para cada naipe.

## Fim de jogo

Assim que uma pessoa sofrer sua **terceira derrota**, a partida termina. Compare o número de derrotas de todos os jogadores: quem tiver menos vence. Se houver empate na menor quantidade, vence quem causou a última derrota, desde que esteja entre os empatados: quem duvidou, se a aposta falhou, ou quem apostou, se a aposta se confirmou. Caso essa pessoa não esteja entre os empatados, eles dividem a vitória.

## Convenções usadas no simulador

Os pontos a seguir completam o funcionamento do simulador e podem ser revistos durante os testes:

- **Desempate:** se mais de um jogador tiver o menor número de derrotas, vence quem causou a última derrota se estiver entre os empatados; caso contrário, os empatados dividem a vitória.
- **Uso de poderes:** cada carta de poder pode ser usada uma vez por rodada. Ao usá-la, o jogador a revela; ela continua na mão e na contagem.
- **Troca com o Rei:** informações já reveladas continuam conhecidas. Depois da troca, as cartas abertas por derrota continuam sem efeito. Se a mão recebida tiver menos cartas de penalidade do que as derrotas do novo dono, cartas adicionais são separadas aleatoriamente para completar a penalidade.
- **Quantidade de jogadores e cartas:** o simulador também permite configurações de dois a seis jogadores e de quatro a seis cartas por pessoa. A configuração discutida como referência é de quatro jogadores com quatro cartas cada.

