# Ecommerce

Sistema de Loja Online em Java

Projeto de faculdade desenvolvido em Java para simular um e-commerce simples, utilizando:

- Programação Orientada a Objetos (POO)
- Collections (`ArrayList`)
- Exceptions (padrão e customizada)
- Interface de console
- Interface gráfica com Swing

---

Estrutura do Projeto

Arquivos principais:

- `Produto.java`  
- `Cliente.java`  
- `ItemPedido.java`  
- `Pedido.java`  
- `PedidoStatus.java`  
- `EstoqueInsuficienteException.java`  
- `Main.java`  
- `LojaUI.java`

---

Pré-requisitos

- Java instalado (JDK 21+ ou superior)  
- Estar na pasta do projeto no terminal (exemplo: `C:\Ecommerce`)

Compilação

Na pasta do projeto, executar:

javac Produto.java Cliente.java ItemPedido.java PedidoStatus.java Pedido.java EstoqueInsuficienteException.java Main.java LojaUI.java

Execução pelo CONSOLE (Main)

Para rodar o sistema no modo console:

java Main

Para rodar no modo interface

java LojaUI

______________________________________________

No menu, você terá opções como:

1. Listar produtos

2. Cadastrar produto

3. Repor estoque

4. Ver cliente atual

5. Criar novo pedido

6. Listar pedidos

7. Abrir interface gráfica

8. Sair

O fluxo recomendado para demonstrar:

1. Listar produtos (opção 1)

2. Cadastrar um novo produto (opção 2)

3. Repor estoque de um produto (opção 3)

4. Criar um pedido (opção 5), adicionando itens e testando a validação de estoque

5. Listar pedidos (opção 6)
