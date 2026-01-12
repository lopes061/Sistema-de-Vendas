# Sistema de Gestão Comercial

Sistema completo de gerenciamento comercial com emissão fiscal (NFC-e, NF-e, NFS-e).

## 📋 Funcionalidades

- **Gestão de Produtos**: Cadastro, edição, alteração de preços e controle de estoque
- **Gestão de Clientes**: Cadastro de CPF/CNPJ com preenchimento automático
- **Vendas**: Sistema de vendas com carrinho, produtos cadastrados e avulsos
- **Emissão Fiscal**: NFC-e, NF-e e NFS-e com cancelamento
- **Controle de Caixa**: Abertura, fechamento, sangria e suprimento
- **Relatórios**: Vendas por dia/período, produtos mais vendidos, estoque baixo
- **Exportação XML**: Para contabilidade e auditoria
- **Integração**: APIs fiscais (Focus NFe, TecnoSpeed)
- **Interface Gráfica**: Sistema completo com Tkinter (GUI moderna)

## 🛠️ Tecnologias

- **Python 3.x**
- **SQLite** - Banco de dados
- **Tkinter** - Interface gráfica
- **Requests** - Integração com APIs

## 📁 Estrutura do Projeto

```
├── models/          # Modelos de dados (Produto, Cliente, Venda, etc)
├── utils/           # Utilitários (validadores, APIs, exportação)
├── database/        # Configuração do banco de dados
├── reports/         # Relatórios e XMLs gerados
├── gui_app.py       # Interface gráfica (Tkinter)
└── requirements.txt # Dependências do projeto
```

## 📝 Licença

Este projeto está sob licença MIT.
