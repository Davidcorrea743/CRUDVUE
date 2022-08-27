<template>
    <div class="container">

        <div class="card">
        <div class="card-header">
            Datos Encuestas
      </div>
            <div class="card-body">
    <table class="table">
      <thead>
        <tr>
          <th>ID</th>
          <th>Correo</th>
          <th>Edad</th>
          <th>Sexo</th>
          <th>Red Social Favorita</th>
          <th>Tiempo promedio al día en Facebook</th>
          <th>Tiempo promedio al día en WhatsApp</th>
          <th>Tiempo promedio al día en Instagram</th>
          <th>Tiempo promedio al día en Twitter</th>
          <th>Tiempo promedio al día en TikTok</th>
          <th>Acciones</th>
        </tr>
      </thead>
      <tbody>
        <tr>    
          <td></td>
          <td></td>
          <td></td>
          <td></td>
          <td></td>
          <td></td>
          <td></td>
          <td></td>
          <td></td>
          <td></td>
          <td>
            
            <div class="btn-group" role="group" aria-label="">
                
                <router-link to="/editar" class="btn btn-info" >Editar</router-link>
                <button type="button" class="btn btn-danger">Borrar</button>
            </div>
          </td>


        </tr>
      </tbody>
    </table>
            </div>

        </div>


    </div>
</template>

<script>
export default {
    data(){
        return{

        }
    }
}
</script>