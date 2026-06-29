# Data Encoding

- **Trilha:** Pré Segurança — Módulo 4
- **Data:** 29/06/2026

## O que aprendi
Como caracteres são codificados em números/bits: ASCII (padrão antigo,
inglês básico), Unicode (universal, cobre todas as línguas e emojis) e
as formas de empacotar Unicode em bytes (UTF-8, UTF-16, UTF-32). Entendi
o que causa os caracteres bugados (leitura com encoding errado).

## Conceitos novos
ASCII, caracteres de controle (ex: BEL = 7), Unicode, UTF-8, encoding.

## Conexão com segurança
Confusão de encoding é usada para burlar filtros; homóglifos Unicode
aparecem em domínios falsos de phishing. Encoding errado em logs pode
ser pista em investigação.
