# What is Networking?

- **Trilha:** Pré Segurança — Módulo de Redes
- **Data:** 01/07/2026

## O que aprendi
Fundamentos de rede: o que é uma rede, identificação de dispositivos por
IP e MAC, e o comando ping (ICMP) para testar conectividade. Fiz um lab
de MAC spoofing e usei ping/leitura de output (ttl, time, packet loss).

## Conexão com segurança
- Filtragem por MAC é segurança fraca — MAC é facilmente falsificável.
- IP é a "identidade" que investigo em logs e threat intel.
- ICMP pode ser usado por atacantes para reconhecimento e até
  exfiltração (ICMP tunneling); o TTL ajuda a inferir o SO do alvo.
