# HTTP in Detail

- **Trilha:** Pré Segurança — Módulo de Redes
- **Data:** 02/07/2026

## O que aprendi
Como o HTTP funciona: anatomia de uma URL (esquema, host, porta, caminho,
query string, fragmento), requisições e respostas, métodos (GET, POST...),
status codes, headers e cookies. Content-Type diz o tipo de dado;
Content-Length diz o tamanho. Set-Cookie salva cookies no navegador.

## Conexão com segurança
- Cookies guardam sessões — alvo de roubo via XSS (session hijacking).
  Flags HttpOnly e Secure protegem cookies sensíveis.
- Status codes em logs contam histórias: muitos 404 = varredura de
  diretórios; 401/403 = tentativas de acesso não autorizado.
- Manipular requisições HTTP (ex: via Burp Suite) é base de AppSec.
