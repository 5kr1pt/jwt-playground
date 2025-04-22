# JWT Playground

---

## ⚠️ Aviso de Segurança

Esta aplicação web permite **criar, modificar e inspecionar JWTs manualmente**, inclusive com opções que **burlam as validações padrão de segurança**, como:
- Gerar tokens com algoritmo `"none"` (sem assinatura)
- Modificar manualmente os tempos (`iat`, `nbf`, `exp`)
- Editar qualquer claim livremente, sem verificação de integridade

**IMPORTANTE:**  
Esta ferramenta foi criada **exclusivamente para fins educacionais**, como:
- Testes em laboratório (labs, CTFs)
- Estudo de vulnerabilidades comuns em autenticação via JWT
- Demonstrações de segurança ofensiva

**NÃO UTILIZE** este playground em sistemas reais, ambientes de produção ou com tokens de terceiros.  
O uso indevido pode comprometer seriamente a **autenticidade, integridade e segurança de aplicações** baseadas em JWT.

---

<p><strong>Licença:</strong> Este projeto é licenciado sob CC BY-NC-SA 4.0. Uso comercial proibido. Para fins educacionais apenas.</p>

---


Uma aplicação simples para **encode**, **decode** e **edição** de tokens JWT diretamente no navegador

Site: https://5kr1pt.github.io/jwt-playground/

---

## 🚀 Features

- **Decode**: cola qualquer JWT e veja header, payload e assinatura em texto.
- **Encode / Sign**: edita header/payload em JSON ou Base64URL puro e gera token (HS256 / none).
- **Clone JSON / Clone Raw**: transfere os dados do painel de decode para encode em um clique.
- **Batch set**: ajuste claims via comandos rápidos (ex: `sub=1 role=admin`).
- **Refresh times**: renova automaticamente `iat`, `nbf` e `exp` com lifetime configurável.
- **Modos JSON & Raw**: escolha trabalhar com JSON legível ou Base64URL "raw".

---
## 📽️ How to use

[![Demonstração do JWT Wizard](https://img.youtube.com/vi/TwRoaJMwru0/hqdefault.jpg)](https://youtu.be/TwRoaJMwru0)

---

## 🤝 Contribuições

Contribuições são sempre bem-vindas! Sinta-se livre para abrir issues ou enviar pull requests.

---

## 📄 Licença

Este projeto está licenciado sob a Licença [Creative Commons BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/).  
Uso comercial é expressamente proibido.

