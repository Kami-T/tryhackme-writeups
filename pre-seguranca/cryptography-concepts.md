# Cryptography Concepts

- **Trilha:** Pré Segurança
- **Data:** 04/07/2026

## O que aprendi
- Criptografia simétrica: mesma chave cifra e decifra (rápida, mas tem o
  problema de distribuir a chave com segurança).
- Criptografia assimétrica: par de chaves — pública (compartilhável) e
  privada (secreta). Resolve o problema de distribuição de chaves (key
  distribution).
- HTTPS usa abordagem híbrida: assimétrica inicia e combina uma chave,
  simétrica lida com os dados em massa por ser mais rápida.
- Certificados e Autoridades Certificadoras (CA) garantem que a chave
  pública realmente pertence ao site.

## Conexão com segurança
Liga com a Integridade da CIA Triad (hashing) e com os cookies Secure /
HTTPS da sala de HTTP. No SOC, hashes identificam malware conhecido.
