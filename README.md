# Betel Corrimão

Site institucional da **Betel Corrimão**, serralheria e vidraçaria especializada em inox e vidro, com mais de 30 anos de experiência. Atende Alphaville, Tamboré, Barueri, Santana de Parnaíba, Carapicuíba e região.

## Sobre o projeto

Página única (one-page), estática e responsiva, feita para apresentar os serviços da empresa e gerar pedidos de orçamento pelo WhatsApp.

### Seções

- **Início:** destaque principal com chamada para orçamento e faixa de números da empresa
- **Serviços:** corrimãos, guarda-corpos, box de banheiro, portas e janelas
- **Projetos:** galeria de imagens e links para YouTube e Instagram
- **Como trabalhamos:** contato, medição, fabricação e instalação
- **Sobre:** história e diferenciais da empresa
- **Contato:** formulário que envia a mensagem pelo WhatsApp

### Destaques técnicos

- Layout responsivo, testado de 320 px a 2560 px de largura
- Menu hambúrguer em telas menores
- Cabeçalho que ganha fundo sólido ao rolar a página
- Botão flutuante do WhatsApp com animação de pulso (respeita a preferência de movimento reduzido do sistema)
- Formulário de orçamento que monta a mensagem e abre o WhatsApp da empresa
- Imagens otimizadas e carregamento tardio (`lazy loading`)
- Sem frameworks nem etapa de build: HTML, CSS e um pequeno trecho de JavaScript

## Estrutura de arquivos

```
.
├── index.html
├── styles.css
├── README.md
└── images/
    ├── logo-betel.png
    ├── hero.jpg
    ├── escada.jpg
    ├── guarda.jpg
    ├── box.jpg
    ├── portas.jpg
    ├── perfil.jpg
    ├── alu.jpg
    ├── janela.jpg
    ├── correr.jpg
    └── fixo.jpg
```

## Como rodar

Não precisa instalar nada. Abra o `index.html` no navegador.

Para testar com um servidor local:

```bash
# Python
python3 -m http.server 8000

# ou Node
npx serve .
```

Depois acesse `http://localhost:8000`.

## Como publicar

Por ser um site estático, funciona em qualquer hospedagem (Netlify, GitHub Pages, Vercel, hospedagem tradicional).

No **Netlify**, conectado ao repositório do GitHub, basta fazer o `git push`. Não é preciso comando de build, e o diretório de publicação é a raiz do projeto.

## Como personalizar

| O que alterar | Onde |
|---|---|
| Cores da marca | Variáveis `:root` no início do `styles.css` (`--navy`, `--accent`, etc.) |
| Telefone / WhatsApp | Procure por `5511910840230` no `index.html` (links e formulário) |
| Textos e serviços | Seções correspondentes no `index.html` |
| Fotos | Substitua os arquivos da pasta `images/`, mantendo os mesmos nomes |
| Redes sociais | Links de Instagram, Facebook e YouTube no rodapé e na seção Projetos |

### Dica

As imagens atuais são renders ilustrativos. Trocar por fotos reais de obras entregues aumenta a credibilidade da página. Use imagens de até 1200 px de largura, em JPG, para manter o carregamento rápido.

## Contato da empresa

- WhatsApp: (11) 91084-0230
- Instagram: [@betelcorrimao](https://www.instagram.com/betelcorrimao/)
- Facebook: [betel.corrimaos](https://www.facebook.com/betel.corrimaos)
- YouTube: [Canal Betel Corrimão](https://www.youtube.com/@BetelCorrim%C3%A3o)

## Desenvolvedor

Desenvolvido por **Israel Calista de Pontes**

- [LinkedIn](https://www.linkedin.com/in/israel-calista-de-pontes/)
- [GitHub](https://github.com/IsraelPontes)
- [WhatsApp](https://wa.me/5511993753442)
