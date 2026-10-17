# Nossas Viagens

Planejador de viagens da família: roteiro por dia, agenda, onde comer, plano B, hospedagem, transporte, orçamento com pagantes, malas, checklist "não esquecer", documentos, notas e exportação de documento em PDF.

## Como funciona
- Tudo fica salvo **neste aparelho** (no navegador). Não há servidor.
- Funciona sem internet depois da primeira abertura.
- A previsão do tempo vem do Open-Meteo quando faltam até 16 dias para a viagem.
- Para passar para outro aparelho: **Backup › Baixar arquivo de backup** e, no outro, **Restaurar de um arquivo**. As fotos vão junto.

## Publicar no GitHub Pages
1. Crie um repositório (ex.: `nossas-viagens`) e envie estes arquivos para a raiz.
2. Em **Settings › Pages**, escolha *Deploy from a branch*, branch `main`, pasta `/ (root)`, e salve.
3. O app fica em `https://SEU-USUARIO.github.io/nossas-viagens/`.

No celular, abra o link e use **Adicionar à tela inicial** para ele virar um app.

## Atualizar
Troque o `index.html` e mude a versão em `sw.js` (`nossas-viagens-v1` → `v2`) para os celulares pegarem a versão nova.
