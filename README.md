# 🛒 Sistema de Lista de Produtos e Carrinho de Compras

Um sistema completo para gerenciamento de estoque de produtos e carrinho de compras, desenvolvido em Python.

## 📋 Funcionalidades Principais

### 🏷️ Módulo de Produtos
- Lista completa de produtos com ID, nome, preço e quantidade em estoque
- Visualização formatada em tabela
- Cálculos automáticos:
  - Média de preços
  - Quantidade total em estoque
  - Valor total do estoque

### 🛍️ Módulo de Carrinho de Compras
- Adição de produtos por ID
- Visualização do carrinho com formatação profissional
- Cálculo automático do total da compra
- Tratamento de erros para entradas inválidas

## ⚙️ Como Usar

1. **Listar Produtos Disponíveis**:
   ```python
   lista()  # Exibe todos os produtos cadastrados
   ```

2. **Adicionar ao Carrinho**:
   ```python
   # O sistema pedirá os IDs dos produtos interativamente
   # Digite 0 para finalizar
   ```

3. **Visualizar Carrinho**:
   ```python
   mostrar_carrinho()  # Exibe os itens e o total da compra
   ```

## 📊 Estrutura dos Dados

Os produtos são armazenados na estrutura:
```python
Produtos = [
    [{
        "id": int,
        "nomeProduto": str,
        "preco": float,
        "Qtde": int
    }],
    # ... mais produtos
]
```

## ✨ Recursos Adicionais

- Formatação profissional de valores monetários
- Feedback visual durante a navegação
- Tratamento de erros para entradas inválidas
- Cálculos automáticos de totais e médias

## 📝 Exemplo de Saída

```
Id  | Nome        |    Preço |    Qtde
----------------------------------------
1   | Maçã        | R$  3.50 |     200
...
----------------------------------------
Quantidade Total de Itens: 2070
Média de Preços: R$ 5.75
Valor Total em Estoque: R$ 11890.50
```

## 🚀 Melhorias Futuras

1. Adicionar sistema de login
2. Implementar desconto por quantidade
3. Adicionar opção para remover itens do carrinho
4. Salvar histórico de compras
5. Interface gráfica (Tkinter/PyQt)

## 📄 Licença

Este projeto está licenciado sob a licença MIT.
