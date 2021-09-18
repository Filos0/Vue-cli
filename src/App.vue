<template>
  <div class="container">
    <h1 class="text-center">Tabla de Usuarios</h1>
    <table class="table table-striped" id="tabla">
      <thead>
        <tr>
          <th scope="col">#</th>
          <th scope="col">Nombre</th>
          <th scope="col">Apellido</th>
          <th scope="col">RUN</th>
          <th scope="col">Fecha de nacimiento</th>
          <th scope="col">Edad</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>{{ usuarios[0].id }}</td>
          <td>{{ usuarios[0].nombre }}</td>
          <td>{{ usuarios[0].apellido }}</td>
          <td>{{ usuarios[0].run }}</td>
          <td>{{ usuarios[0].nacimiento }}</td>
          <td>{{ usuarios[0].edad }}</td>
        </tr>
        <tr>
          <td>{{ usuarios[1].id }}</td>
          <td>{{ usuarios[1].nombre }}</td>
          <td>{{ usuarios[1].apellido }}</td>
          <td>{{ usuarios[1].run }}</td>
          <td>{{ usuarios[1].nacimiento }}</td>
          <td>{{ usuarios[1].edad }}</td>
        </tr>
        <tr>
          <td>{{ usuarios[2].id }}</td>
          <td>{{ usuarios[2].nombre }}</td>
          <td>{{ usuarios[2].apellido }}</td>
          <td>{{ usuarios[2].run }}</td>
          <td>{{ usuarios[2].nacimiento }}</td>
          <td>{{ usuarios[2].edad }}</td>
        </tr>
      </tbody>
    </table>
  </div>
</template>

<script>
export default {
  name: "App",
  data: () => ({
    usuarios: [
      {
        id: 1,
        nombre: "José",
        apellido: "Pérez",
        run: "123456-8",
        nacimiento: "12/03/1989",
        edad: 32,
      },
      {
        id: 2,
        nombre: "María",
        apellido: "Rodriguez",
        run: "654321-8",
        nacimiento: "30-11-90",
        edad: 29,
      },
      {
        id: 3,
        nombre: "Manuel",
        apellido: "Patiño",
        run: "14558522222-8",
        nacimiento: "01/10//1989",
        edad: 32,
      },
    ],
  }),
};
</script>

<style></style>
