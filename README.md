# Termos de Serviço | Animes Café

Site estático dos Termos de Serviço do Hatsutech, app/bot usado no servidor Animes Café.

## Sobre

Este repositório publica uma página simples em HTML e CSS, sem framework, build step ou JavaScript obrigatório.

## Arquivos

- `index.html`: conteúdo dos Termos de Serviço.
- `style.css`: estilos visuais da página.

## Site principal

- https://animescafe.vercel.app/

## Rodar localmente

Abra o arquivo `index.html` diretamente no navegador ou sirva a pasta atual com:

```bash
python3 -m http.server 8080
```

Depois acesse:

```text
http://localhost:8080
```

## Deploy

### Vercel

1. Crie ou selecione um projeto na Vercel.
2. Use a raiz deste repositório como diretório do projeto.
3. Não configure framework.
4. Publique como site estático.

### Netlify

1. Crie um novo site na Netlify.
2. Faça upload deste repositório ou conecte o repositório Git.
3. Deixe o comando de build vazio.
4. Use a raiz do repositório como diretório de publicação.

### GitHub Pages

1. Ative Pages nas configurações do repositório.
2. Selecione a branch desejada.
3. Publique a partir da raiz do projeto.

## Discord Developer Portal

Depois do deploy, copie a URL pública desta página e configure no campo **Terms of Service URL** do app Hatsutech.
