# Instalação do printer.cfg

Este manual vale para todas as impressoras do kit Klipper + Orbiter.

## Antes de começar

- Klipper já instalado no Raspberry Pi
- Placa SKR Mini E3 V3.0 com o firmware do Klipper gravado
- Acesso à interface web (Mainsail)

## Passo a passo

1. Abra a interface web da impressora (com o IP dela).
2. No painel esquerdo procure por (Machine ou Maquina).
3. Substitua o conteúdo do `printer.cfg` pelo arquivo da sua máquina,
   em `printer/config/`. (nao exclua o printer.cfg, no lugar, acesse-o e substitua o conteudo com ctrl+A + ctrl+V).
4. Clique em salvar e reiniciar (Save & Restart).
5. Confira se a impressora conecta sem erros.

## O que ajustar depois de instalar

- (preencher: calibração do Z offset, PID, esteps do extrusor...)

## Problemas comuns

- (preencher conforme aparecerem)