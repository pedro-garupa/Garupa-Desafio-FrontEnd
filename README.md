# Garupa - Desafio Frontend

## Criar um blog com painel admin

### Para iniciar:
- Faça um fork desse repositorio.
- Git Clone
- yarn install

### Requisitos:
[ ] Ter página que mostre <b> todas as postagens </b>.

[ ] Ter página para <b> criar postagens  </b> (painel admin).

[ ] Site <b> não pode recarregar  </b>(single page application).

[ ] Ter <b> hover effects  </b> nos cards do blog.

[ ] TextArea <b> não pode ser redimencionada </b>
pelo usuário.

[ ] Formulário deve ser <b> limpo após enviar. </b>

[ ] Na página do Blog os posts deverão ser requisitados ao banco de dados
e utilizar useContext. (https://firebase.google.com/products/realtime-database?gclid=CjwKCAiAmrOBBhA0EiwArn3mfOGXbHcOgOvPIdL1MKOcii_aman4ZJNMbedi7cE9yZWu0HPTsxwD5hoCeCQQAvD_BwE)

[ ] Seguir o <b> design proposto </b>.

#### Utilizar:

[ ] <b> ReactJs (useContext) </b>

[ ] <b> Styled-Components </b>

[ ] <b> Firebase Realtime DataBase </b>

[ ] <b> react-router-dom </b>

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
