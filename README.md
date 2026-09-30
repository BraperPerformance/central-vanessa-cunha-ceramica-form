# Pré-briefing de encomendas · Vanessa Cunha Cerâmica

Formulário público para pedidos de orçamento de peças sob encomenda. Site estático: sem build, sem dependências e sem banco de dados.

Ao enviar, a pessoa é levada ao WhatsApp da Vanessa com as respostas já escritas. Os pedidos chegam apenas pelo WhatsApp; nada fica armazenado.

## Arquivos

| Arquivo | Função |
|---|---|
| `index.html` | O formulário. **O nome precisa ser exatamente `index.html`.** |
| `assets/` | Logos usadas na página |

## Publicar (GitHub → Vercel)

1. Crie um repositório dedicado e suba todos os arquivos para a raiz (branch `main`), mantendo a pasta `assets`.
2. Na Vercel, importe o repositório como projeto estático (framework: *Other*, sem build command, output = raiz).
3. O endereço publicado é o link público do formulário. É ele que vai no Linktree.

## Trocar o número do WhatsApp

No `index.html`, altere a linha `var WHATSAPP='5511976875699';` (DDI + DDD + número, só dígitos).

## Imagens de referência

Link de WhatsApp não anexa arquivos. O formulário orienta a pessoa a enviar as imagens na mesma conversa, logo depois da mensagem.
