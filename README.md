# Sistema de Venda de Água

Este projeto é um programa em C que simula um sistema de vendas de diferentes tipos de água via terminal. O usuário pode escolher entre várias opções de água, adicionar ao carrinho e selecionar a forma de pagamento, incluindo descontos e parcelamentos.

## Funcionalidades

- **Menu Inicial:** O usuário pode iniciar uma venda ou sair do programa.
- **Seleção de Produtos:** São oferecidos seis tipos de água com preços diferentes:
  - Água comum
  - Água de poço
  - Água com gás
  - Água benta
  - Água saborizada
  - Água de coco
- **Carrinho de Compras:** O usuário pode adicionar quantos produtos quiser antes de finalizar a compra.
- **Finalização:** Ao finalizar, o programa mostra o valor total e oferece opções de pagamento:
  - Dinheiro/Pix (15% de desconto)
  - Cartão de crédito à vista (10% de desconto)
  - Parcelamento em 2 vezes (sem juros)
  - Parcelamento em 3 vezes ou mais (10% de juros)
- **Validações:** O sistema valida as opções escolhidas e informa o usuário em caso de entradas inválidas.

## Como usar

1. Compile o arquivo `avaliativa.c` usando um compilador C.
2. Execute o programa no terminal.
3. Siga as instruções exibidas para realizar uma compra.

## Observações

- O programa utiliza variáveis do tipo `float` para armazenar valores monetários.
- O controle de fluxo é feito com estruturas de repetição e variáveis booleanas.
- O sistema é totalmente interativo via terminal.
