# Vezzo Totens - Landing Page

Landing page estática pronta para deploy no Vercel, com carrossel e redirecionamento para WhatsApp.

## Como usar

1. Clone ou crie um repositório no GitHub com estes arquivos:
   - `index.html`
   - `vercel.json`
   - `README.md`

2. Faça commit e envie para o GitHub:
   ```
   git init
   git add .
   git commit -m "Landing page Vezzo Totens"
   git branch -M main
   git remote add origin https://github.com/<seu-usuario>/<seu-repo>.git
   git push -u origin main
   ```

3. Conecte no Vercel:
   - Vá para https://vercel.com/
   - Clique em "New Project"
   - Importe o repositório que você criou no GitHub
   - Use as configurações padrão (é estático)
   - Deploy será feito automaticamente

4. Personalize:
   - Substitua as imagens do carrossel por fotos reais.
   - Ajuste e-mail, texto e referências no rodapé conforme necessário.

## O que acontece ao enviar o formulário

O formulário monta uma mensagem com os dados preenchidos e abre o WhatsApp para o número +55 51 99758-8099 com o texto pronto para você responder.

## Sem backend

Essa versão não salva leads no servidor. Se quiser evoluir para guardar os contatos, posso te ajudar a:
- Adicionar Google Sheets via Apps Script
- Criar uma API simples em Node.js (hosteada no próprio Vercel)