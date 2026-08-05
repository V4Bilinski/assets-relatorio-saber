# Passo a passo de implementação

## Fase 1 · Colocar no ar (hoje, ~10 min)
1. Abra github.com/V4Bilinski/assets-relatorio-saber
2. Add file > Upload files
3. Arraste o CONTEÚDO da pasta design-system (as subpastas e arquivos, não a pasta mãe)
4. Escreva no commit: "design system v1" > Commit changes (direto na main)
5. Aguarde ~1 min (o Vercel publica sozinho)
6. TESTE 1: abra https://assets-relatorio-saber.vercel.app
   O título "Design System" deve aparecer alto, condensado e vermelho. Se sim, fontes OK.
7. TESTE 2: abra https://assets-relatorio-saber.vercel.app/templates/relatorio-executivo.html
   Deve estar idêntico ao seu HTML original.

## Fase 2 · Completar o banco de assets (esta semana)
1. Baixe as 3 logos de ai.bilinski.cloud (abrir a URL da logo no navegador > clicar com botão direito > salvar) e suba em /logos/ com os mesmos nomes
2. Suba logos de clientes em /logos/clientes/ (PNG transparente, nome minúsculo sem acento)
3. Suba fotos do time em /fotos/time/ (fundo radial vermelho, WebP)
4. Imagem nova sempre: converter em squoosh.app > WebP qualidade 80 > máx 300KB

## Fase 3 · Usar no dia a dia
Opção A (Skill, recomendado): instale a skill apresentacoes-bilinski no Claude
(Configurações > Capacidades > Skills > enviar o zip). Depois é só pedir:
"Gera um Relatório Executivo com esses dados: ..."

Opção B (sem skill): cole no chat o conteúdo de skills/regras-marca.md +
a SKILL do formato + seu conteúdo.

## Limite conhecido
O HTML final precisa de internet para carregar fontes e imagens.
Para apresentar offline, peça à IA: "gera a versão empacotada com assets embutidos"
(fica pesada, usar só nesse caso).

## Regra de manutenção
Toda mudança de padrão visual = editar o template no GitHub, nunca no chat.
O template é a fonte da verdade; o chat só troca conteúdo.
