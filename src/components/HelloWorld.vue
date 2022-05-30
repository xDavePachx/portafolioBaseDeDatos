<template>
  <div class="hello" align="center">
    <div align="center">
      <h1>Estudiante:</h1>
      <h1>Anderson David Pacheco Medrano</h1>
      <h2>
        Portafolio de segundo y tercer computo | Administracion de base de datos
        2
      </h2>
      <br />
    </div>
    <div id="apartado1">
      <h2>Introduccion</h2>
      <p>
        Mi nombre es: Anderson David Pacheco Medrano y este es mi portafolio,
        por este medio se espera dejar constancia de las actividades, proyectos
        y temas recibidos en este computo, de forma que se vea el avance que se
        a logrado y el nivel de conocimiento que se a alcanzado a la fecha,
        tambien resumir contenidos resaltando lo mas importante de cada tema
        impartido por la ingeniera.
      </p>
      <br />
      <br />
      <h4>Temas impartidos en el segundo computo</h4>
      <ol>
        <li># Generalidades de la seguridad de los datos</li>
        <br />
        <li># Amenazas, riesgos y vulnerabilidades de las bases de datos</li>
        <br />
        <li># Normas ISO para la seguridad de los datos</li>
        <br />
        <li># Plan de seguridad de los datos basado en ISO 27001</li>
        <br />
        <li># Seguridad de las bases de datos, en entornos locales</li>
      </ol>
      <br />
      <br />

      <h4>Temas impartidos en el tercer computo</h4>
      <ol>
        <li>$ Almacen de datos</li>
        <br />
        <li>$ ETL</li>
        <br />
        <li>$ Cubos OLAP</li>
        <br />
        <li>$ Introduccion a la mineria de datos</li>
        <br />
        <li>$ Herramientas para la mineria de datos</li>
        <br />
        <li>$ Herramientas para la mineria de datos II</li>
      </ol>
      <br />
      <br />
      <h4>Objetivos academicos</h4>

      <p>
        Desde el momento en que empece a estudiar esta carrera, mi proposito a
        sido desarrollar conocimientos importantes en cada area de mi carrera,
        en este caso para la materia de "Bases de datos" y pues con ayuda de la
        ingeniera que nos imparte clases y temas super interesantes, se que
        lograre estos objetivos, vale recalcar que cada clase me motiva a seguir
        mejorando porque siempre hay un nuevo reto que superar y eso me mantiene
        activo ya sean bases de datos como tal o hasta la creacion de planes de
        seguridad.
      </p>
      <br />
      <br />
      <h4>Competencias adquiridas en el segundo computo</h4>
      <ol>
        <li>
          --> Conocimientos sobre creacion de planes de seguridad basados en las
          normas ISO27001 y ISO27002
        </li>
        <br />
        <li>--> Aplicacion de familia de normas ISO27000</li>
        <br />
        <li>--> Creacion de bases de datos no-SQL</li>
      </ol>
      <br />

      <h4>Competencias adquiridas en el tercer computo</h4>
      <ol>
        <li>--> Estructuras logicas de almacenes de datos.</li>
        <br />
        <li>--> Procesos ETL y herramientas para data warehouses.</li>
        <br />
        <li>--> Uso y características de los cubos OLAP</li>
        <br />
        <li>--> Introduccion a la mineria de datos</li>
        <br />
        <li>--> El uso de herramientas para la mineria de datos</li>
      </ol>
      <br />
      <h4>Temas dificiles</h4>
      <p>
        En este computo, no hubieron retos complicados de superar quiza si
        trabajos que requerian de tiempo para lograr terminarlos con exito y un
        poco de constansia, realmente no hubieron muchos problemas o retrasos en
        este computo.
      </p>
      <br />
      <br />
      <br />
      <br />
    </div>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
#apartado1 {
  border:3px solid brown;
   border-radius:22px;
   width: 70rem;
}
.hello {
  background-color: #abbaea;
}
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
