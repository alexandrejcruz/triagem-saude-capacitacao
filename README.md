# 📚 Sistema de Capacitação em Triagem de Saúde - Defensoria Pública

## Publicar no GitHub Pages (Link Privado)

### ✅ Pré-requisitos
- Conta GitHub (https://github.com)
- Git instalado no computador
- Arquivos HTML prontos (já preparados)

---

## 🚀 Passo-a-Passo para Publicar

### PASSO 1: Criar Repositório Privado no GitHub

1. Acesse **github.com** e faça login
2. Clique no **+ (canto superior direito) → New repository**
3. Preencha assim:
   - **Repository name**: `triagem-saude-capacitacao`
   - **Description**: "Sistema de Capacitação em Triagem de Saúde - Defensoria Pública"
   - **Private**: ✅ MARCAR (importante para link privado)
   - **Add a README file**: ☐ Deixar desmarcado
4. Clique **Create repository**

---

### PASSO 2: Configurar GitHub Pages

1. No repositório criado, vá em **Settings**
2. Lado esquerdo, clique em **Pages**
3. Em "Source", selecione **Deploy from a branch**
4. Escolha **main** (branch) e **/root** (pasta)
5. Clique **Save**
6. Aguarde 1-2 minutos (aparecerá: "Your site is live at...")

---

### PASSO 3: Upload dos Arquivos

#### Opção A: Via GitHub Web (Mais Fácil)

1. No repositório, clique **Add file → Upload files**
2. Arraste e solte (ou selecione) estes 4 arquivos:
   - `index.html`
   - `styles.css`
   - `script.js`
   - `README.md` (este arquivo)
3. Clique **Commit changes**
4. Aguarde 2-3 minutos

#### Opção B: Via Terminal/Git (Mais Rápido)

```bash
# 1. Clonar repositório
git clone https://github.com/SEU-USERNAME/triagem-saude-capacitacao.git
cd triagem-saude-capacitacao

# 2. Copiar os arquivos HTML/CSS/JS para a pasta

# 3. Fazer commit
git add .
git commit -m "Deploy: Sistema de Capacitação em Triagem de Saúde"
git push origin main

# Pronto! Site estará disponível em:
# https://github.com/pages/username/triagem-saude-capacitacao
```

---

### PASSO 4: Acessar o Site

Sua URL pública será algo assim:
```
https://SEU-USERNAME.github.io/triagem-saude-capacitacao/
```

**Compartilhe esse link com sua equipe!** ✅

---

## 🔐 Segurança - Link Privado

Como o repositório é **PRIVADO**, apenas quem tiver acesso ao GitHub conseguirá ver o código.

### Para Compartilhar com a Equipe

**Opção 1: Adicionar Colaboradores**
- Settings → Collaborators → Adicione email dos colegas
- Cada pessoa precisa criar conta GitHub (grátis)

**Opção 2: Compartilhar URL (Recomendado para esta fase)**
- Copie a URL do site: `https://seu-username.github.io/triagem-saude-capacitacao/`
- Compartilhe via email/WhatsApp
- Qualquer pessoa com a URL consegue acessar (sem login GitHub necessário)
- ⚠️ Nota: URL é "difícil de adivinhar" mas não 100% segura

**Opção 3: Usar Proteção por Senha (Avançado)**
- Implementar autenticação básica via GitHub Pages + ações
- (Pode ser adicionado depois se necessário)

---

## 📱 Funcionalidades do Site

✅ **Totalmente Responsivo**
- Desktop, tablet, mobile
- Navegação suave
- Design profissional

✅ **Documentos Integrados**
- 3 documentos acessíveis via botões
- Visualização em modal (sem sair do site)
- Impressão/download fácil

✅ **Seções**
- Introdução e pilares
- 8 módulos de capacitação
- Cronograma de implementação
- Estatísticas de impacto
- Contato e informações

---

## 🛠 Como Usar Depois de Publicado

### Para Acessar no Navegador
1. Abra a URL em qualquer browser
2. Clique em "Acessar Material"
3. Visualize os 3 documentos
4. Compartilhe o link com colegas

### Para Fazer Atualizações
1. Edite os arquivos locally
2. Faça commit e push
3. GitHub Pages atualiza automaticamente (2-3 min)

---

## 📞 Suporte Rápido

**Problema**: Site não está acessível
- Aguarde 5 minutos após upload
- Verifique se o repositório é **PRIVADO** ✓
- Verifique se Pages está ativado em Settings

**Problema**: Documentos não carregam
- Verifique console (F12 → Console)
- Certifique-se que `script.js` foi uploaded

**Problema**: Layout quebrado
- Limpe cache do navegador (Ctrl+Shift+Delete)
- Verifique se `styles.css` foi uploaded

---

## 📋 Checklist Final

- [x] Repositório criado e PRIVADO
- [x] Arquivos: index.html, styles.css, script.js
- [x] GitHub Pages ativado (Settings → Pages)
- [x] Build concluído (aguardou 2-3 min)
- [x] URL funcionando
- [x] Documentos carregando
- [x] Link compartilhado com equipe

---

## 🎓 Próximas Funcionalidades (Opcional)

Se quiser expandir depois:
- ✨ Adicionar quiz/avaliações
- 📧 Formulário de contato
- 📊 Painel de progresso
- 📱 App mobile
- 🔐 Autenticação com GitHub

---

## 📄 Arquivos Inclusos

```
triagem-saude-capacitacao/
├── index.html          (página principal)
├── styles.css          (estilos/design)
├── script.js           (funcionalidades)
├── README.md           (este arquivo)
└── SISTEMA_CAPACITACAO_TRIAGEM_SAUDE.md (documentos originais em markdown)
    GUIA_PRATICO_ATENDIMENTO.md
    MATRIZ_COMPETENCIAS_AVALIACAO.md
```

---

## ✅ Sistema Pronto!

Seu portal online de capacitação está pronto para uso. Compartilhe a URL com sua equipe e comece a capacitação em qualquer dispositivo, em qualquer hora!

**Sucesso na implementação! 🎯**

---

*Desenvolvido para Defensoria Pública - Especialidade Saúde*
*Sistema de Capacitação em Triagem com Acolhimento Humanizado*
