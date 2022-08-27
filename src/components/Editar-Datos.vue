<template>
    <div class="container">
    <div class="card">
      <div class="card-header">
        Editar Encuestado (a)
      </div>
      <div class="card-body">
        <form v-on:submit.prevent="actualizarRegistro">
            <div class="form-group">
                <label for="">Correo: </label>
                <input type="email"
                class="form-control" required name="correo" id="correo" v-model="e.correo" aria-describedby="helpId" placeholder="">
                <small id="helpId" class="form-text text-muted">Ingresa tu correo</small>
                <br>
                
            </div>
            <div class="form-group">
                <label for="">Edad: </label><br>
                <select>
                <option>18-25</option>
                <option>26-33</option>
                <option>34-40</option>
                <option>40 +</option>
                <input type="select"
                class="form-control" required name="edad" id="edad" v-model="e.edad" aria-describedby="helpId" placeholder="">
                <small id="helpId" class="form-text text-muted">Selecciona tu edad</small>
                </select>
            </div>
            <br>  
            <div class="form-group">
                <label for="">Sexo: </label><br>
                <select >
                <option>M</option>
                <option>F</option>
                <input type="select"
                class="form-control" required name="sexo" id="sexo" v-model="e.sexo" aria-describedby="helpId" placeholder="">
                <small id="helpId" class="form-text text-muted"></small>
                </select>
            </div>
            <br>
            <div class="form-group">
                <label for="">Red Social Favorita: </label>
                <input type="text"
                class="form-control" required name="rsf" id="rsf" v-model="e.rsf" aria-describedby="helpId" placeholder="Facebook, Twitter, Instagram, Whatsapp, TikTok">
                <small id="helpId" class="form-text text-muted"></small>
                <br>
                
            </div>
            <div class="form-group">
                <label for="">Tiempo promedio al día en Facebook</label>
                <input type="text"
                class="form-control" required name="tpf" id="tpf" v-model="e.tpf" aria-describedby="helpId" placeholder="">
                <small id="helpId" class="form-text text-muted"></small>
                <br>
                
            </div>
            <div class="form-group">
                <label for="">Tiempo promedio al día en Twitter</label>
                <input type="text"
                class="form-control" required name="tpt" id="tpt" v-model="e.tpt" aria-describedby="helpId" placeholder="">
                <small id="helpId" class="form-text text-muted"></small>
                <br>
                
            </div>
            <div class="form-group">
                <label for="">Tiempo promedio al día en Instagram</label>
                <input type="text"
                class="form-control" required name="tpi" id="tpi" v-model="e.tpi" aria-describedby="helpId" placeholder="">
                <small id="helpId" class="form-text text-muted"></small>
                <br>
            </div>
            <div class="form-group">
                <label for="">Tiempo promedio al día en Whatsapp</label>
                <input type="text"
                class="form-control" required name="tpw" id="tpw" v-model="e.tpw" aria-describedby="helpId" placeholder="">
                <small id="helpId" class="form-text text-muted"></small>
                <br>
            </div>
            <div class="form-group">
                <label for="">Tiempo promedio al día en TikTok</label>
                <input type="text"
                class="form-control" required name="tpk" id="tpk" v-model="e.tpk" aria-describedby="helpId" placeholder="">
                <small id="helpId" class="form-text text-muted"></small>
                <br>
            </div>

            <div class="btn-group" role="group" aria-label="">
                <button type="submit" class="btn btn-success">Modificar</button>
                <router-link to="/listar" class="btn btn-warning" >Cancelar</router-link>

                
                
            </div>
            
            
            

        </form>

      </div>

    </div>

    </div>
</template>

<script>
export default {
        data(){
        return{
            e:{}
        }

    },
    
}
</script>