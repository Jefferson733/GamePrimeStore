# GamePrimeStore

Uma loja online de produtos para gamers com interface moderna e responsiva.

## Publicando no Netlify

Siga estas instruções para publicar seu site no Netlify:

### 1. Fazer download do código

No Replit:
- Clique nos três pontos (...) no menu lateral
- Selecione "Download as zip"
- Descompacte o arquivo em seu computador

### 2. Criar uma conta no Netlify

- Acesse [netlify.com](https://www.netlify.com/)
- Clique em "Sign up" e crie uma conta (pode usar GitHub, GitLab ou e-mail)
- Faça login na sua conta

### 3. Publicar o site pelo método "drag-and-drop"

- No dashboard do Netlify, clique em "Add new site" > "Deploy manually"
- Arraste a pasta do projeto descompactado para a área indicada
- Aguarde o upload e a publicação inicial

### 4. Configurar o site

- Após a publicação inicial, vá para "Site settings" 
- Em "Build & deploy" > "Build settings", configure:
  - Build command: `npm run build`
  - Publish directory: `dist`
- Salve as configurações

### 5. Fazer novo deploy

- Vá para a aba "Deploys"
- Clique em "Trigger deploy" > "Deploy site"
- Aguarde a conclusão do build e deploy

### 6. Configurar domínio personalizado (opcional)

- Em "Site settings" > "Domain management", você pode:
  - Usar o domínio gratuito fornecido pelo Netlify (nome-aleatorio.netlify.app)
  - Adicionar seu próprio domínio personalizado

### 7. Compartilhar seu site

- Na página principal do seu site no Netlify, copie a URL fornecida
- Use esta URL para compartilhar seu site no Instagram e outras redes sociais

## Funcionalidades implementadas

- Navegação responsiva com menu mobile
- Listagem de produtos por categoria
- Detalhes do produto
- Carrinho de compras
- Processo de checkout
- Confirmação de pedido
- Tema escuro por padrão
- Site totalmente em português para o mercado brasileiro

## Estrutura do projeto

- `/client` - Frontend React com Vite
- `/server` - Backend Express.js
- `/functions` - Funções serverless para o Netlify
- `/shared` - Tipos e esquemas compartilhados
- `/public` - Arquivos públicos estáticos

## Tecnologias utilizadas

- React
- TypeScript
- Tailwind CSS
- Express.js
- ShadCN UI
- Netlify Functions
