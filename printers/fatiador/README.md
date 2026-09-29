# Perfis do fatiador

Perfis prontos para importar no fatiador. Eles são independentes do
`printer.cfg`, mas trabalham em conjunto com ele.

## Fatiador usado

- Nome e versão: OrcaSlicer 4.2.4

## Como importar

1. Baixe os arquivos da pasta do fatiador.
2. No fatiador, importe primeiro o perfil da **impressora**,
   depois os de **filamento** e **qualidade**.
3. Selecione o conjunto correto na tela principal antes de fatiar.

## Perfis disponíveis

### Impressora

| Arquivo | Modelo | Observações |
|---|---|---|
| ender-3-v2.json | Ender 3 V2 | |
| ender-3-v2-neo.json | Ender 3 V2 Neo | |
| ender-7.json | Ender 7 | |
| ender-5.json | Ender 5 | |

### Filamento

| Arquivo | Material | Marca testada | Hotend | Temperatura bico / mesa |
|---|---|---|---|---|
| pla.json | PLA | (preencher) | V6 / Volcano | (preencher) |
| petg.json | PETG | (preencher) | V6 / Volcano | (preencher) |

### Qualidade

| Arquivo | Altura de camada | Uso recomendado |
|---|---|---|
| 0.12mm-fino.json | 0,12 mm | Detalhes finos |
| 0.20mm-padrao.json | 0,20 mm | Uso geral |
| 0.28mm-rapido.json | 0,28 mm | Protótipos rápidos |

## Ligação com o printer.cfg

- O G-code inicial dos perfis de impressora chama: (preencher, ex.: START_PRINT)
- Se mudar a macro no `printer.cfg`, atualize o perfil da impressora também.
