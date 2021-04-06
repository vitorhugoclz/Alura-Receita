Este projeto foi desenvolvido como aprendizado do curso da Alura sobre introdução ao Django 3

O curso pode ser acessado através do link https://www.alura.com.br/formacao-django

Seu foco foi em aprender os conceitos básicos de Django sobre Urls, View, Template. Além de uma introdução ao ORM dentro do Django para criação de Modelo Entidade.

Neste curso foi desenvolvido um sistema de Receita onde é possível inserir e editar Receitas.

A interface gráfica foi feita com HTML 5, CSS 3.

A pagina inicial do projeto mostra as receitas que estão marcadas para estarem visiveis no banco de dados. As receitas podem ter um foto personalizada como icono, mas se não for adicionada uma foto existe um foto padrão que será icone e outra que será usada para descrição da receita.
![alt text](https://github.com/vitorhugoclz/Alura-Receita/blob/master/FotosGitHub/PaginaInicialNova.png)

A página com os detalhes sobre a receita incluem algumas informações básica sobre uma receita, o banner é a mesma foto que utilizado no icone caso tenha sido adiciona, caso contrário é colocada um foto padrão.

Página de um receita de bolo de teste com foto definida.
![alt text](https://github.com/vitorhugoclz/Alura-Receita/blob/master/FotosGitHub/Receita%20Bolo.png)

Página de uma receita sem foto definida.
![alt text](https://github.com/vitorhugoclz/Alura-Receita/blob/master/FotosGitHub/Pagina%20ComUmaReceita.png)

As novas receitas são geradas através do Django Admin uma ferramenta bastante poderosa que permite fácil acesso as operações de um CRUD.

A página inicial do sistema de Admin para receitas está abaixo
![alt text](https://github.com/vitorhugoclz/Alura-Receita/blob/master/FotosGitHub/Novo%20Admin%20Receita.png)

Através dessa ferramenta é possível editar objetos já inseridos no banco de dados.

![alt text](https://github.com/vitorhugoclz/Alura-Receita/blob/master/FotosGitHub/AdminReceitaEdicao.png)


Também é possível fazer um busca pelo nome de uma receita. Tanto na página inicial quanto na página de Receita
![alt text](https://github.com/vitorhugoclz/Alura-Receita/blob/master/FotosGitHub/Pesquisa%20Bolo.png)
