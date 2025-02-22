<h1 align="center"> Site de Notícias 📰 </h1>
Este é um pequeno projeto seguindo o curso de Symfony que estou fazendo. Aqui podemos ver a página principal do site de notícias:
<br>
<img width="1453" alt="jornal" src="https://github.com/user-attachments/assets/05f5fc09-a910-44dd-b7a6-4defc898afa4" />
<hr>
Nesse projeto eu utilizo templates do Bootstrap, e renderizo o front utilizando a ferramenta TWIG, do próprio Symfony. Veja como faço um
laço de repetição, por exemplo, trazendo as informações do backend (o TWIG possui sua própria sintaxe 😎): 
<br><br>
<img width="690" alt="categorytwig" src="https://github.com/user-attachments/assets/26ca377b-110f-48cc-a78f-38449cc1db2b" />
<br><br>
As informações com o nome de 'text' são trazidas de dentro da variável chamada 'categories', que na verdade é um array dentro do Controller:
<br><br>
<img width="1175" alt="jornal2" src="https://github.com/user-attachments/assets/881f6982-5f02-49e8-8d79-346ee8a177a5" />
<hr>
<br><br>
Dessa maneira, conseguimos organizar bem os arquivos do nosso projeto, separando a "lógica" da visualização. O Symfony 
é incrível! Vejamos como ficou o exemplo dentro das categorias de notícias: 
<br><br>
<img width="1447" alt="category" src="https://github.com/user-attachments/assets/d77b5753-f179-45fb-9970-86e8c2d0acd6" />




