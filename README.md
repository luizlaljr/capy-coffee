# Capy Coffee — Vercel-ready

Implementação estática baseada na referência visual fornecida, com foco em fidelidade no viewport de **1536 × 1024**.

## Rodar localmente

Você pode abrir `index.html` diretamente ou servir a pasta com qualquer servidor HTTP, por exemplo:

```bash
npx serve .
```

## Publicar na Vercel

1. Crie um repositório e envie todos os arquivos desta pasta.
2. Importe o repositório na Vercel.
3. Framework Preset: **Other**.
4. Build Command: deixe vazio.
5. Output Directory: `.`
6. Deploy.

## Estrutura

- `index.html`: estrutura semântica do site.
- `styles.css`: reprodução visual + responsividade.
- `script.js`: navegação suave.
- `assets/`: fotos e elementos extraídos da referência enviada.
- `vercel.json`: configuração de deploy/cache.

## Observação de fidelidade

A seção hero usa a arte fornecida como composição visual exata e adiciona uma camada semântica/clicável por cima. O cardápio, textos, preços, seção da idealizadora e footer são elementos reais de HTML/CSS. Isso equilibra máxima fidelidade à imagem com um site navegável e editável.
