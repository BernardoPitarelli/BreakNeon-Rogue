# BreakNeon Rogue

BreakNeon Rogue é um jogo de navegador inspirado no clássico Breakout e desenvolvido como trabalho para a Feira de Ciências do Colégio Pentágono – Santo André, representando o 8º ano do período da manhã.

O projeto é um exercício de vibe coding. O jogo foi desenvolvido integralmente pelo agente de inteligência artificial Codex, do ChatGPT, com a orientação do aluno Bernardo Pitarelli, responsável por definir as ideias, regras, mecânicas, ajustes de dificuldade e decisões criativas adotadas durante o desenvolvimento.

## Sobre o jogo

O jogo combina a mecânica de destruir blocos com elementos roguelite, progressão por andares, loja de melhorias, relíquias permanentes, conquistas, fases bônus e chefes com padrões próprios de combate.

No modo Campanha, o jogador percorre cinco andares. Os três primeiros possuem três níveis antes do chefe, o quarto possui quatro e o quinto possui cinco. Entre os andares existe uma fase bônus que pode conceder uma melhoria gratuita. A campanha termina após a vitória sobre o quinto chefe.

No modo Infinito, os campos são gerados continuamente, a dificuldade aumenta de forma progressiva e o melhor resultado fica registrado no navegador.

## Mecânicas principais

O BreakNeon Rogue possui blocos regenerativos, invisíveis, teleportadores, congelantes, fortificados, elétricos e inquebráveis. O jogador pode adquirir melhorias como Multibolas, Bolinha Gigante, Bola de Fogo, Bola Perfurante, Impacto Crítico, Laser Automático, Holo Escudo, aumento de vida máxima e expansão da raquete.

Os cinco chefes apresentam ataques telegrafados, períodos de invulnerabilidade e comportamentos específicos. O quarto chefe possui duas fases, o quinto possui três, e todos são imunes ao laser.

O sistema de combos aumenta a pontuação quando vários blocos são destruídos sem que a bola seja perdida. Relíquias obtidas após os chefes oferecem vantagens permanentes, enquanto as compras da loja são reiniciadas a cada nova partida.

## Controles

Use o mouse, o toque, as setas direcionais ou as teclas A e D para movimentar a raquete. Pressione Espaço, clique ou toque no campo para lançar a bola. Quando adquirido, o laser dispara automaticamente enquanto houver uma bola em movimento. Pressione P ou Esc para pausar.

## Salvamento

Conquistas, relíquias, recordes e a partida em andamento são salvos automaticamente no `localStorage` do navegador. A opção “Iniciar um novo jogo” reinicia as relíquias da campanha, enquanto “Continuar” recupera o progresso salvo. A limpeza dos dados do site no navegador também apaga o salvamento.

## Como executar

Abra `outputs/BreakNeon_Rogue.html` em um navegador moderno. Não é necessário instalar dependências, iniciar um servidor ou executar uma etapa de compilação. É necessária conexão com a internet para carregar Tailwind CSS, Lucide Icons e as fontes do Google.

Na versão com trilha sonora, os arquivos `Andar 2.mp3`, `Andar 5.mp3`, `Musica Chefes.mp3` e `Musica Menu.mp3` devem permanecer no mesmo diretório do HTML. O pacote `outputs/BreakNeon_Rogue_Com_Musicas_v3.zip` reúne o jogo e essas faixas.

A versão `outputs/BreakNeon_Rogue_Sem_Trilha.html` dispensa os arquivos de música e mantém os efeitos sonoros produzidos pelo próprio jogo. Também existe uma versão Android em `outputs/BreakNeon_Rogue.apk`.

## Tecnologias

O jogo utiliza HTML, CSS e JavaScript, com Canvas para renderização, Tailwind CSS para a interface e Lucide Icons para os ícones. A versão Android utiliza um WebView que empacota o jogo e seus recursos em um APK.

## Processo de desenvolvimento

O desenvolvimento ocorreu de maneira iterativa por meio de instruções em linguagem natural. Bernardo Pitarelli orientou o projeto, propôs as funcionalidades e avaliou os resultados. O agente Codex do ChatGPT realizou a implementação do código, as alterações solicitadas, as verificações de sintaxe, a preparação dos arquivos de publicação, a criação do ícone e a geração do APK.

Esse processo demonstra como uma pessoa pode orientar uma inteligência artificial para transformar uma ideia em um projeto funcional, revisar o resultado e aperfeiçoá-lo gradualmente. Por isso, o BreakNeon Rogue também serve como demonstração prática de criatividade, programação assistida por IA e vibe coding.

## Licença

Nenhuma licença foi definida até o momento. Antes de reutilizar, modificar ou redistribuir o projeto e suas faixas de áudio, confirme as permissões aplicáveis a cada arquivo.
