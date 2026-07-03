<h1>Portfolio</h1>

## Sobre o projeto

Site pessoal em formato *single page*, com navegação por âncoras entre as seções. Foi pensado para ser simples de manter (sem build, sem dependências, sem framework) e fácil de estender conforme novos projetos e experiências forem surgindo.

### Seções

- **Hero** — apresentação, foto e chamadas para ação
- **Sobre** — bio e informações rápidas (localização, formação, foco atual, idiomas)
- **Experiência** — linha do tempo com as atuações no IFPB
- **Projetos** — cards com descrição, tecnologias e link do repositório
- **Skills** — stack organizada por categoria (Mobile, Web & Backend, Banco de dados, Arquitetura, Ferramentas)
- **Contato** — Email, LinkedIn e GitHub

### Funcionalidades

- **Bilíngue (PT/EN)** — botão de toggle no estilo terminal (`$ lang=pt`) que traduz o conteúdo da página via JavaScript, sem recarregar. O idioma escolhido fica salvo no `localStorage`.
- **Responsivo** — layout adaptado para desktop, tablet e mobile, com menu hambúrguer nas telas menores.
- **Acessibilidade** — foco visível no teclado e respeito à preferência `prefers-reduced-motion`.
- **Design system próprio** — paleta, tipografia (Fraunces + Inter + IBM Plex Mono) e componentes consistentes em todo o site.

## Tecnologias

- HTML5 semântico
- CSS3 (custom properties, grid, flexbox)
- JavaScript puro (sem frameworks ou bibliotecas)
- Google Fonts

## Estrutura do repositório

```
Portfolio-Web/
├── index.html            # Estrutura e conteúdo (PT/EN via data-i18n)
├── styles.css            # Design system e estilos
├── script.js             # Toggle de idioma, menu mobile, ano do rodapé
├── assets/
│   └── davi.png          # Foto de perfil
│   └── logo.svg          # Favicon
└── README.md
```

## Como rodar localmente

Por ser um site 100% estático, basta abrir o `index.html` no navegador — ou, para evitar problemas com caminhos relativos, servir a pasta com um servidor simples:

```bash
# Python
python3 -m http.server 8080

# ou VS Code: extensão "Live Server"
```

Depois acesse `http://localhost:8080`.

## Deploy

O site é publicado via **GitHub Pages** a partir da branch `main`, na raiz do repositório.

## Contato

<p>
  <a href="mailto:davimelonsmt@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white"></a>
  <a href="https://www.linkedin.com/in/davimelodev/" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a>
  <a href="https://daviimelo.github.io/Portfolio-Web/" target="_blank"><img src="https://img.shields.io/badge/Portfólio-%23252525.svg?style=for-the-badge&logo=github&logoColor=white" alt="Portfólio"></a>
</p>
