# Impressoras 3D: kit Klipper + Orbiter

## Manuais

- [Revitalização (PDF)](manual-revitalizacao.pdf): serve para todas as máquinas.
- [Instalação do printer.cfg](manual-instalacao-cfg.md): serve para todas as máquinas.

## Máquinas

| Etiqueta | Modelo | Arquivo de configuração | Observações |
|---|---|---|---|
| ender-3-v2-00 | Ender 3 V2 | [configs/ender-3-v2-00.cfg](configs/ender-3-v2-00.cfg) | |
| ender-3-v2-01 | Ender 3 V2 | [configs/ender-3-v2-01.cfg](configs/ender-3-v2-01.cfg) | |
| ender-3-v2-neo-00 | Ender 3 V2 Neo | [configs/ender-3-v2-neo-00.cfg](configs/ender-3-v2-neo-00.cfg) | |
| ender-3-v2-neo-01 | Ender 3 V2 Neo | [configs/ender-3-v2-neo-01.cfg](configs/ender-3-v2-neo-01.cfg) | |
| ender-7 | Ender 7 | [configs/ender-7.cfg](configs/ender-7.cfg) | |
| ender-5 | Ender 5 | [configs/ender-5.cfg](configs/ender-5.cfg) | |

## Regras para o printer.cfg

- Um arquivo por máquina, com o mesmo nome da etiqueta colada nela.
- Ao mudar algo, escreva no commit qual máquina e o motivo.
- Não coloque senhas nem dados de rede nos arquivos!

## O kit upgrade:

Todas as impressoras foram convertidas com o mesmo kit:

- Firmware: Klipper
- Extrusor: direct drive Orbiter
- Hotend: tipo V6 / Volcano
- Placa controladora: BIGTREETECH SKR Mini E3 V3.0
- Computador de bordo: Raspberry Pi executando o Klipper