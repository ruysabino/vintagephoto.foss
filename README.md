# Vintage Photo

Vintage Photo é a trilha FOSS do projeto, pensada para publicação no F-Droid.

## Objetivos

- processamento local de imagem
- leitura de EXIF offline
- efeitos retrô em Canvas
- exportação em PNG
- orientação retrato e paisagem
- PWA instalável
- sem integrações Google
- geolocalização opcional apenas com OpenStreetMap / Nominatim

## Estrutura

- `index.html` — aplicação principal
- `manifest.webmanifest` — manifesto PWA
- `sw.js` — service worker
- `favicon.svg` — favicon vetorial
- `icon-192.png` e `icon-512.png` — ícones do app
- `.nojekyll` — evita processamento Jekyll no GitHub Pages
- `LICENSE` — licença do projeto

## Publicação no GitHub Pages

1. envie todos os arquivos para a raiz do repositório
2. abra `Settings > Pages`
3. escolha `Deploy from a branch`
4. selecione a branch principal e a pasta `/root`
5. salve

## Diretrizes FOSS

Para manter a compatibilidade com uma futura trilha F-Droid:

- mantenha o código-fonte público
- use licença livre
- evite SDKs e serviços proprietários
- preserve build reproduzível
- mantenha a variante com recursos Google em um projeto separado (`Polaroid Generator`)

## Licença

Consulte o arquivo `LICENSE`.
