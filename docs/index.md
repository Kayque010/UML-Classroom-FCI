<h2><a href= "https://www.mackenzie.br">Universidade Presbiteriana Mackenzie</a></h2>
<h3><a href= "https://www.mackenzie.br/graduacao/sao-paulo-higienopolis/sistemas-de-informacao">Sistemas de Informação</a></h3>


<font size="+12"><center>
**Sistema Pizza-Express**
</center></font>

**Conteúdo**

- [Autores](#autores)
- [Descrição do Projeto](#descrição-do-projeto)
- [Análise de Requisitos Funcionais e Não-Funcionais](#análise-de-requisitos-funcionais-e-não-funcionais)
- [Diagrama de Atividades](#diagrama-de-atividades)
- [Diagrama de Casos de Uso](#diagrama-de-casos-de-uso)
- [Descrição dos Casos de Uso](#descrição-dos-casos-de-uso)
- [Diagrama de Sequência](#diagrama-de-sequência)
- [Diagrama de Classes](#diagrama-de-classes)
- [Diagrama de Estados](#diagrama-de-estados)
- [Diagrama de Implantação](#diagrama-de-implantação)
- [Referências](#referências)


# Autores

* Kayque Matias Ferreira



# Descrição do Projeto

*O projeto visa desenvolver um sistema que otimize o processo de recebimento e entrega de pizzas em um estabelecimento que tem perdido clientes por conta de um concorrente que consegue entregar com maior velocidade. A ideia é utilizar automação em todo o processo desde o momento do recebimento do pedido, cálculo da loja mais próxima do cliente, automação no preparo e envio e, consequentemente maior agilidade e qualidade na entrega para o cliente.*

# Análise de Requisitos Funcionais e Não-Funcionais


## Requisitos Funcionais ##

**Cardápio Online:**

* Solicitar endereço do cliente;
* Consultar produtos
* Adicionar produtos ao carrinho
* Retirar produtos do carrinho
* Finalizar pedido
* Cancelar pedido
* Cadastrar dados do cliente no sistema
* Informar nome do responsável pelo pedido
* Escolher forma de pagamento

**Central:**

* Receber endereço do cliente
* Calcular loja mais próxima do endereço informado
* Aguardar efetivação do pedido
* Enviar o pedido para loja escolhida quando pedido for efetivado
* Finalizar processo e apagar dados de localização se pedido não for efetuado
* Salvar dados cadastrais do cliente se o pedido for efetivado

**Loja:**

* Recber ordem de pedido da central
* Informar o sistema da cozinha para preparação
* Enviar endereço para entregador
* enviar para entrega
* Dar baixa como entregue no pedido

## Requisitos Não Funcionais ##
* Não armazenar dados de clientes que não efetivaram pedidos;
* Cuidado no tratamento dos dados de localização, nome, e todos os demais dados pessoais dos clientes que efetivarem os pedidos;
* Ambiente de pagamento ágil e seguro;
* Procedimentos para restabelecer o sistema em caso de queda de no máximo 5
minutos;
* Facilidade de navegação para os usuários;
* Integração fluída do sistema entre as interações da central com as lojas;

# Diagrama de Atividades

[Diagrama de Atividades.pdf](https://github.com/user-attachments/files/17951939/Diagrama.de.Atividades.pdf)


# Diagrama de Casos de Uso

[Pizza Express - Casos de uso.pdf](https://github.com/user-attachments/files/17249216/Pizza.Express.-.Casos.de.uso.pdf)


# Descrição dos Casos de Uso

[Pizza Express - Descrição dos casos de uso.pdf](https://github.com/user-attachments/files/17249219/Pizza.Express.-.Descricao.dos.casos.de.uso.pdf)

# Diagrama de Sequência

[Diagrama de Sequencia.pdf](https://github.com/user-attachments/files/17951942/Diagrama.de.Sequencia.pdf)

# Diagrama de Classes

[Diagrama de Classes.pdf](https://github.com/user-attachments/files/17951947/Diagrama.de.Classes.pdf)

# Diagrama de Estados

[Diagrama de Estados.pdf](https://github.com/user-attachments/files/17951951/Diagrama.de.Estados.pdf)

# Diagrama de Implantação

[Diagrama de Implantação.pdf](https://github.com/user-attachments/files/17951952/Diagrama.de.Implantacao.pdf)

# Referências

**__SOMMERVILLE, Ian. Engenharia de software. 10. ed. São Paulo, SP: Pearson, 2018. E-book. Disponível em: https://plataforma.bvirtual.com.br. Acesso em: 28 nov. 2024.**__

**__Engenharia de software: uma abordagem profissional Roger S. Pressman, Bruce R. Maxim; – 9. ed. – Porto Alegre: AMGH, 2021.**__

**__Utilizando UML e padrões : uma introdução à análise e
ao projeto orientados a objetos e ao desenvolvimento iterativo / Craig Larman – 3. ed. – Porto Alegre : Bookman, 2007**__

 **__UML essencial: um breve guia para a linguagem-padrão de modelagem de objetos / Martin Fowler – 3.ed. – Porto Alegre: Bookman, 2005.**__
