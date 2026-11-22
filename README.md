# PunchComp — Arcade Edition

Jogo de palavras cruzadas e luta inspirado nos fliperamas, desenvolvido em HTML, CSS e JavaScript puros para a atividade de Arquitetura Computacional.

## Como jogar

1. Abra `index.html` no navegador.
2. Clique em uma pista horizontal ou vertical, ou em uma casa da cruzadinha.
3. Digite diretamente no tabuleiro. Use as setas para navegar e Backspace para apagar.
4. Clique em **CONFERIR & ATACAR** (ou pressione Enter) para verificar as palavras. Cada nova palavra correta acerta um golpe no adversário.
5. Acerte as 16 palavras para nocautear o BUG BOSS.
6. Use **REINICIAR** para jogar novamente.

## Palavras e pistas

| Palavra | Pista |
|---|---|
| DMA | Recurso que transfere dados entre periféricos e memória sem intervenção contínua do processador. |
| UC | Parte do processador que coordena a execução das instruções. |
| FLASH | Tecnologia não volátil muito usada em pendrives e unidades de estado sólido. |
| ADDRESSBUS | Conjunto de vias que indica qual posição de memória será acessada. |
| MICROCONTROLADOR | Circuito integrado que reúne processamento, memória e periféricos para sistemas embarcados. |
| QUADCORE | Processador que possui quatro núcleos de execução. |
| REGISTRADORES | Pequenos espaços internos do processador usados para guardar valores temporários. |
| EEPROM | Memória não volátil que pode ser apagada e regravada eletricamente. |
| ULA | Parte do processador responsável por cálculos e comparações lógicas. |
| CPU | Componente principal que executa instruções e coordena o processamento do computador. |
| DATABUS | Conjunto de vias por onde circulam valores entre os componentes do sistema. |
| CACHE | Memória muito rápida que reduz o tempo de acesso a dados frequentes. |
| RAM | Memória volátil usada pelos programas durante a execução. |
| MEMORIADEMASSA | Armazenamento persistente de grandes volumes de arquivos e programas. |
| ROM | Memória não volátil que armazena instruções essenciais de inicialização. |
| DUALCORE | Processador que possui dois núcleos de execução. |

## Publicação

Envie estes arquivos à raiz de um repositório público e habilite GitHub Pages em Settings → Pages → Deploy from a branch → main → /(root). Atualize este README com o endereço publicado.

O projeto não utiliza frameworks, bibliotecas JavaScript ou backend. A fonte do Google Fonts é opcional; o jogo também funciona offline com fontes alternativas.


## Atualização v3
- Layout desktop sem rolagem da página: arena e cruzadinha lado a lado.
- Cinco respostas incorretas completas causam Game Over; respostas incompletas não gastam tentativas.
- Socos animados dos dois lutadores; acerto ataca o chefe, erro gera contra-ataque.
- Conferência da palavra selecionada, para evitar penalizar outras palavras ainda em preenchimento.
