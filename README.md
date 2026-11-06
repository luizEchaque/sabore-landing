# Sabore · Landing page

Landing page responsiva em React + Vite, construída com a identidade visual e os materiais fornecidos pela Sabore.

## Executar

Requer Node.js 20.19+ ou 22.12+.

```sh
npm install
npm run dev
```

## Gerar versão de produção

```sh
npm run build
npm run preview
```

A pasta `dist` contém o site estático pronto para hospedagem.

## GitHub Pages

Endereço: https://luizechaque.github.io/sabore-landing/

O workflow `.github/workflows/deploy-pages.yml` instala as dependências, compila e publica automaticamente a cada push para `main`. O repositório deve usar **Settings → Pages → Source: GitHub Actions**.

O Vite utiliza a base `/sabore-landing/`. A prévia local também deve ser acessada nesse caminho, informado pelo Vite ao iniciar o servidor.

## Conteúdo e manutenção

- `src/main.jsx`: seções, produtos, valores, sabores e telefone do WhatsApp.
- `src/styles.css`: estilos, fontes locais e regras responsivas.
- `public/assets`: marca, grafismos, imagens otimizadas e cardápio em PDF.
- O catálogo e o contato foram transcritos do cardápio fornecido. Confirme valores e disponibilidade com a empresa antes de uma divulgação comercial.
- O pedido abre uma mensagem no WhatsApp com produto, sabor, tamanho, quantidade e total estimado. Não há pagamento, envio automático ou armazenamento de dados.
- As imagens de apresentação foram aproveitadas dos mockups fornecidos pela marca; as ilustrações de produtos são decorativas.
