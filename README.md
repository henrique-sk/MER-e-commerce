# MER-e-commerce
 Modelo Entidade Relacionamento do E-Commerce proposto no Desafio de Projeto Conceitual de Banco de Dados do Bootcamp de Data Science da DIO.
 
 * **Refinamento**
     * Cliente PF e PJ: Foram criadas entidades ClientePF e ClientePJ que herdam atributos de Cliente. Ambas entidades fazem relacionamento com Pedido.
     * Pagamento: Foi criada uma entidade com as informações do cartão e faz relação com Cliente.
     * Entrega: Criada conforme orientado e faz relação com Pedido.