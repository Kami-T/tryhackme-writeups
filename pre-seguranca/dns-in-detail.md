# DNS in Detail

- **Trilha:** Pré Segurança — Módulo de Redes
- **Data:** 01/07/2026

## O que aprendi
Como o DNS traduz nomes de domínio em endereços IP e os principais
tipos de registro: A (IPv4), AAAA (IPv6), CNAME (apelido), MX (e-mail)
e TXT (texto). Fiz consultas DNS na prática com nslookup e um simulador
de "Send DNS Request".

## Conexão com segurança
- Registro A: rastrear para qual IP um domínio suspeito de phishing aponta.
- Registro MX e TXT (SPF/DKIM/DMARC): analisar se um e-mail foi falsificado.
- DNS tunneling é técnica de exfiltração; tráfego DNS anômalo é
  monitorado no SOC.

## Lição prática (nslookup)
Escrever o domínio completo uma vez só — duplicar (www.website.thm.
website.thm) causa NXDOMAIN.
