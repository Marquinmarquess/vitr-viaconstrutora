# Vitrúvia Construtora: site institucional

Site estático (HTML único) publicado na Vercel.

## Antes da versão final
- `ZAP_NUMERO` em `index.html`: trocar pelo WhatsApp oficial
- Fotos das obras, retratos, prints do app e depoimentos (marcados como "Foto" e "Texto do depoimento")
- CNPJ e nº do CREA no rodapé e em "Quem somos"
- Remover o header `X-Robots-Tag: noindex` em `vercel.json` ao publicar no domínio final

## Hero com scroll
O modo atual desenha a casa em traço arquitetônico. Para usar o vídeo realista,
extrair os quadros para `frames/` e definir `HERO_FRAMES` em `index.html`.
