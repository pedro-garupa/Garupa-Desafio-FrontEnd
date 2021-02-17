# Garupa - Desafio Frontend

## Criar um blog com painel admin

### Requisitos:
- Ter página que mostre todas as postagens.
- Ter página para criar postagens (painel admin).
- Site não pode recarregar (single page application).
- Ter hover effects nos cards do blog.
- TextArea não pode ser redimencionada
pelo usuário.
- Formulário deve ser limpo após enviar.
- Na página do Blog os posts deverão ser requisitados ao banco de dados
e utilizar useContext. (https://firebase.google.com/products/realtime-database?gclid=CjwKCAiAmrOBBhA0EiwArn3mfOGXbHcOgOvPIdL1MKOcii_aman4ZJNMbedi7cE9yZWu0HPTsxwD5hoCeCQQAvD_BwE)
- Seguir o design proposto.
#### Utilizar:
- ReactJs (useContext)
- Styled-Components
- Firebase Realtime DataBase
- react-router-dom

### UI
https://www.figma.com/file/EkXrEhsno644EvGgNWuAfd/Desafio---FrontEnd---Garupa?node-id=0%3A1

### Páginas

#### Painel admin - Criador de postagens => Rota “/admin”
Formulário para postagem com:
- Título
- Subtítulo
- Parágrafo 
- Data

#### Página do Blog => Rota “/”
- Mostrar postagens
- Se não tiver postagens mostrar mensagem avisando
- Loading enquanto não aparecer as postagens
