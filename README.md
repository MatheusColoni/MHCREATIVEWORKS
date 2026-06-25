# 🎬 MH Creative Works

Site profissional de portfólio para **MH Creative Works** - Produtora de conteúdo audiovisual especializada em fotografia, filmagem e edição em Santa Catarina.

![Status](https://img.shields.io/badge/status-ativo-brightgreen)
![License](https://img.shields.io/badge/license-MIT-blue)
![Version](https://img.shields.io/badge/version-1.0.0-blue)

---

## 🎯 Sobre o Projeto

MH Creative Works é um site moderno e responsivo que showcaseia os trabalhos audiovisuais de uma produtora profissional. O site inclui:

- 📸 **Portfólio**: Galeria de projetos com filtros
- 🎬 **Serviços**: Apresentação dos serviços oferecidos
- 📋 **Sobre**: Seção institucional com informações da empresa
- 💬 **Contato**: Formulário de contato sincronizado
- 🔧 **Admin Panel**: Painel administrativo integrado

---

## ✨ Características Principais

### Design
- ✅ Design moderno e minimalista
- ✅ Paleta de cores: Preto + Roxo
- ✅ Tipografia elegante (Bebas Neue + Inter)
- ✅ Animações suaves e fluidas

### Responsividade
- ✅ Mobile-first design
- ✅ 100% responsivo (360px - 1920px+)
- ✅ Testado em iOS e Android
- ✅ Otimizado para performance mobile

### Funcionalidades
- ✅ Portfólio com lightbox modal
- ✅ Filtros por categoria
- ✅ Admin panel integrado
- ✅ Upload de imagens
- ✅ Formulário de contato
- ✅ Integração WhatsApp e Instagram
- ✅ Painel de mensagens
- ✅ Editor de hero section
- ✅ Editor de seção "Sobre Nós"

### Segurança
- ✅ Validação de inputs
- ✅ Proteção XSS
- ✅ Validação de arquivos
- ✅ Rate limiting implementado
- ✅ Logging de eventos

### Performance
- ✅ Sem dependências externas (exceto fontes)
- ✅ HTML puro + CSS + JavaScript
- ✅ Carregamento rápido
- ✅ Sem bloat de frameworks

---

## 🛠️ Tecnologias

- **HTML5** - Estrutura semântica
- **CSS3** - Estilização moderna com Grid e Flexbox
- **JavaScript Vanilla** - Sem bibliotecas externas
- **Google Fonts** - Bebas Neue, Inter, Playfair Display
- **SessionStorage/LocalStorage** - Armazenamento de dados

---

## 📦 Estrutura do Projeto

```
mhcreativeworks/
│
├── 📄 index.html          ← Site completo (arquivo único)
│
├── 📄 README.md           ← Este arquivo
├── 📄 .gitignore          ← Configuração Git
│
└── 📁 docs/               ← Documentação
    ├── AUDITORIA_SEGURANCA.md
    ├── DESIGN_FINAL.md
    ├── EDITOR_SOBRE_NOS.md
    ├── FUNCOES_SEGURANCA.js
    ├── GUIA_CONTATOS.md
    ├── GUIA_PROJETOS.md
    ├── GUIA_RAPIDO.md
    ├── GUIA_RESPONSIVIDADE.md
    ├── IMPLEMENTACAO_SEGURANCA.md
    ├── README_ADMIN.md
    └── GUIA_DEPLOY_GITHUB_VERCEL.md
```

---

## 🚀 Como Usar

### Localmente

```bash
# Clone o repositório
git clone https://github.com/seu-usuario/mhcreativeworks.git

# Abra o arquivo
cd mhcreativeworks
# Duplo clique em: index.html
# Ou abra em um servidor local
```

### Deploy no Vercel

1. Faça push para GitHub
2. Acesse https://vercel.com
3. Clique "New Project"
4. Selecione seu repositório
5. Clique "Deploy"
6. Seu site estará em: `https://mhcreativeworks.vercel.app`

---


`

### Funcionalidades do Admin

1. **📷 Configurar Portfólio**
   - Upload de 6 imagens principais
   - Preview em tempo real

2. **➕ Novo Projeto**
   - Criar projetos com múltiplas imagens
   - Dados salvos em sessionStorage
   - Filtros por categoria

3. **💬 Mensagens**
   - Visualizar contatos recebidos
   - Informações completas
   - Delete de mensagens

4. **🎬 Mídia Hero**
   - Editar imagem do hero
   - Validação de arquivo
   - Preview antes de aplicar

5. **🖼️ Sobre Nós**
   - Editar imagem da seção sobre
   - Upload simples e rápido

---

## 📱 Responsividade

O site é 100% responsivo em:

| Dispositivo | Suporte |
|-------------|---------|
| Desktop (1920px+) | ✅ Completo |
| Tablet (768px) | ✅ Otimizado |
| Mobile (480px) | ✅ Compacto |
| Pequeno (360px) | ✅ Ultra compacto |
| Landscape | ✅ Horizontal |

---

## 🔒 Segurança

A segurança foi auditada com foco em:

- **XSS Prevention** - Sanitização de inputs
- **Input Validation** - Validação de dados
- **File Upload** - Validação de tipos e tamanho
- **Rate Limiting** - Proteção contra brute force
- **Logging** - Rastreamento de eventos

*Veja `docs/AUDITORIA_SEGURANCA.md` para detalhes completos.*

---

## 📊 Performance

- **Carregamento**: < 2 segundos
- **Performance Score**: 95+
- **Responsividade**: 60 FPS
- **Sem CLS**: Layout shifts zero

---

## 📝 Documentação

Documentação completa disponível em `docs/`:

- `README_ADMIN.md` - Como usar o painel admin
- `GUIA_RESPONSIVIDADE.md` - Detalhes de mobile
- `AUDITORIA_SEGURANCA.md` - Análise de segurança
- `DESIGN_FINAL.md` - Especificações de design
- `GUIA_DEPLOY_GITHUB_VERCEL.md` - Deploy passo-a-passo

---



**Versão**: 1.0.0  
**Última atualização**: 25/06/2026  
**Status**: ✅ Pronto para Produção
