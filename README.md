# Design System · V4 Bilinski&Co

Repositório de assets e padrões para geração de apresentações via LLM.
Publica automaticamente em https://assets-relatorio-saber.vercel.app

## Estrutura
- tokens/tokens.css · cores, gradientes, tipografia (fonte da verdade)
- fonts/ · Morganite self-hosted + fonts.css
- logos/ · logos Bilinski/V4 + logos/clientes/ (1 por cliente)
- fotos/time/ · fotos oficiais do time (fundo radial obrigatório)
- img/relatorio-executivo/ · imagens desse formato
- img/growth-class/ · imagens desse formato
- templates/ · 1 HTML de referência por formato (layout congelado)
- skills/ · regras-marca.md + 1 skill por formato

## Fluxo de uso com o Claude
Cole no chat: regras-marca.md + skill do formato + seu conteúdo. A IA lê o template pela URL e devolve o HTML final.

## Como atualizar
GitHub V4Bilinski/assets-relatorio-saber > Add file > Upload files > Commit na main. O Vercel publica em ~1 min.

## Regras de ouro
1. Editar SEMPRE aqui; cópia local é rascunho.
2. Nada de base64 em HTML.
3. Nada de cor, fonte ou componente fora dos tokens.
4. ATENÇÃO: o template só renderiza bonito com os assets no ar. Antes do primeiro upload, a Morganite não carrega.
