# 🌐 WebCoding — Faculdade

Projeto desenvolvido nas aulas de **Programação Web** da faculdade para praticar os fundamentos do desenvolvimento Front-End com **HTML5**, **CSS3**, **JavaScript** e **Bootstrap**.

A página apresenta as quatro tecnologias em seções alternadas (imagem + texto), com um menu de navegação fixo e responsivo que leva o usuário direto para cada uma delas.

---

## 📋 Sobre o Projeto

Este repositório tem dois objetivos principais:

- 📚 **Aprender na prática** como HTML, CSS, JavaScript e Bootstrap trabalham juntos na construção de uma página web
- 🛠️ **Praticar Git e GitHub**, versionando a evolução do projeto com commits reais

> 📌 O projeto está em construção e vai crescendo conforme as aulas avançam.

---

## 🛠️ Tecnologias Utilizadas

| Tecnologia | Função no projeto |
|---|---|
| **HTML5** | Estrutura da página: menu, seções e conteúdo |
| **CSS3** | Ajustes visuais que complementam o Bootstrap (tamanho das imagens, espaçamentos, rolagem suave até as seções) |
| **JavaScript** | Arquivo já criado para receber a interatividade nas próximas aulas |
| **Bootstrap 5.0.2** | Grid responsivo, navbar com menu hambúrguer, botões e utilitários de layout (via CDN) |

---

## ✨ Funcionalidades

- Menu de navegação **fixo no topo** (`fixed-top`)
- Menu **responsivo**: vira um botão hambúrguer em telas pequenas
- Links âncora (`#html`, `#css`, `#javascript`) que levam direto a cada seção
- Seções com **layout alternado** (imagem à esquerda / à direita) usando `flex-row-reverse`
- Compensação da navbar fixa com `scroll-margin`, para o título não ficar escondido atrás do menu
- Imagens responsivas com `img-fluid`
- Layout adaptado para computador, tablet e celular

---

## 📁 Estrutura do Projeto

```
WebCoding_Facudade/
│
├── index.html            # Página principal
├── README.md             # Documentação do projeto
│
└── Projeto/
    ├── css/
    │   └── style.css     # Estilos personalizados
    ├── js/
    │   └── script.js     # Interatividade (em desenvolvimento)
    └── img/
        ├── Html.jpg
        ├── Css.jpg
        ├── JavaScript.jpg
        └── Bootstrap.jpg
```

### Descrição dos arquivos

- **`index.html`** — Estrutura do site: navbar, as quatro seções sobre cada tecnologia e a importação do Bootstrap pelo CDN.
- **`Projeto/css/style.css`** — Estilos que complementam o Bootstrap, como a largura das imagens, o espaço no topo para a navbar fixa e o `scroll-margin` das seções.
- **`Projeto/js/script.js`** — Reservado para a parte de JavaScript que será adicionada nas próximas aulas.
- **`Projeto/img/`** — Imagens ilustrativas de cada tecnologia.

---

## 🚀 Como Executar o Projeto

### 1. Requisitos

- [Visual Studio Code](https://code.visualstudio.com/) ou outro editor de código
- Navegador atualizado
- Conexão com a internet (para carregar o Bootstrap pelo CDN)

### 2. Clonar o repositório

```bash
git clone https://github.com/PedroVini09/WebCoding_Facudade.git
cd WebCoding_Facudade
```

### 3. Executar o site

1. Abra a pasta do projeto no VS Code
2. Instale a extensão **Live Server**
3. Clique com o botão direito em `index.html`
4. Selecione **Open with Live Server**
5. O site abrirá automaticamente no navegador

> 💡 Recomendo usar o Live Server: como os caminhos do CSS e das imagens começam com `/`, abrir o `index.html` direto com duplo clique pode fazer a página carregar sem estilo e sem imagens.

---

## 🎯 Objetivos de Aprendizagem

Com este projeto, pratiquei:

- A estrutura básica de uma página HTML5
- Navegação interna com links âncora (`href="#id"`)
- O sistema de **grid** do Bootstrap (`row`, `col-md-6`)
- Componentes do Bootstrap como **navbar**, **collapse** e **botões**
- Classes utilitárias (`my-5`, `text-center`, `align-items-center`, `bg-primary`)
- Como sobrescrever e complementar o Bootstrap com CSS próprio
- Organização do projeto em pastas separadas (CSS, JS e imagens)
- Versionamento com Git e GitHub

---

## 🔮 Próximos Passos

- [ ] Substituir os textos *Lorem ipsum* por explicações reais sobre cada tecnologia
- [ ] Corrigir o link **Bootstrap** do menu para `#bootstrap`
- [ ] Trocar o texto "Logo" da navbar pelo nome/logo do projeto
- [ ] Ligar o `script.js` ao `index.html` e adicionar interatividade aos botões
- [ ] Criar um **quiz** sobre HTML, CSS, JavaScript e Bootstrap
- [ ] Adicionar exemplos de código em cada seção
- [ ] Criar um rodapé com contato e links
- [ ] Publicar o site no **GitHub Pages**

---

## 📝 Licença

Este repositório é de uso **educacional e pessoal**.
O projeto foi desenvolvido por mim durante as aulas de Programação Web.

---

## 👨‍💻 Autor

**Pedro Vinícius**
Estudante de Ciência da Computação

[![GitHub](https://img.shields.io/badge/GitHub-PedroVini09-181717?style=flat&logo=github)](https://github.com/PedroVini09)

### 📧 Contato

Encontrou algum erro ou quer trocar ideia sobre o projeto?
Abre uma **issue** aqui no repositório!