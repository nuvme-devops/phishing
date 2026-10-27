# Nuvme Security Awareness

Portal estático de conscientização de segurança com duas trilhas:
- **Básico:** 10 cenários de phishing e hábitos de segurança.
- **Avançado:** 10 cenários de BEC, fraude de fornecedor, MFA, domínios parecidos e engenharia social.

## Publicar no GitHub Pages

1. Baixe e extraia o ZIP.
2. Copie o conteúdo desta pasta para a raiz do repositório `nuvme-devops/phishing`, preservando a estrutura:
   - `index.html`
   - `assets/styles.css`
   - `assets/app.js`
   - `README.md`
3. Faça commit e push para a branch `main`.
4. Em GitHub → **Settings → Pages**, selecione **Deploy from a branch**, branch `main`, pasta `/(root)`.
5. Aguarde a publicação na aba **Actions**.
6. Acesse `https://nuvme-devops.github.io/phishing/`.

## Recursos

- Página inicial profissional com escolha explícita de trilha Básico ou Avançado.
- 10 perguntas por trilha (20 cenários no total).
- Feedback educativo após cada resposta.
- Pontuação, resumo final e opção de copiar o resultado.
- Nome e departamento opcionais, apenas para personalizar o resumo.
- Responsivo para desktop e celular.

## Privacidade e limites desta versão

- Não há backend, banco de dados ou envio de e-mails.
- Respostas e pontuação existem apenas na memória da página enquanto o quiz está aberto.
- Nome e departamento não são enviados nem armazenados.
- Não há painel administrativo nem relatórios centralizados.
- Mensagens, nomes e domínios são exemplos fictícios de treinamento; remetentes exibidos não são verificados.
- Nunca use os links dos exemplos para acessar sistemas reais.
- Antes de compartilhar resultados, siga as políticas internas de privacidade e segurança.

## Próxima fase opcional

Para armazenamento central, pode-se adicionar API Gateway + Lambda + DynamoDB, com validação dos dados, proteção contra abuso, autenticação do painel e política de retenção. O frontend pode continuar hospedado no GitHub Pages.
