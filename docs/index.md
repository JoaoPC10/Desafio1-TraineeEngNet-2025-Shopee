<style>

  @import url("https://fonts.googleapis.com/css2?family=Roboto:wght@400;700;900&display=swap");

  :root {

    --jornada-bg: #ffffff; /* Fundo Branco */

    --jornada-text: #000000; /* Texto Preto */

    --jornada-float-animation: float 10s ease-in-out infinite;

    --jornada-fade-in-animation: fadeIn 2s ease-in;

  }


  .md-main {

    background-color: var(--jornada-bg) !important;

  }


  .md-content,

  body {

    background-color: var(--jornada-bg) !important;

    color: var(--jornada-text) !important;

    font-family: "Roboto", sans-serif; 

  }




  .md-main__inner {

    padding-top: 0 !important; 

    margin-top: 0 !important; 
  }



  nav.md-breadcrumbs {



  }




  .md-content h1 {


  }

  

  .background {

    display: flex;

    justify-content: center;

    align-items: center;

    flex-direction: column;

    padding: 100px 20px 50px 20px;

    text-align: center;

  }



  .logo {

    width: 400px; 

    height: auto;

    animation: var(--jornada-float-animation);

  }



  .description {

    margin: 20px auto;

    font-size: 1.5rem;

    max-width: 600px;

    animation: var(--jornada-fade-in-animation);

    color: var(--jornada-text) !important;

  }



  .team, .project-info {

    max-width: 800px;

    margin: 50px auto;

    padding: 20px;

    text-align: left;

    color: var(--jornada-text) !important; 

  }



  .team h1, .project-info h1 {

    margin-bottom: 10px;

    color: #FF6600 !important; 

  }

  

  .team li, .project-info li {

    color: var(--jornada-text) !important; 

  }




  @keyframes float {

    0%, 100% {

      transform: translateY(0);

    }

    50% {

      transform: translateY(-10px);

    }

  }



  @keyframes fadeIn {

    from {

      opacity: 0;

      transform: translateY(30px);

    }

    to {

      opacity: 1;

      transform: translateY(0);

    }

  }

</style>



<div class="background">

  <img src="https://i.postimg.cc/5tD9D620/shopee.png" alt="Logo Shopee" class="logo" />

  <p class="description">

    Documentação da consultoria de software do processo trainee da EngNet do aplicativo <strong>Shopee</strong>

  </p>

</div>


<div class="team" style="max-width: 800px; margin: 50px auto; padding: 20px; text-align: left;">

  <h1 style="color: #FF6600;">✨ Introdução</h1>
  <p style="margin-bottom: 50px;">
    Este repositório foi desenvolvido para documentar o trabalho do processo trainee da EngNet. Nosso projeto consiste em um estudo aprofundado sobre o aplicativo Shopee, com foco na aplicação de técnicas de elicitação, priorização, modelagem e prototipação de requisitos, através da metodologia de engenharia reversa.
  </p>


  <h1 style="color: #FF6600; margin-top: 50px;">🎯 Objetivos</h1>

  <ul>
    <li>Elicitar requisitos com <strong>Observação</strong> e <strong>Introspecção</strong>;</li>
    <li>Priorizar com <strong>MoSCoW</strong> e  <strong>Three Level Scale</strong></li>
    <li>Modelar com <strong> Rich Picture, Casos de Uso, Léxico e Especificação Suplementar</strong> </li>
    <li>Prototipar interfaces principais não implementadas</li>
    <li>Fluxo de Trabalho: <strong>📱 Exploração → 🔍 Elicitação → ⭐ Priorização → 🎨 Modelagem → 🖼️ Prototipação → 📦 Entrega. </strong></li>
  </ul>


  <h2 style="color: #FF6600; margin-top: 50px;">📦 Lista de Entregáveis</h2>

  <ul>
    <li>🔍 Fase 1: Elicitação de Requisitos</li>
    <li>⭐ Fase 2: Priorização de Requisitos</li>
    <li>🎨 Fase 3: Modelagem</li>
    <li>🖼️ Fase 4: Prototipação</li>
  </ul>

<h1 style="color: #FF6600; margin-top: 50px; margin-bottom: 25px;">👥 Membros da Equipe</h1>

  <table>
    <tr>
    <td align="center"><a href="https://github.com/AnnaClarafg"><img src="https://avatars.githubusercontent.com/u/169397157?v=4" width="200px;" alt=""/><br/><sub><b>Ana Clara</b></sub></a><br/>
    <td align="center"><a href="https://github.com/Dev-Gabriel-Lima"><img src="https://avatars.githubusercontent.com/u/156694363?v=4" width="200px;" alt=""/><br /><sub><b>Gabriel</b></sub></a><br />
    <td align="center"><a href="https://github.com/JoaoPC10"><img src="https://avatars.githubusercontent.com/u/104221138?v=4" width="200px;" alt=""/><br /><sub><b>João Igor</b></sub></a><br />
        <td align="center"><a href="https://github.com/luisa12ll"><img src="https://avatars.githubusercontent.com/u/194189725?v=4" width="200px;" alt=""/><br /><sub><b>Luisa de Souza</b></sub></a><br />
    <td align="center"><a href="https://github.com/edumoisessilva"><img src="https://avatars.githubusercontent.com/u/185516590?v=4" width="200px;" alt=""/><br /><sub><b>Moisés</b></sub></a><br />  
  </table>

</div>
</div>