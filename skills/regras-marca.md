# Regras de marca V4 Bilinski&Co (inegociáveis)

Aplicar em TODA peça HTML gerada. Violação de qualquer regra = refazer.

## Cor
- Vermelho #E50914 é a cor da marca: luz de cena, acento, destaque. NUNCA em botão de conversão.
- CTA sempre verde: #00A86B (texto grande/bold) ou #0E8420 (texto normal, passa AA).
- ZERO azul em qualquer tom, em qualquer elemento.
- Fundos escuros padrão: #050505, #280000, ou var(--bg-dark).
- Verde #3FBF7F apenas como estado positivo de dado, nunca CTA.

## Tipografia
- Morganite: só títulos e números de impacto, sempre UPPERCASE condensado. NUNCA em corpo de texto.
- IBM Plex Sans: todo o corpo, labels, eyebrows, descrições.
- Máximo 2 famílias por peça. Nunca serif.
- Números sempre como dígitos: "45 dias", nunca "quarenta e cinco dias".

## Copy
- Português brasileiro com acentuação completa.
- Zero travessão em texto renderizável (hífen em palavra composta pode).
- Dado antes de adjetivo: a frase abre com número, caso ou fato.
- Toda tela termina puxando ação, não filosofia.

## Assets
- Logo é intocável: usar sempre os arquivos por URL. Proibido recriar em tipografia, SVG, IA, rotacionar, distorcer, recolorir ou aplicar sombra.
- Logos oficiais: https://ai.bilinski.cloud/logos/logo-bilinski-branco.png (padrão sobre escuro), logo-bilinski-preto.png (sobre claro P&B), logo-bilinski-vermelho.png (sobre claro).
- Fontes e imagens NUNCA em base64 dentro do HTML. Sempre por URL do repositório de assets.
- Foto de pessoa: fundo radial vermelho obrigatório, meio-corpo. Proibido stock genérico.

## Superfície
- Glass é o default de card: fundo translúcido, borda iluminada, blur. Flat só como fallback.
- Cena escura com glow vermelho localizado atrás do assunto.
- Contraste mínimo WCAG AA: 4.5:1 texto normal, 3:1 texto grande.
