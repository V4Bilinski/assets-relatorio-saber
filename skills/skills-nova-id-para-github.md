# Skill: NOVA ID · V4 Bilinski&Co [EXPERIMENTAL]

## O que é
Formato de teste da nova identidade 2026 (BrandBook V4). Não substitui os formatos existentes; usar somente quando o usuário pedir "NOVA ID" explicitamente.

## Como gerar
1. Leia o template: https://assets-relatorio-saber.vercel.app/templates/nova-id.html
2. O template É a fonte da verdade. Mantenha <style> e estrutura; troque só conteúdo.
3. GLASS É RECEITA, NÃO CRIAÇÃO: use a classe .v4-glass exatamente como está no template (6 camadas do BrandBook). É PROIBIDO inventar outro efeito de vidro, alterar blur, opacidades ou sombras.
4. GRADIENTES SÓ OS OFICIAIS 2026 (já no :root do template): Primary 135deg #560303->#FB2E0A; Subtle #560303->#C41E08; Radial #FB2E0A->#560303 origem 20% 80%. Proibido criar gradiente novo.
5. Ícones: Material Symbols Rounded, weight 700 (link já no template). Nunca emoji, nunca SVG improvisado.
6. Aplicar regras-marca.md (zero azul, CTA verde #00A86B, amarelo de ativação 2026 = #FFDD00, Morganite só título, números como dígitos).

## Anatomia dos slides
- .slide.capa: foto oficial mão+logo (imagem à direita, título Morganite à esquerda)
- .slide.sumario: mulher à direita (NUNCA cobrir com elementos); painel .v4-glass à esquerda com o sumário
- .slide.conteudo: fundo gradiente + título + cards .v4-glass (2 a 4)
- .slide.grafico: fundo gradiente + card glass com gráfico de barras CSS + KPIs
- .slide.reverb: divisor conceitual com reverberação (3 glass aninhados)
- .slide.closing: encerramento com CTA verde

## Imagens do formato
https://assets-relatorio-saber.vercel.app/img/nova-id/
capa-mao-logo.webp · sumario-mulher.webp · fundo-gradiente.webp · fundo-cards-glass.webp
