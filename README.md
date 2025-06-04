# 💳 Módulo de Gerenciamento de Pagamentos

## 📄 Descrição
Este módulo permite o processamento de pagamentos para um sistema de carrinho de compras, oferecendo suporte a diferentes métodos de pagamento, incluindo Pix, Cartão de Débito e Cartão de Crédito (com opção de parcelamento).

## 🚀 Funcionalidades
- ✅ Pagamento via **Pix**
- ✅ Pagamento via **Cartão de Débito**
- ✅ Pagamento via **Cartão de Crédito** com até **5 parcelas**

## 💻 Exemplo de Uso
O programa será executado diretamente no terminal. Ele exibirá as formas de pagamento e solicitará que o usuário escolha uma opção.

Se a opção selecionada for Cartão de Crédito, será possível escolher até 5 parcelas.

## 🔧 Funções Disponíveis

| Função                   | Descrição                                               |
|--------------------------|---------------------------------------------------------|
| `exibir_formas_pagamento()` | Exibe as formas de pagamento disponíveis              |
| `selecionar_pagamento()`    | Solicita e retorna a escolha do usuário                |
| `selecionar_parcelas()`     | Se for cartão de crédito, permite escolher as parcelas |
| `processar_pagamento()`     | Executa todo o fluxo de pagamento                       |

## ⚠️ Regras
O parcelamento está disponível apenas para Cartão de Crédito, limitado a até 5 parcelas.
