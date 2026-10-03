# Aurora Odontologia Integrada

Landing page institucional de uma clínica odontológica, criada para transmitir acolhimento, confiança e cuidado humanizado desde a primeira visita.

## Visão geral

Este projeto é uma página estática moderna e responsiva, com foco em:

- apresentar a clínica e sua proposta de atendimento;
- destacar tratamentos e experiência do paciente;
- aumentar a conversão de agendamento por meio de CTA para WhatsApp;
- manter uma identidade visual limpa, elegante e acolhedora.

## Tecnologias utilizadas

- HTML5
- CSS3
- JavaScript vanilla
- Google Fonts
- Imagens externas via Unsplash

## Estrutura do projeto

```text
frontend/
├── index.html
├── styles.css
├── script.js
├── README.md
└── assets/ (se houver personalizações futuras)
```

## Funcionalidades

- Menu responsivo para mobile;
- Seções de apresentação, serviços, experiência e FAQ;
- Animações de entrada ao rolar a página;
- Botões e links com foco em contato e agendamento;
- Layout pensado para conversão de leads em clínicas.

## Como executar localmente

### Opção 1: abrir diretamente no navegador

Basta abrir o arquivo `index.html` no navegador.

### Opção 2: rodar um servidor local

No terminal, dentro da pasta do projeto, execute:

```bash
python -m http.server 8000
```

Em seguida, acesse:

```text
http://localhost:8000
```

## Personalização

Para adaptar a página ao seu projeto real, você pode alterar facilmente:

- número do WhatsApp;
- endereço e horário de funcionamento;
- e-mail de contato;
- textos da clínica, tratamentos e FAQ;
- paleta de cores no bloco `:root` em `styles.css`.

## Arquivos principais

- `index.html`: estrutura e conteúdo da landing page;
- `styles.css`: design visual, responsividade e estilos;
- `script.js`: comportamento do menu e animações de scroll.

## Observações

Este projeto foi desenvolvido como uma landing page estática, sem dependências externas de build ou framework. Isso facilita manutenção, customização e deploy em serviços simples como GitHub Pages, Netlify ou Vercel.

Se quiser, posso continuar e transformar este projeto em uma versão com:

- formulário de agendamento;
- integração com backend;
- versão em React/Next.js;
- documentação mais completa para produção.
