# Social-tree

![social-trre (4)](https://user-images.githubusercontent.com/126616878/222877427-d33b8300-297c-4c5a-acf7-33f21ab2c99e.png)

<!DOCTYPE html>
<html>
  <head>
    <meta charset="UTF-8">
    <title>Social Tree</title>
    <link href="https://fonts.googleapis.com/css?family=Poppins:400,500,600&display=swap" rel="stylesheet">
    <style>
      /* Variáveis de cor */
      :root {
        --white: #FFFFFF;
        --purple: #6F48C9;
      }
      
      /* Resetando margens, preenchimentos e dimensionamentos */
      * {
        margin: 0;
        padding: 0;
        box-sizing: border-box;
      }
      
      /* Estilizando globalmente */
      body {
        background: var(--white);
        font-family: 'Poppins', sans-serif;
      }
      
      /* Estilos para o avatar */
      .profile-img {
        width: 120px;
        height: 120px;
        border-radius: 50%;
        margin-top: 50px;
      }
      
      /* Estilos para o nome de usuário */
      .profile-name {
        font-size: 36px;
        font-weight: 600;
        color: var(--purple);
        margin-top: 20px;
      }
      
      /* Estilos para links */
      .profile-links {
        margin-top: 40px;
      }
      
      .profile-links a {
        display: inline-block;
        margin-right: 20px;
        text-decoration: none;
        color: var(--purple);
      }
      
      .profile-links a:hover {
        text-decoration: underline;
      }
      
      /* Estilos para ícones de mídia social */
      .profile-links i {
        font-size: 24px;
      }
      
      .profile-links .fa-github {
        color: #333;
      }
      
      .profile-links .fa-twitter {
        color: #1DA1F2;
      }
      
      .profile-links .fa-linkedin {
        color: #0077B5;
      }
    </style>
  </head>
  
  <body>
    <div class="profile">
      <img src="https://avatars.githubusercontent.com/u/1234567?v=4" alt="Avatar" class="profile-img">
      <h1 class="profile-name">Seu Nome Aqui</h1>
      <div class="profile-links">
        <a href="https://github.com/seunomeaqui" target="_blank"><i class="fab fa-github"></i></a>
        <a href="https://twitter.com/seunomeaqui" target="_blank"><i class="fab fa-twitter"></i></a>
        <a href="https://www.linkedin.com/in/seunomeaqui" target="_blank"><i class="fab fa-linkedin"></i></a>
      </div>
    </div>
  </body>
</html>

