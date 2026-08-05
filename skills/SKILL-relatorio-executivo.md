# Skill: Relatório Executivo · V4 Bilinski&Co

## O que é
Apresentação HTML de slides 16:9 para relatório mensal executivo de squad/cliente. Tema escuro cinematográfico com seções claras intercaladas.

## Como gerar
1. Baixe/leia o template: https://assets-relatorio-saber.vercel.app/templates/relatorio-executivo.html
2. O template É a fonte da verdade de layout e CSS. Mantenha o <style> completo e a estrutura de slides. Troque apenas o CONTEÚDO (textos, números, dados).
3. Aplique as regras de skills/regras-marca.md sem exceção.
4. Não adicione novas fontes, novas cores, nem CSS que conflite com os tokens.

## Anatomia (19 slides de referência)
- .slide.cover: capa com título Morganite gigante
- .slide: slide escuro padrão (default)
- .slide.divider: divisor de seção
- .slide.slide--light: slide claro (#FAF9F7) para dados densos
- Componentes: .kpi (métrica), .hrow/.htrack/.hfill (barras de progresso), .glass (card vidro), .phase/.dot (etapas), .sig (assinatura), .bleed (imagem sangrada com scrim)

## Conteúdo esperado do usuário
Resultados do mês, KPIs com meta vs realizado, fases do projeto, próximos passos. Se faltar dado, perguntar; nunca inventar número.

## Saída
Um único arquivo HTML. Fontes via https://assets-relatorio-saber.vercel.app/fonts/fonts.css. Imagens novas: o usuário sobe no repositório em /img/relatorio-executivo/ e usa a URL; nunca base64.
