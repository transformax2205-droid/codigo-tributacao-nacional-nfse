# Código de Tributação Nacional (cTribNac) da NFS-e Nacional

Tabela oficial dos **338 códigos de tributação nacional (cTribNac)** usados na **NFS-e Nacional** (DPS/Emissor Nacional, `nfse.gov.br`), derivada da lista de serviços da **Lei Complementar 116/2003**. Disponível em **JSON** e **CSV**, livre para uso.

## Busca online

Ferramenta de busca (por número ou por serviço, sem acento) com todos os 338 códigos:

**https://notafiscalafiliados.com.br/guia/codigo-tributacao-nacional-nfse-lista**

## Arquivos

| Arquivo | Descrição |
| --- | --- |
| [`ctribnac.json`](ctribnac.json) | Objeto `{ "codigo": "descrição" }` com os 338 códigos. |
| [`ctribnac.csv`](ctribnac.csv) | Colunas `codigo`, `codigo_formatado`, `descricao`. |

## Formato do código

O cTribNac tem **6 dígitos** no formato `item.subitem.desdobramento` (ex.: `17.06.01`). O item vem da lista de serviços da LC 116/2003.

| Código | Serviço |
| --- | --- |
| `01.01.01` | Análise e desenvolvimento de sistemas. |
| `10.05.01` | Agenciamento, corretagem ou intermediação de bens móveis ou imóveis, não abrangidos em outros itens ou subitens, por quaisquer meios. |
| `17.06.01` | Propaganda e publicidade, inclusive promoção de vendas, planejamento de campanhas ou sistemas de publicidade, elaboração de desenhos, textos e demais materiais publicitários. |
| `17.14.01` | Advocacia |
| `01.03.01` | Processamento de dados, textos, imagens, vídeos, páginas eletrônicas, aplicativos e sistemas de informação, entre outros formatos, e congêneres. |

Para **afiliado** de marketplace, o código costuma ser **17.06.01** (propaganda e publicidade, inclusive promoção de vendas).

## Guias gratuitos sobre NFS-e Nacional

- [Código de tributação nacional (cTribNac): lista e busca](https://notafiscalafiliados.com.br/guia/codigo-tributacao-nacional-nfse-lista)
- [Glossário da NFS-e Nacional (DPS, DANFSe, cTribNac, ISS)](https://notafiscalafiliados.com.br/guia/glossario-nfse-nacional)
- [Código de serviço da NFS-e para afiliado](https://notafiscalafiliados.com.br/guia/codigo-de-servico-nfs-e-afiliado)
- [Qual a melhor forma de emitir nota de afiliado (comparativo)](https://notafiscalafiliados.com.br/guia/nota-fiscal-afiliado-melhor-forma-emitir)
- [Nota fiscal de afiliado em Mercado Livre, Amazon e Magalu](https://notafiscalafiliados.com.br/guia/nota-fiscal-afiliado-marketplaces)
- [Emissor Nacional NFS-e: como emitir passo a passo](https://notafiscalafiliados.com.br/guia/emissor-nacional-nfse-como-emitir)
- Índice de guias: https://notafiscalafiliados.com.br/guias · Versão para IA: https://notafiscalafiliados.com.br/llms-full.txt

## Fonte e licença

Dados derivados do anexo de códigos de tributação nacional do Emissor Nacional da NFS-e (`gov.br/nfse`) e da lista de serviços da LC 116/2003 (documentos públicos). Compilação e arquivos distribuídos sob **CC BY 4.0** — cite [Nota Fiscal Afiliados](https://notafiscalafiliados.com.br).

Mantido por [Nota Fiscal Afiliados](https://notafiscalafiliados.com.br), emissão de NFS-e em lote pelo Emissor Nacional para afiliados PJ.
