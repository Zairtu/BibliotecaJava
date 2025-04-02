# BibliotecaJava
 Uma simulação de uma biblioteca feita em java utilizando estrutura de dados
Projeto 1: Sistema de gerenciamento de uma biblioteca
Descrição do Projeto:
Você deve desenvolver um sistema de gerenciamento de uma biblioteca que
permita o cadastro de livros, o empréstimo e a devolução de exemplares, além de
manter um histórico de operações. O sistema deve ser eficiente e garantir que as
operações sejam realizadas de forma organizada.
Funcionalidades do Sistema:
1. Cadastro de Livros:
o O sistema deve permitir o cadastro de livros, com informações como
título, autor, ano de publicação e quantidade de exemplares
disponíveis.
o Deve ser possível adicionar, remover e buscar livros.
2. Empréstimo de Livros:
o O sistema deve permitir que usuários realizem empréstimos de livros.
o Cada empréstimo deve ser registrado com o nome do usuário, título
do livro e data de empréstimo.
o Se não houver exemplares disponíveis, o usuário deve ser colocado
em uma fila de espera.
3. Devolução de Livros:
o O sistema deve permitir a devolução de livros.
o Após a devolução, o exemplar deve ser disponibilizado novamente
para empréstimo.
o Se houver usuários na fila de espera, o primeiro da fila deve ser
notificado (ou automaticamente atendido, se possível).
4. Histórico de Operações:
o O sistema deve manter um registro de todas as operações realizadas
(ex: cadastro de livros, empréstimos, devoluções).
o Deve ser possível visualizar o histórico e desfazer a última operação
realizada.
5. Consulta de Disponibilidade:
o O sistema deve permitir consultar a disponibilidade de um livro
(quantidade de exemplares disponíveis).
o Deve ser possível listar todos os livros cadastrados.
Requisitos Técnicos:
1. Armazenamento de Dados:
o Utilize estruturas de dados em memória para armazenar os livros,
empréstimos e fila de espera.
o Escolha estruturas que permitam buscas, inserções e remoções
eficientes.
o Não é permitido o uso de bibliotecas como ArrayList, LinkedList,
Stack, Queue, etc. No entanto, você pode implementar suas
próprias estruturas de dados .
o As classes devem ser organizadas separadamente para representar
as estruturas de dados utilizadas.
2. Gestão de Empréstimos:
o Implemente uma forma de garantir que um livro não seja emprestado
se não houver exemplares disponíveis.
o Utilize uma fila para gerenciar a lista de espera.
3. Histórico de Operações:
o Implemente uma forma de armazenar as operações realizadas,
permitindo que a última operação seja desfeita.
4. Interface do Usuário:
o Crie um menu interativo no terminal para que o usuário possa realizar
as operações de forma simples.
