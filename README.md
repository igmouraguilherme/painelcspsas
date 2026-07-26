# Painel de Carteira CSP — Time Igor

Dashboard de análise de carteira para o time de Consultores de Sucesso Pedagógico (CSP) da SAS Educação.

## 🔒 Confidencial
Este painel é de uso interno exclusivo. Não compartilhar externamente.

## Como hospedar no GitHub Pages

### 1. Criar o repositório
```bash
# Clone ou crie um repositório novo
git init dashboard-csp
cd dashboard-csp
```

### 2. Copiar os arquivos
Coloque o arquivo `index.html` na raiz do repositório.

### 3. Fazer deploy
```bash
git add .
git commit -m "Deploy dashboard CSP"
git branch -M main
git remote add origin https://github.com/SEU_USUARIO/dashboard-csp.git
git push -u origin main
```

### 4. Ativar GitHub Pages
1. Vá em **Settings** → **Pages**
2. Em **Source**, selecione **Deploy from a branch**
3. Selecione a branch **main** e pasta **/ (root)**
4. Clique **Save**
5. Em ~1 minuto, o dash estará disponível em `https://SEU_USUARIO.github.io/dashboard-csp/`

## Atualização de dados
Os dados estão embeddados no HTML. Para atualizar:
1. Re-extrair dados da planilha
2. Gerar novo `index.html`
3. Commit + push
