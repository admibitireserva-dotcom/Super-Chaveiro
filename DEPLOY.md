# Super Chaveiro Sorocaba — publicação

## Site
Projeto estático, sem dependências, sem build e sem banco de dados.
Basta publicar todo o conteúdo desta pasta na raiz da hospedagem.

## Antes de publicar no domínio definitivo
1. Informar o domínio final.
2. Adicionar `<link rel="canonical" href="https://DOMINIO/">` no `<head>`.
3. Adicionar `og:url` com a URL final.
4. Transformar `og:image`, `image` e `logo` do JSON-LD em URLs absolutas.
5. Criar `sitemap.xml` com a URL final e adicionar `Sitemap: https://DOMINIO/sitemap.xml` ao `robots.txt`.
6. Validar os dados estruturados no Rich Results Test do Google.
7. Cadastrar/verificar o domínio no Google Search Console.

## Contatos atualmente configurados
- WhatsApp / telefone: +55 15 99684-1263
- E-mail: superchaveirosorocaba@gmail.com
- Endereço: Voluntários de Sorocaba, 191, sala 5 — Sorocaba/SP
- Instagram: @superchaveirosorocaba
- Horário: todos os dias, das 8h às 22h

## Performance
- Imagens principais em WebP.
- Hero pré-carregado e com `fetchpriority="high"`.
- Demais imagens com `loading="lazy"`.
- CSS e JavaScript locais, sem bibliotecas externas.
- Logotipo convertido para WebP otimizado.
