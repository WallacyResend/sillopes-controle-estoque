# sillopes-controle-estoque
MVP de controle de estoque e registro de vendas para loja de bijuterias (Projeto de Extensão / ADS).
# SILLOPES — MVP de Controle de Estoque e Vendas

Sistema web responsivo (mobile-first) desenvolvido para apoiar o controle rápido de estoque e o registro de vendas (WhatsApp e Shopee) de uma microempresa de bijuterias.

## Problema Resolvido
Evitar vendas de peças sem saldo disponível, eliminar o retrabalho de anotações manuais fragmentadas e alertar rapidamente sobre produtos que atingiram o estoque mínimo.

## Funcionalidades do MVP
- **Autenticação (RF01):** Acesso restrito ao proprietário com controle de sessão.
- **Registro de Venda com Baixa Automática (RF04 / RF08):** Lançamento rápido por produto, quantidade e canal (Shopee ou WhatsApp) com desconto imediato no saldo.
- **Bloqueio de Venda sem Saldo (RF05):** Validação no servidor que impede saídas acima do estoque disponível.
- **Alertas de Reposição e Pedidos (RF06 / RF07):** Listagem automática de produtos no estoque mínimo ou abaixo dele e indicador de pedidos aguardando envio.

## Tecnologias
- **Back-end:** Python 3 + Django
- **Banco de Dados:** SQLite (ambiente de desenvolvimento) / PostgreSQL (produção)
- **Front-end:** HTML5, CSS3 responsivo (coluna única, mobile-first) e JavaScript
