# PAP - Jogo de Estratégia Tática 2D

Projeto de Prova de Aptidão Profissional (PAP). É um jogo 2D de estratégia híbrida que junta gestão no mapa-mundo por turnos com combates táticos em tempo real 1v1, feito para rodar em PCs fracos.

## Objetivo

Desenvolver um jogo completo em Godot aplicando uma arquitetura dupla (GDScript para interface/mapa e C# para matemática de combate e IA), com foco em mecânicas de moral, IA simétrica e eventos apocalípticos.

## Tecnologias Usadas

* **Engine:** Godot Engine (versão Mono / C#)
* **GDScript:** Menus, UI, lógica do mapa-mundo por turnos e diplomacia.
* **C#:** Simulação das batalhas em tempo real, cálculo de moral, IA e física.

## Resumo das Mecânicas

* **Mapa-Mundo (Turnos):** Movimentação de tropas, gestão de economia, leis e diplomacia.
* **Batalhas (Tempo Real):** Controlo direto de unidades. O Herói é a âncora de moral; se a moral chegar a zero ou o Herói morrer, as tropas entram em pânico e fogem do mapa.
* **Apocalipse:** Eventos globais ativados por leis (ex: Elfos a reviver a Árvore da Vida), que forçam todas as outras raças a fazer uma aliança temporária para parar o cataclismo.

## Fações

* **Humanos:** Democracia medieval, Heróis com magias fortes e recrutamento rápido. Usam Cristais Aether (minados em Planícies).
* **Elfos:** Ditadura tecnológica com armas de fogo, tanques e artilharia. Defesa fanática na capital. Usam Ferro (minado em Montanhas).
* **Ratos🐭:** Enxame de unidades baratas, subcidades invisíveis e conversão de prisioneiros. Usam Mutagéneo (ganho em batalhas).
