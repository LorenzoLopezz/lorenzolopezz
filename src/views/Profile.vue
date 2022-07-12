<template>
  <main>
    <Header />
    <section class="hero">
      <div class="hero-presentation">
        <h1>Lorenzo López</h1>
        <h3>Desarrollador Web - Frontend & Backend</h3>
        <a href="https://wa.me/50370338902?text=Hola Lorenzo" target="blank_"><button class="action-btn"><v-icon color="white">mdi-whatsapp</v-icon> ¡Contácteme!</button></a>
        <br>
        <a href="www.linkedin.com/in/lorenzolopezz" target="blank_"><v-icon color="white">mdi-linkedin</v-icon> Linkedin</a>
        <a href="https://github.com/LorenzoLopezz" style="margin-left: 15px;" target="blank_"><v-icon color="white">mdi-github</v-icon> GitHub</a>
      </div>
      <div class="hero-photo">
        <img src="./../assets/images/profile.jpeg" alt="Profile picture">
      </div>
    </section>

    <section class="aboutme" id="aboutme">
      <h1>SOBRE MÍ</h1>
      <p>Soy Lorenzo López, desarrollador web con <b>casi 3 años de experiencia en área profesional y otros 3 años de manera independiente</b> en el área y a solo un semestre de culminar mis estudios universitarios en <b>Ingenierá en Ciencias de la Computación.</b></p>
      <p>Apasionado por la informática y la programación incursioné a los 15 años en el mundo mágico de la tecnología y desde ese momento no dejo de autoeducarme para aprender sobre las diferentes tecnologías que salen al mercado.</p>
      <p>Mi mayor fuerte es el <b>desarrollo Backed PHP (Codeigniter, Laravel, Symfony)</b> y <b>desarrollo Frontend con Vue JS</b>, así también manejo Node JS y diferentes bases de datos como lo son: <b>MySQL, PostgreSQL y SQLServer</b>.</p>
      <p>Actualmente me encuentro estudiando a fondo la tecnología de <b>Node JS y React JS</b>.</p>
    </section>

    <section class="habilities" id="habilities">
      <h1>HABILIDADES</h1>
      <v-row>
        <v-col cols="12" md="4" lg="3">
        <h3>Tecnologías web</h3>
        <ul>
          <li>HTML 5</li>
          <li>
          CSS
            <ul>
              <li>Tailwind CSS</li>
              <li>Bootstrap</li>
              <li>Materialize</li>
            </ul>
          </li>
          <li>
          PHP 5 - 7
          <ul>
            <li>Symfony</li>
            <li>Codeigniter</li>
            <li>Laravel</li>
          </ul>
          </li>
          <li>
          JavaScript avanzado
          <ul>
            <li>Vue JS</li>
            <li>Node JS</li>
            <li>React JS</li>
          </ul>
          </li>
        </ul>
        </v-col>
        <v-col cols="12" md="4" lg="3">
        <h3>Bases de datos</h3>
        <ul>
          <li>MySQL</li>
          <li>PostgreSQL</li>
          <li>SQL Server</li>
          <li>SQLite</li>
        </ul>
        </v-col>
        <v-col cols="12" md="4" lg="3">
        <h3>Productividad y organización</h3>
        <ul>
          <li>Metodologías ágiles</li>
          <li>Git, Github y Gitlab</li>
          <li>Docker</li>
        </ul>
        </v-col>
        <v-col cols="12" md="4" lg="3">
        <h3>Otras áreas</h3>
        <ul>
          <li>UX</li>
          <li>UI</li>
          <li>Figma</li>
          <li>Adobe Photoshop, Adobe Illustrator</li>
        </ul>
        </v-col>
        <v-col cols="12" md="4" lg="3">
        <h3>Habilidades blandas</h3>
        <ul>
          <li>Responsable</li>
          <li>Eficiente con las deadlines</li>
          <li>Trabajo en equipo</li>
          <li>Liderazgo</li>
          <li>Capacidad de comunicación y toma de requerimientos</li>
          <li>Ético</li>
          <li>Profesional</li>
        </ul>
        </v-col>
      </v-row>
    </section>

    <section class="experiences" id="experiences">
      <h1>Experiencias</h1>
      <v-row>
        <v-col cols="12" md="6" lg="6">
          <div class="experiencies-card">
            <h3>Ministerio de Salud de El Salvador</h3>
            <p class="text-muted">Octubre 2021 - Actualmente</p>
            <p class="text-justify">Me encargo del desarrollo de nuevos módulos para software usado a nivel nacional en tecnologías como Symfony 2, Symfony 5, Node Js y Vue Js, usando bases de datos PostgreSQL, tomando en cuenta requerimientos establecidos haciendo uso también de metodologías ágiles versionamiento y dockerización de contenedores para los diferentes ambientes utilizados. Desarrollo de API REST para conexión con servicios externos. Así también me dedico al mantenimiento y rediseño de módulos ya implementados buscando generar procesos eficaces y eficientes que disminuyan los tiempos de carga y ayuden al personal a realizar su trabajo de la manera más rápida y con la menor o ninguna inconsistencia.</p>
          </div>
        </v-col>
        <v-col cols="12" md="6" lg="6">
          <div class="experiencies-card">
            <h3>Conta Smart S.A. de C.V.</h3>
            <p class="text-muted">Febrero 2020 – octubre 2021</p>
            <p class="text-justify">En Conta Smart S.A. de C.V. me encargué de desarrollar nuevas funcionalidades que aporten ventajas competitivas en el mercado, generen una buena experiencia y sea fácil de usar para el usuario, además es importante que el código que escriba sea fácil de comprender, se encuentre documentado y sea actualizable. Otra de las asignaciones fue brindar capacitación y soporte de funciones previamente desarrolladas. Tuve funciones en el área administrativa, siendo mi persona el desarrollador del software administrativo para generación de estadísticas sobre ventas, clientes, entre otras funciones. Creación de API REST para diferentes aplicaciones.</p>
          </div>
        </v-col>
      </v-row>
    </section>

    <section class="contacatme" id="#contactme">
      <a href="https://wa.me/50370338902?text=Hola Lorenzo" target="blank_"><button class="action-btn"><v-icon color="white">mdi-whatsapp</v-icon> ¡Contácteme!</button></a>
      <p style="margin-top: 30px; color: white;">Esta web ha sido desarrollada por Lorenzo López con Vue JS</p>
      <a href="www.linkedin.com/in/lorenzolopezz" target="blank_"><v-icon color="white">mdi-linkedin</v-icon> Linkedin</a>
      <a href="https://github.com/LorenzoLopezz" style="margin-left: 15px;" target="blank_"><v-icon color="white">mdi-github</v-icon> GitHub</a>
    </section>
  </main>
</template>

<style scoped>
a {
  text-decoration: none;
  color: white !important;
}
a:hover {
  color: #1976d2 !important;
  transition: all 0.3s ease-in-out;
}
.hero {
  display: flex;
  flex-wrap: wrap;
  min-height: 50vh;
  align-items: center;
  padding: 120px 150px;
  justify-content: space-between;
  background: linear-gradient(96.19deg, #47DEB1 13.54%, rgba(61, 199, 243, 0.689896) 48.96%, rgba(0, 112, 216, 0.79) 84.38%);
}
.hero h1 {
  font-size: 3rem;
}
.hero h3 {
  font-size: 1.5rem;
  color: #C5FFFF;
}
.hero button {
  width: 50%;
  padding: 20px;
  color: white;
  border-radius: 35px;
  background: #0097EC;
  margin: 40px 0 20px 0;
}
.hero-presentation {
  order: 1;
}
.hero-photo {
  order: 2;
}
.hero-photo img {
  width: 350px;
  height: 350px;
  border-radius: 50%;
}
.aboutme {
  margin: 30px 0;
  padding: 20px 30vh;
  text-align: center;
}
.habilities {
  margin: 30px 0;
  padding: 20px 30vh;
  background: #f2f2f2;
}
.habilities h1 {
  text-align: center;
}
.habilities li {
  display: block;
}
.experiences {
  margin: 30px 0;
  padding: 20px 30vh;
}
.experiences h1 {
  text-align: center;
}
.contacatme {
  margin: 30px 0 0 0;
  padding: 40px 0;
  text-align: center;
  background: #0097EC;
}
.contacatme button {
  width: 50%;
  padding: 20px;
  color: white;
  border-radius: 35px;
  background: #47DEB1;
}

@media (max-width: 640px) {
  .hero {
    min-height: auto;
    padding: 120px 20px;
    justify-content: center;
  }
  .hero-presentation {
    order: 2;
    text-align: center;
  }
  .hero-photo {
    order: 1;
    text-align: center;
  }
  .aboutme {
    margin: 30px 0;
    padding: 20px;
    text-align: center;
  }
  .habilities {
    margin: 30px 0;
    padding: 20px;
    background: #47DEB1;
  }
  .experiences {
    padding: 20px;
  }
}

@media (min-width: 640px) and (max-width: 980px) {
  .hero {
    min-height: auto;
    padding: 120px 20px;
    justify-content: center;
  }
  .hero-presentation {
    order: 2;
    text-align: center;
  }
  .hero-photo {
    order: 1;
    text-align: center;
  }
  .aboutme {
    margin: 30px 0;
    padding: 20px 100px;
    text-align: center;
  }
  .habilities {
    margin: 30px 0;
    padding: 20px 100px;
    background: #47DEB1;
  }
  .experiences {
    padding: 20px;
  }
}
</style>

<script>
import Header from './Header.vue'

export default {
  name: 'Profile',
  components: { Header }
}
</script>
