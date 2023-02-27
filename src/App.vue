<template>
  
    <!-- NavBar -->
    <nav class="navbar navbar-expand-lg bg-body-tertiary">
  <div class="container-fluid">
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
      <div class="navbar-nav">
        <a class="nav-link active" aria-current="page" href="#">Home</a>
        <a class="nav-link" href="#Contenidos">Contenidos</a>
        <a class="nav-link" href="#apuntes">Apuntes</a>
        <a class="nav-link disabled">Practica</a>
        <a class="nav-link disabled">Tareas</a>
      </div>
    </div>
  </div>
</nav>
    <!-- End Navbar -->
    
    <div class="banner-1">
      <div class="relative w-16 h-16">
          <img
            class="rounded-full border border-gray-75 shadow-sm"
            src="./assets/descarga.jpeg"
            alt="user image"
          />
        </div>
    <div class="flex items-center">
      <div class="w-11/12 space-y-5 md:space-y-10">
        <h3
          class="hello-button text-gray-700 w-fit md:py-3 md:px-5 py-1 px-2 rounded-lg 3xl:text-3xl 2xl:text-xl lg:text-xl md:text-md text-sm font-semibold font-work_sans"
        >
          👋 Hola,
        </h3>
        <h1
          class="display-6"
        >
          Mi nombre es 
          <p class="display-3 pre"> Emerson Isaias Segovia</p>
        </h1>
        <h4 class="fw-bold" style="color:brown;">Estudiante de Ingenieria en Sistemas y redes imformaticas.</h4>
      </div>

      <div class="w-8/12 flex justify-end">
        <img
          class="3x1:h-[500px] 2xl:h-[700px] xl:h-[550px] lg:h-[600px] md:h-[450px] sm:h-[350px]"
          src="./assets/isa.png"
          alt="user image"
        />
      </div>
    </div>
  </div>


  <div class="banner-2 space-y-10 pb-20" id="Contenidos">
    <center><h3 class="heading3 my-5">CONTENIDOS DE LA ASIGNATURA</h3></center>
  <div class="card mb-3" style="max-width: 1500px;">
  <div class="row g-0">
    <div class="col-md-4">
      <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/99/Unofficial_JavaScript_logo_2.svg/1200px-Unofficial_JavaScript_logo_2.svg.png" class="img-fluid rounded-start" alt="...">
    </div>
    <div class="col-md-8">
      <div class="card-body">
        <h5 class="card-title">¿QUE ES JAVASCRIPT?</h5>
        <p class="card-text">•	Un lenguaje de programación. <br> 
          •	Sirve para hacer paginas dinámicas <br>
          •	Se puede usar este lenguaje tanto del lado del cliente como de el servidor. <br>
          •	Es un lenguaje interpretado <br> •	El motor de JavaScript está dentro del código del navegador.
        </p>
        <hr style="height:px;border:none;color:black;background-color:black;" />
        <a href="https://drive.google.com/file/d/1_5kMpGeQ-lctsboTBH3LsuInWbosmeK2/view?usp=sharing" 
        class="btn btn-primary stretched-link">Contenido</a>
        <p class="card-text"><small class="text-muted">Semana 1 del 16 al 22 de enero</small></p>
      </div>
    </div>
  </div>
</div>
<div class="card mb-3" style="max-width: 1500px;">
  <div class="row g-0">
    <div class="col-md-4">
      <img src="https://vuejs.org/images/logo.png" class="img-fluid rounded-start" alt="...">
    </div>
    <div class="col-md-8">
      <div class="card-body">
        <h5 class="card-title">Bootstrap</h5>
        <p class="card-text">•	¿Qué es Bootstrap?  Bootstrap es un marco de desarrollo web que ayuda 
          a los desarrolladores a crear interfaces web.
          <hr style="height:1px;border:none;color:black;background-color:black;" />
          <h5 class="card-title">vue js</h5>•	¿Qué es VueJS?
          Es un marco progresivo para construir interfaces de
          usuario. A diferencia de otros marcos monolíticos, Vue
          está diseñado desde cero para ser adoptable de forma
          incremental.
        </p>
        <hr style="height:1px;border:none;color:black;background-color:black;" />
        <a href="https://drive.google.com/file/d/1KbQOvLSxguWEXZ3nwVdnSUy5dz7aByAz/view?usp=sharing" 
        class="btn btn-primary stretched-link">Contenido</a>
        <p class="card-text"><small class="text-muted">Semana 2 del 23 al 29 de enero</small></p>
      </div>
    </div>
  </div>
</div>
<div class="card mb-3" style="max-width: 1500px;">
  <div class="row g-0">
    <div class="col-md-4">
      <img src="https://www.nextu.com/wp-content/uploads/2021/11/2-2.png" class="img-fluid rounded-start" alt="...">
    </div>
    <div class="col-md-8">
      <div class="card-body">
        <h5 class="card-title">Rendering y directivas</h5>
        <p class="card-text">•	El rendering es una opción que propone VueJS para interactuar con el DOM, para lo cual se tendría: <br>
          • Vista: HTML <br>• Estado: Datos JS <br>• Usuario: Interactúa e introduce cambios en la vista.
          <h5 class="card-title">Directivas</h5>
          <hr style="height:1px;border:none;color:black;background-color:black;" />
          <p class="card-text">•	Las directivas de Vue son atributos especiales que se colocan en las etiquetas HTML y están prefijados
          por v-, como por ejemplo, v-for,
          </p> 
        </p>
        <hr style="height:1px;border:none;color:black;background-color:black;" />
        <a href="https://drive.google.com/file/d/1xOBgTMBnVaTg5BYLAEmmgMbcmcHlT4zp/view?usp=sharing" 
        class="btn btn-primary stretched-link">Contenido</a>
        <p class="card-text"><small class="text-muted">Semana 3 del 30 de enero al 05 de febrerp</small></p>
      </div>
    </div>
  </div>
</div>
<div class="card mb-3" style="max-width: 1500px;">
  <div class="row g-0">
    <div class="col-md-4">
      <img src="https://preview.redd.it/r2qp14woir961.png?width=785&format=png&auto=webp&s=d4ee735b991911761b8517cf992c0e4c0763269d" class="img-fluid rounded-start" alt="700">
    </div>
    <div class="col-md-8">
      <div class="card-body">
        <h5 class="card-title">Eventos y Clases</h5>
        <h5 class="card-title">¿Qué son los eventos?</h5>
        <p class="card-text">	Un evento es una acción del usuario ante la cual puede realizarse 
          algún proceso (por ejemplo, el cambio del valor de un formulario, o la pulsación de un enlace).
        </p>
        <hr style="height:1px;border:none;color:black;background-color:black;" />
        <a href= "https://drive.google.com/file/d/1iNWB6qADWZNEsEPGzBfQ2LF9IOpsdbWe/view?usp=sharing"
        class="btn btn-primary stretched-link">Contenido</a>
        <p class="card-text"><small class="text-muted">Semana 4 del 06 al 12 de febrero</small></p>
      </div>
    </div>
  </div>
</div>
<div class="card mb-3" style="max-width: 1500px;">
  <div class="row g-0">
    <div class="col-md-4">
      <img src="https://vuejsbr-docs-next.netlify.app/images/components_provide.png" class="img-fluid rounded-start" alt="700">
    </div>
    <div class="col-md-8">
      <div class="card-body">
        <h5 class="card-title">Componentes</h5>
        <p class="card-text">Un componente en Vue.js es la forma de reutilizar una instancia de Vue 
        tantas veces como sea necesario.
        Mediante los componentes se pueden crear elementos propios html, cada uno con sus propiedades y
        métodos particulares que fácilmente se pueden reutilizar en toda la aplicación.
        </p>
        <hr style="height:1px;border:none;color:black;background-color:black;" />
        <a href= "https://drive.google.com/file/d/1nqRhAOCCyEbSRwYNqZKG1y54_gsE9CmC/view?usp=sharing"
        class="btn btn-primary stretched-link">Contenido</a>
        <p class="card-text"><small class="text-muted">Semana 5 del 13 al 19 de febrero</small></p>
      </div>
    </div>
  </div>
</div>
    </div>

  <div class="banner-1" id="apuntes">
    <div class="space-y-4 grid place-items-center mt-5">
      <h3 class="heading3">APUNTES</h3>
      <center><p class="font-work_sans text-gray-600 font-semibold leading-relaxed">
        De acuerdo a las clases impartidas se han tomado los siguientes apuntes como agregados a fortalecer
        los conocimientos requeridos para trabajar con el Frenwork de Vue js.
      </p></center>
    </div>
    <div class="card bg-dark ">
  <img src="./assets/apuntes.png" class="card-img" alt="...">
</div>
  </div>

  <div class="banner-2 md:flex items-center md:justify-evenly" id="about">
    <img
      class="md:h-[500px] h-[400px]"
      src="https://www.oomnitza.com/wp-content/uploads/2022/06/github-logo-300x300.png"
      alt="user image"
    />
    <div class="space-y-5 py-8 px-8 md:py-16 md:px-20 md:w-1/2">
      <h4 class="heading3 my-5" >Conocimientos</h4>
      <p class="heading4 font-work_sans ">
        Los contenidos que hasta el momento han sido impartidos he aprendido el uso basico de 
        JavaScript, Html5, y Bootstra haciendo uso del Frenwork de Vue js 3, de la misma forma hemos aprendido 
        las buenas practicas de la programacion.
        <br />
        El enfoque de programacion 4 es el dearrollo web, trabajar del lado del cliente y servidor, 
        y la formacion nos encamina a conocer mas a fondo los principales lenguajes que son fuerte en el desarrollo web.
      </p>
      <div>
      <a href="https://github.com/isaias04/Practicas-de-progra.git" 
      class="btn btn-success stretched-link"> Practicas</a>
      <a href="https://github.com/Uvense/PROGRA4.git" 
      class="btn btn-warning stretched-link">Laboratorio1</a>
    </div>
    </div>
  </div>


</template>
<script>

  export default {
    data() {
      return {
        showMenu: false,
        
      }
      
    },
    
  }
</script>
