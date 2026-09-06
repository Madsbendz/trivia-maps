# trivia-maps

Regionale kort til geografiquizzer: et kort per land, hvor landet er fremhaevet
i `#47ade6` og naboerne staar i landfarve med synlige graenser.

- **1600 x 1030 PNG**, 164 lande
- Filnavnet er landets Natural Earth-navn (`United_States_of_America.png`).
  Det navn er ikke altid quizsvaret - se `kort_egnet.csv` i pipelinen.
- Kun souveraene stater der er store nok at se fremhaevet. Territorier,
  ikke-anerkendte stater og mikrostater er sorteret fra.

## Kilde og licens

Geometrien er [Natural Earth](https://www.naturalearthdata.com/) 1:50m
Admin 0 Countries, som er **public domain**. Kortene er tegnet med `sf` og
`ggplot2` og er dermed ogsaa frit anvendelige. Ingen kreditering paakraevet.

Tegnet af `lav_landekort.R`; udvalget bestemt af `tjek_kort_egnet.R`.
