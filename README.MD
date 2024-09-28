# <center>BlogMba</center>
## � Projeto de um BLOG simples para MBA DEVEXPERTS

## 1)  Objetivos:
- Criar um blog simples para postagem de artigos e coment�rios dos artigos. Somente usu�rios autenticados podem publicar artigos e coment�rios.
- Usu�rios n�o autenticados podem visualizar os artigos e coment�rios.
- O blog deve ter uma interface WEB utilizando o ASPNET MVC CORE e uma API RESTFULL expondo os mesmos recursos do BLOG WEB.

## 2)  Tecnologias:
- ASPNET MVC CORE
- SQL SERVER
- ENTITY FRAMEWORK CORE
- AUTENTICA��O DA API COM JWT
- AUTENTICA��O DO BLOG COM IDENTITY

## 3) Como estou implementando

Seguindo as orienta��es do trabalho, criei 3 projetos :
1 ) BlogMba.Api
2 ) BlogMba.Web
3 ) BlogMba.Data

Meu objetivo � que no projeto BlogMba.Api eu implemente a API RESTFULL, no projeto BlogMba.Web eu implemente a interface WEB e no projeto BlogMba.Data eu implemente o acesso ao banco de dados.
O meu problema hoje, � como compartilhar o acesso a dados, principalmente do Identity entre os outros dois projetos. 
Neste caso o BlogMba.data seria um projeto de class library n�o dependendo de nenhum outro. Mas os outros dois projetos dependem do BlogMba.Data.

Hoje estou subindo uma vers�o do projeto, para uma avalia�ao inicial. Ainda com pouco c�digo.





