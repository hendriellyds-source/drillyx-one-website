<div align="center">

# Drillyx ONE — Website & Portfólio

**Infinitas soluções para o seu negócio.**

Landing page institucional e portfólio de sistemas, automações e experiências digitais.

[Ver projetos](#projetos-em-destaque) · [Como executar](#executar-localmente) · [Instagram](https://instagram.com/drillyxone)

</div>

## Sobre o projeto

Este repositório apresenta a identidade digital da **Drillyx ONE**, criada para exibir soluções de tecnologia para negócios. O site é desenvolvido com **HTML, CSS e JavaScript**, sem framework ou processo de compilação.

### Funcionalidades

- Layout responsivo para desktop e celular.
- Navegação por seções e menu mobile.
- Animações de entrada, barra de progresso e microinterações.
- Identidade visual com gradientes violeta, azul e turquesa.
- Portfólio com links de projetos e demonstrações públicas.

## Projetos em destaque

| Projeto | Descrição | Link |
| --- | --- | --- |
| **Elizabete Prado** | Landing page para arquitetura | [Abrir](https://elizabetepradoarquiteta.netlify.app/) |
| **Shopping Náutico** | Landing page comercial | [Abrir](https://aluguelshoppingnautico.netlify.app/) |
| **Sistema de Gestão Operacional** | Aplicação FastAPI com dados fictícios | [Demo online](https://gestao-operacional-demo-ypoh.onrender.com/login) · [Código](https://github.com/hendriellyds-source/sistema-gestao-operacional) |

## Executar localmente

Clone este repositório e execute, na pasta raiz:

```bash
python -m http.server 8000
```

Abra http://localhost:8000.

## Estrutura esperada

```text
.
├── index.html
├── style.css
├── script.js
├── assets/
│   ├── favicon.png
│   ├── favicon-64.png
│   ├── logo-horizontal.png
│   ├── infinito.png
│   ├── og-image.png
│   └── sistema-gestao-preview.webp
├── .gitignore
└── README.md
```

**Site publicado:** https://drillyxone.netlify.app/

O site é estático e pode ser publicado no Netlify ou GitHub Pages. Um push no GitHub só atualiza a hospedagem se o deploy automático estiver conectado ao repositório.

## SEO e compartilhamento

O `index.html` inclui descrição, URL canônica e metadados Open Graph/Twitter. A imagem de compartilhamento utiliza `assets/og-image.png` (1200 × 630), sem alterar o layout da landing page.

## Acessibilidade

O site inclui navegação por teclado com foco visível, atalho para o conteúdo principal, menu móvel com estado acessível e fechamento por `Escape`, botões do fluxo com `aria-pressed` e suporte a `prefers-reduced-motion`.

## Observações

- A imagem do Sistema de Gestão é uma captura real incluída no pacote final.
- As prévias de Elizabete Prado e Shopping Náutico usam serviço externo de screenshots, que pode ficar indisponível.
- Não há dados empresariais privados ou segredos de produção neste projeto.

---

**Hendrielly de Souza · Drillyx ONE**  
[Instagram](https://instagram.com/drillyxone) · [E-mail](mailto:drillyxone@gmail.com)
