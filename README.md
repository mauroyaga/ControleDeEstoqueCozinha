# ControleDeEstoqueCozinha
Este projeto conciste em um sistema a ser dezenvolvido a mérito de pesquisa para 
a graduação do curso de Análide de Projeto de Sistemas da Graduação de Análise e Desenvolvimento de 
Sistemas da Faculdade Senac-PR Maringá

Alunos Desenvolvedores: 
Marcelo
Kalel 
Mauro

Orientador: Willian Nalepa Oizumi


SISTEMA DE CONTROLE DE ESTOQUE PARA COZINHAS



ESTRUTURA DO SISTEMA INICIAL

Pacote Telas: contém as classes responsáveis por exibir as interfaces gráficas do sistema para o usuário. 
Nesse pacote, você pode incluir as seguintes telas:

Tela Inicial: exibe a lista de itens no estoque, juntamente com informações como quantidade disponível, 
data de validade e notificações de nível de estoque.

Tela de Manipulação dos Itens: permite ao usuário adicionar novos itens ao estoque, notificar a data de 
compra e validade, bem como a quantidade disponível.

Tela de Detalhes do Item: exibe informações mais detalhadas sobre um item específico no estoque, como 
data de compra, data de validade e quantidade disponível.

Pacote Lógica de Negócio: contém as classes responsáveis por implementar as regras de negócio do sistema,
incluindo validações e cálculos. Nesse pacote, você pode incluir as seguintes classes:

GerenciadorDeEstoque: responsável por gerenciar as operações relacionadas ao estoque, como adicionar um novo item, 
verificar o nível de estoque e notificar o usuário sobre a data de validade dos itens.
ValidadorDeItem: responsável por validar as informações fornecidas pelo usuário ao adicionar um novo item ao estoque,
como a data de validade e a quantidade disponível.

Pacote Persistência de Dados: contém as classes responsáveis por armazenar os dados do sistema em um banco de 
dados ou arquivo. Nesse pacote, você pode incluir as seguintes classes:
DAO (Data Access Object): responsável por realizar as operações de leitura e gravação dos dados em um banco de dados
ou arquivo.
ItemDAO: responsável por realizar as operações específicas relacionadas aos itens no estoque, como adicionar, 
remover e atualizar os itens.

_______________________________________________________________________________________________________________

PACOTES E CLASSES ORGANIZADOS NA ARQUITETURA MVC* ATENDENDO AO REQUISITOS FUNDAMENTAIS MVP*

Pacote Telas:

Pacote Lógica de Negócio
Pacote Persistência de Dados
Pacote Telas

Tela Inicia
Lista de Itens
Quantidade
Notificação de validade
Notificação de nível de estoque

Tela de Manipulação dos Itens
Adiciona ingredientes
Notifica data de compra e validade
Quantidade Disponível

Tela de Detalhes do item
Informações detalhadas do item
Data de compra
Data de Validade
Quantidade Disponível

_______________________________________________________________________________________________________

Pacote Lógica de Negócio

classes:

GerenciadorDeEstoque: 
responsável por gerenciar as operações relacionadas ao estoque, como adicionar um novo item, verificar 
o nível de estoque e notificar o usuário sobre a data de validade dos itens.

ValidadorDeItem:
responsável por validar as informações fornecidas pelo usuário ao adicionar um novo item ao estoque, 
como a data de validade e a quantidade disponível.

___________________________________________________________________________________________________________

Pacote Persistência de Dados
DAO (Data Access Object): responsável por realizar as operações de leitura e gravação dos dados em um 
banco de dados ou arquivo.

ItemDAO: responsável por realizar as operações específicas relacionadas aos itens no estoque, comoadicionar, remover e atualizar os itens.


