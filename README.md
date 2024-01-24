Sistema de Gerenciamento de Vendas
Este é um sistema simples de gerenciamento de vendas em Python, que utiliza classes para representar usuários (clientes e vendedores), contratos e vendas. O programa oferece opções interativas para criar clientes, vendedores, contratos e vendas, além de exibir informações detalhadas e calcular comissões.

Estrutura do Código
Classes Principais
Usuario

Representa um usuário básico com nome e contato.
Possui um método para exibir informações.
Cliente

Herda da classe Usuario.
Adiciona a propriedade endereco.
Sobrescreve o método exibir_informacoes para incluir o endereço.
Vendedor

Herda da classe Usuario.
Adiciona a propriedade id.
Sobrescreve o método exibir_informacoes para incluir o ID.
Contrato

Representa um contrato com detalhes.
Possui um método para exibir informações.
Venda

Representa uma venda com informações do cliente, vendedor, contrato, data, valor e status de pagamento.
Calcula a comissão do vendedor com base no ID.
Possui um método para exibir informações detalhadas.
Funções de Criação e Exibição
criar_cliente(): Cria um novo cliente solicitando informações ao usuário.
criar_vendedor(): Cria um novo vendedor solicitando informações ao usuário.
criar_contrato(): Cria um novo contrato solicitando detalhes ao usuário.
criar_venda(cliente, vendedor, contrato): Cria uma nova venda solicitando informações ao usuário.
exibir_informacoes(obj): Exibe as informações de um objeto.
calcular_comissao(venda): Calcula e exibe a comissão do vendedor com base na venda.
Loop de Execução
O programa utiliza um loop infinito para exibir um menu interativo.
As opções incluem criar clientes, vendedores, contratos, vendas, exibir informações, calcular comissão e sair do programa.
Como Utilizar
Execução:

Execute o script Python.
O programa iniciará um menu interativo.
Menu Interativo:

Escolha as opções do menu para criar usuários, contratos e vendas, além de exibir informações e calcular comissões.
Criação de Elementos:

Siga as instruções para criar clientes, vendedores, contratos e vendas.
Exibição de Informações:

Utilize a opção "Exibir Informações" para visualizar detalhes dos clientes e outros elementos.
Cálculo de Comissão:

Se uma venda foi criada, utilize a opção "Calcular Comissão" para calcular e exibir a comissão do vendedor.
Encerramento:

Escolha a opção "Sair" para encerrar o programa.
Observação: Este sistema foi desenvolvido para fins didáticos e pode ser adaptado conforme necessário. Certifique-se de seguir as instruções do menu para criar elementos antes de realizar vendas ou exibir informações.