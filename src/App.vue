<script setup>
// No script needed for static content
</script>

<template>
  <div id="app">
    <header>
      <h1>Diseño de Planos y Modelos 3D</h1>
      <p>Especialistas en creación de planos arquitectónicos y modelos tridimensionales</p>
    </header>

    <main>
      <section id="servicios">
        <h2>Nuestros Servicios</h2>
        <div class="servicio">
          <h3>Diseño de Planos</h3>
          <p>Creación de planos detallados para proyectos de construcción, remodelación y diseño interior.</p>
        </div>
        <div class="servicio">
          <h3>Modelos 3D</h3>
          <p>Desarrollo de modelos tridimensionales realistas para visualización y presentación de proyectos.</p>
        </div>
        <div class="servicio">
          <h3>Consultoría</h3>
          <p>Asesoramiento profesional en diseño y planificación de espacios.</p>
        </div>
      </section>

      <section id="contacto">
        <h2>Contacto</h2>
        <p>¿Interesado en nuestros servicios? Contáctanos para discutir tu proyecto.</p>
        <p>Email: info@disenoplanos3d.com</p>
        <p>Teléfono: +123 456 7890</p>
      </section>
    </main>

    <footer>
      <p>&copy; 2024 Diseño de Planos y Modelos 3D. Todos los derechos reservados.</p>
    </footer>
  </div>
</template>

<style scoped>
#app {
  font-family: Arial, sans-serif;
  max-width: 800px;
  margin: 0 auto;
  padding: 20px;
}

header {
  text-align: center;
  margin-bottom: 40px;
}

h1 {
  color: #333;
}

h2 {
  color: #555;
  border-bottom: 2px solid #ddd;
  padding-bottom: 10px;
}

.servicio {
  margin-bottom: 20px;
  padding: 15px;
  border: 1px solid #eee;
  border-radius: 5px;
}

footer {
  text-align: center;
  margin-top: 40px;
  color: #777;
}
</style>
