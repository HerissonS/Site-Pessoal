# Portfólio Pessoal — Hérisson Silva

Site pessoal e portfólio profissional de **Antonio Herisson Silva Morais** (apresentação: **Hérisson Silva**), profissional de TI atuante em **Cloud | DevOps | Infraestrutura | Suporte**.

## Sobre o projeto

Este repositório contém um site estático que funciona como portfólio profissional de tecnologia. O site apresenta trajetória, experiência, competências, projetos, formação, certificações e formas de contato, servindo como porta de entrada para os projetos públicos no GitHub.

## Evolução do projeto

A história deste projeto segue a seguinte evolução:

```text
Bootcamp DIO + Carrefour
        ↓
Primeiro site pessoal
        ↓
Ideia inicial de site/blog
        ↓
Evolução profissional
        ↓
Modernização do projeto
        ↓
Portfólio profissional
```

**Este projeto iniciou tendo como foco a montagem de um site pessoal e foi iniciado no Bootcamp da DIO em parceria com Carrefour.**

Naquele momento, a intenção inicial era transformar o site em uma espécie de blog pessoal, com uma área de posts. Essa ideia foi abandonada, e o projeto foi modernizado e transformado em um portfólio profissional estático de tecnologia.

## Objetivo atual

O projeto atualmente tem como objetivo:

- funcionar como portfólio profissional;
- apresentar a trajetória profissional;
- apresentar competências e níveis de conhecimento;
- apresentar certificações e formações;
- apresentar projetos reais;
- centralizar links profissionais (LinkedIn, GitHub e e-mail);
- direcionar visitantes para os projetos no GitHub.

O site promove uma experiência focada em: **quem sou → experiência → impacto profissional → competências → projetos → formação/certificações → como entrar em contato.**

## Tecnologias utilizadas

- HTML5
- CSS3
- Bootstrap 5 (arquivos locais em `bootstrap/`)
- JavaScript simples (utilizado apenas para o menu responsivo do Bootstrap e data dinâmica no footer)

O projeto **não** utiliza frameworks JavaScript, build tools ou dependências de backend. É um site 100% estático.

## Estrutura

```text
Site-Pessoal/
├── assets/
│   └── img/
│       ├── favicon.svg
│       └── herisson.png
├── bootstrap/
│   ├── css/
│   └── js/
├── css/
│   └── style.css
├── index.html
└── README.md
```

## Executando localmente

Como o projeto é estático, basta abrir o `index.html` diretamente no navegador ou servir a pasta com um servidor estático simples:

```bash
# Python
python -m http.server 8000

# PHP
php -S localhost:8000
```

## Portfólio

Os projetos apresentados no site são trabalhos reais de atuação com infraestrutura, automação, CI/CD e Cloud, como:

- **HSAgendamentos** — projeto freelancer com Docker Compose, Linux, Nginx, MariaDB, APIs e Trivy.
- **Automação de deploy com Jenkins** — pipeline CI/CD com Jenkins, GitHub, Linux e Shell Script.

Novos repositórios e projetos serão adicionados à medida que forem organizados no GitHub.

## Publicação

O site está publicado através do **GitHub Pages** e pode ser acessado em:

**https://herissons.github.io/Site-Pessoal/**

O projeto foi preparado tecnicamente para funcionar em subdiretório do GitHub Pages:

- site totalmente estático;
- nenhuma dependência de backend, banco de dados ou processamento no servidor;
- nenhuma credencial ou dado sensível versionado.

## Autor

**Hérisson Silva** — Cloud | DevOps | Infraestrutura | Suporte

- E-mail: antonioherisson@gmail.com
- LinkedIn: [linkedin.com/in/herisson-silva-7275a0187](https://www.linkedin.com/in/herisson-silva-7275a0187/)
- GitHub: [github.com/HerissonS](https://github.com/HerissonS)