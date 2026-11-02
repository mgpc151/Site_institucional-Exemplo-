# TechFácil — Site Institucional

Landing page institucional da **TechFácil**, uma iniciativa de tecnologia
voltada a pequenos negócios: sistemas sob medida, sites, automações,
chatbots com IA e integração com WhatsApp.

> "Tecnologia simples para transformar pequenos negócios."

## Sobre o projeto

Página única e estática que apresenta a empresa, seus diferenciais,
serviços e um formulário de solicitação de orçamento. O visual usa um
estilo **liquid glass** (vidro translúcido, blur, reflexos e esferas de
luz animadas) em preto, azul e cinza.

## Seções

- **Início** — proposta de valor e destaques
- **Sobre** — história, missão, diferenciais e equipe
- **Serviços** — criação de sistemas/sites, automação, chatbots, WhatsApp e suporte
- **Portfólio** — casos e resultados
- **Contato** — formulário de orçamento e canais diretos

## Tecnologias

- HTML5 semântico
- CSS3 (variáveis, grid, flexbox, `backdrop-filter`, animações)
- Google Fonts (DM Sans e Sora)
- Sem frameworks e sem dependências de build

## Como visualizar

Basta abrir `index.html` no navegador. Para servir localmente:

```bash
python -m http.server 8000
# ou
npx serve .
```

## Estrutura

```
.
├── index.html
├── css/
│   └── style.css
└── img/
    ├── icone.png
    ├── icone2.png
    ├── logo.jpg
    ├── logo_inicio.png
    ├── membro-placeholder.svg
    └── projeto-placeholder.svg
```

## Acessibilidade e responsividade

- Layout adaptável a celular, tablet e desktop
- `prefers-reduced-motion` respeitado
- Foco visível para navegação por teclado
- Fallback para navegadores sem `backdrop-filter`

## Status

Landing page em desenvolvimento. O formulário de contato está
desativado no momento (exibe um aviso ao usuário). Itens pendentes:

- Número real de WhatsApp (substituir `55DDDNUMERO`)
- E-mail de contato real
- Fotos reais da equipe e do portfólio (placeholders em `img/`)
- Integração do formulário com um backend

## Autor

Desenvolvido por Miguel.
