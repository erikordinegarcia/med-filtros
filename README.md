# Med Filtros — Site

Site institucional estático (HTML + CSS + JS puro), com a mesma estrutura do site da M&G Tech.

## Estrutura

```
index.html   → página principal
style.css    → estilos (cores no topo, em :root)
script.js    → menu mobile, animações, menu ativo e FAQ
assets/
  logo.png       → logo da Med Filtros
  home_page.jpg  → (opcional) foto de fundo do topo
  partners/      → (opcional) logos de parceiros
```

## O que editar antes de publicar

Procure por `EDITAR` no `index.html`:

- **WhatsApp**: troque `5511900000000` (aparece 2 vezes) e `(11) 90000-0000` no rodapé
- **E-mail**: troque `contato@medfiltros.com.br`
- **Endereço**: troque `[Endereço da empresa]`
- **Anos de experiência**: bloco `+10`
- **Depoimentos**: substitua os textos entre colchetes por depoimentos reais
- **Parceiros**: coloque as logos em `assets/partners/` e troque os quadrados "Logo do parceiro"

## Fotos

- Topo: salve uma foto como `assets/home_page.jpg` e ela aparece automaticamente.
- Áreas de atuação: no `style.css`, troque o `background-image` de `.project-large`,
  `.project-two` e `.project-three` por `url('assets/sua-foto.jpg')`.

## Rodar localmente

Abra o `index.html` no navegador, ou use a extensão Live Server do VS Code.
