# OnePage - Indicadores Diários por Loja

Este script automatiza o envio diário de e-mails com indicadores de performance para cada loja.

## Funcionalidades

- Leitura dos dados de vendas por loja.
- Cálculo de:
  - Faturamento do dia e do ano
  - Diversidade de produtos
  - Ticket médio
- Comparação com metas definidas.
- Geração de e-mail com resumo visual dos indicadores.
- Envio automático via Outlook.
- Anexo com planilha detalhada dos dados do dia.

## Como usar

1. Configure os arquivos de entrada:
   - `dicionario_lojas` com os DataFrames de vendas.
   - `emails` com os contatos dos gerentes.
2. Defina as metas:
   - `meta_faturamento_dia`, `meta_qtdeprodutos_dia`, etc.
3. Rode o script com a data desejada em `dia_indicador`.
4. Os e-mails serão enviados automaticamente via Outlook.

## Pré-requisitos

- Python 3.x
- Pandas
- pywin32 (para integração com o Outlook)

## Exemplo de uso

```bash
python main.py
```

---

📩 Geração e envio automático de relatórios diários por e-mail.
