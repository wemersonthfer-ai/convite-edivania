[README.md](https://github.com/user-attachments/files/33399421/README.md)
# Surpresa de aniversário — Edvania Braun

Página estática responsiva com mensagem de aniversário e convite para jantar. Os botões abrem a conversa do WhatsApp com W. Thiago, com uma mensagem pronta conforme a opção escolhida.

## Como funciona
- Botão **Sim, aceito**: abre `wa.me` com a mensagem de confirmação preenchida.
- Botão **Não, obrigada**: abre a mesma conversa com uma mensagem educada de recusa.
- Em ambos os casos, Edvania precisa tocar em **Enviar** no WhatsApp. A página não envia mensagens por conta própria nem registra a escolha se ela não enviar a mensagem.

O número de destino configurado no HTML é `5527996008908`. Se precisar trocar, edite `whatsappNumber` no final de `index.html`, mantendo o formato internacional apenas com dígitos.

## Hospedagem recomendada
Como esta versão não precisa de backend nem de banco de dados, uma hospedagem estática é suficiente. A Vercel é uma boa opção — especialmente se você já tem conta — mas Netlify ou GitHub Pages também servem. Não é necessário configurar a API do WhatsApp Business nesta versão.

## Publicar na Vercel
1. Descompacte o ZIP.
2. Crie um repositório no GitHub e envie o `index.html`.
3. Entre na Vercel, escolha **Add New → Project** e importe o repositório.
4. Faça o deploy; nenhuma variável de ambiente é necessária.
5. Abra a URL publicada no celular e teste os dois botões.

## Gerar o QR Code
Depois de publicar:
1. Copie a URL pública da página na Vercel.
2. Gere um QR Code apontando para essa URL usando um gerador de QR confiável.
3. Leia o código com outro celular e teste se a página abre e se cada botão abre o WhatsApp com a mensagem correta.
4. Só então imprima no cartão.

## Convite
Mahai — Praia da Costa, 17 de janeiro de 2027, às 20h. Confirme com o restaurante a disponibilidade e o horário antes do encontro.
