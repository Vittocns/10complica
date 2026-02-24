# (10)COMPLICA - Página de Vendas

Página de vendas de alta conversão para o curso "(10)COMPLICA" do Dr. Marcelo Brito.
Projeto desenvolvido com HTML5, CSS3 (Tailwind CSS via Vite) e JavaScript Vanilla.

## Como rodar localmente

1. Certifique-se de ter o [Node.js](https://nodejs.org/) instalado.
2. Clone este repositório.
3. Instale as dependências:
   ```bash
   npm install
   ```
4. Inicie o servidor de desenvolvimento:
   ```bash
   npm run dev
   ```
5. Acesse `http://localhost:3000` no seu navegador.

## Como subir no GitHub

1. Crie um novo repositório no seu GitHub.
2. No terminal, na pasta do projeto, execute:
   ```bash
   git init
   git add .
   git commit -m "Initial commit: Landing Page (10)COMPLICA"
   git branch -M main
   git remote add origin https://github.com/SEU_USUARIO/SEU_REPOSITORIO.git
   git push -u origin main
   ```

## Como publicar no Netlify

### Opção 1: Deploy via GitHub (Recomendado)
1. Crie uma conta no [Netlify](https://www.netlify.com/).
2. Clique em **"Add new site"** > **"Import an existing project"**.
3. Escolha **GitHub** e autorize o acesso.
4. Selecione o repositório que você acabou de criar.
5. Configurações de build:
   - **Build command:** `npm run build`
   - **Publish directory:** `dist`
6. Clique em **"Deploy site"**. O Netlify atualizará o site automaticamente a cada novo commit no GitHub.

### Opção 2: Drag-and-drop (Manual)
1. No terminal, execute o comando de build para gerar os arquivos estáticos:
   ```bash
   npm run build
   ```
2. Uma pasta chamada `dist` será criada na raiz do projeto.
3. Acesse o painel do [Netlify](https://app.netlify.com/drop).
4. Arraste a pasta `dist` para a área indicada na tela.
5. O site estará no ar em poucos segundos!

## Personalização (Para o Desenvolvedor/Cliente)

Busque no arquivo `index.html` pelos comentários `<!-- SUBSTITUIR: ... -->` para inserir:
- Prints de prova social na seção "Provas".
- Foto do Dr. Marcelo Brito na seção "Sobre".
- Imagens ilustrativas do curso na seção "Hero".
