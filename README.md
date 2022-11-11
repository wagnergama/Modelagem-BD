# Modelagem de Banco de Dados

>Neste projeto utilizei o [MySQL Workbench](https://www.mysql.com/products/workbench/) para modelar um escopo de E-commerce. 
>
>As instancias utilizadas foram:
>1. Cliente: Com duas especializações
> * Cliente PJ (Pessoa Jurídica)
> * Cliente PF (Pessoa Física)
>2. Fornecedor (Produtos próprios do E-commerce)
>3. Parceiros  (Vendem seus produtos dentro do E-commerce)
>4. Produtos
>5. Entrega-Frete (Persiste no BD essa informação caso precise realizar um extorno de venda)
>6. Estoque 
>7. Pagamento (Persiste no BD as informações de cartão de Crédito/Débito do cliente)
>8. Pedido (Persiste no BD o que o cliente comprou e a forma de pagamento)

## Narrativa - Cliente
* O cliente pode se cadastrar no site com seu CPF ou CNPJ
* O Endereço do cliente irá determinar o valor do frete (Será calculado por uma função)
* Um cliente pode comprar mais de um pedido. Este tem um período de carência para devolução do produto
![image](https://user-images.githubusercontent.com/42256375/201388448-f5a01be4-151d-47eb-891f-64e2b9bc1885.png)

