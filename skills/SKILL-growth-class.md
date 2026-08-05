# Skill: Growth Class · V4 Bilinski&Co

## O que é
Apresentação HTML 16:9 de Growth Class: aula estratégica para cliente, com diagnóstico, conceitos e plano. 13 slides de referência, tema escuro com bloco central de slides claros para dados.

## Como gerar
1. Leia o template: https://assets-relatorio-saber.vercel.app/templates/growth-class.html
2. O template É a fonte da verdade de layout e CSS. Mantenha o <style> completo e a estrutura. Troque apenas o CONTEÚDO.
3. Aplique skills/regras-marca.md sem exceção.
4. Personalização por cliente: nome do cliente no lugar do placeholder, logo do cliente por URL de /logos/clientes/ (chip branco sem sombra), imagens específicas em /img/growth-class/ ou pasta do cliente.

## Anatomia
- .slide.cover: capa co-branded
- .slide: conteúdo escuro (conceito, provocação)
- .slide.slide--light: bloco de dados/diagnóstico (5 slides no meio)
- .slide.closing: encerramento com CTA verde

## Conteúdo esperado do usuário
Nome do cliente, diagnóstico/dados do negócio, conceitos a ensinar, plano proposto. Se faltar dado, perguntar; nunca inventar número.

## Saída
Um único arquivo HTML com assets por URL. Nunca base64.
