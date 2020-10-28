<template>
  <div class="h-screen flex flex-row">

    <!-- Div menú lado izquierdo -->
    <div class="w-20 bg-blue-800 pl-2 pr-2">

      <div class="h-8 w-8 object-contain mt-2 ml-2">
          <img class="w-full h-full" src="./assets/images/logo-icon.png" alt="">
      </div>


      <div class="bg-white w-8 h-8 rounded-full m-2 mt-4">
        <span class="text-xl font-medium text-blue-900 inline-block px-1">AT</span>
      </div>


      <div class="w-8 h-8  m-2 mt-10">
        <img src="./assets/images/desktop.png" alt="">
      </div>

      <div class="w-8 h-8 m-2 mt-6">
        <img src="./assets/images/dinero.png" alt="">
      </div>

      <div class="w-8 h-8 m-2 mt-6">
        <img src="./assets/images/documento.png" alt="">
      </div>

      <div class="w-8 h-8 m-2 mt-6">
        <img src="./assets/images/usuarios.png" alt="">
      </div>

      <div class="w-8 h-8 m-2 mt-6">
        <img src="./assets/images/documentos.png" alt="">
      </div>

      <div class="w-12 h-12 rounded-full m-2 mt-50 border-solid border-2 border-yellow-500">
        <img src="./assets/images/ovni.png" alt="">
      </div>

    </div>


    <!-- Div perfil user  -->
    <div class="w-72">

    <!-- Div Perfil más imagen de documento  -->
      <div class="h-6 mt-6">
        <div class="flex flex-row">
          <div class="w-6 h-8 ml-4">
            <img src="./assets/images/documento-negro.png" alt="">
          </div>
          <div class="w-15 h-6 ml-4">
            <span class="text-sm font-body">Mi Perfil</span>
          </div>
        </div>


      <!-- Div foto de perfil -->
        <div class="h-40 w-40 mt-12 rounded-full border-4 border-gray-500 m-6">
          <img class="p-1" src="./assets/images/ovnig.png" alt="">
        </div>


        <div class="h-10 bg-gray-300 mx-2 mt-16 flex flex-row rounded-lg">
          <div class="w-4 h-6 ml-4 pt-3">
            <img src="./assets/images/usuariop.png" alt="">
          </div>

          <div class="w-15 h-6 ml-4 pt-2">
            <span class="text-xs font-body">Mi Perfil</span>
          </div>
          
        </div>


        <div class="h-10 mx-2 mt-2 flex flex-row rounded-lg">
          <div class="w-4 h-6 ml-4 pt-3">
            <img src="./assets/images/candado.png" alt="">
          </div>

          <div class="w-15 h-6 ml-4 pt-2">
            <span class="text-xs font-body">Cambiar Contraseña</span>
          </div>
          
        </div>



      </div>




      

    </div>


    <!-- Div formulario  -->
    <div class="w-screen bg-gray-200">

      <!-- Div principal que contiene letras de perfil y formulario  -->
      <div class="h-auto flex flex-col m-4">

        <!-- Div principal que contiene letras de Perfil > Mi Perfil -->
        <div class="h-6 flex flex-row">
           <span class="text-sm font-body font-semibold">Perfil</span>
           <span class="text-sm font-body ml-2 text-gray-700"> > MI Perfil</span>
        </div>

        <!-- Div principal que contiene letras de Mi Perfil -->
        <div class="h-8">
          <span class="text-xl font-body">MI PERFIL</span>
        </div>


        <!-- Div principal que contiene el formulario -->
        <div class="h-64 rounded-sm border-2 border-gray-400 bg-white">

      <!-- <el-form  :model="formulario" class="demo-form-inline"> -->
          <!-- Div secundario que contiene el formulario -->
          <div class=" h-56 m-3">

            <!-- Div que contiene el nombre y apellido -->
            <div class="h-24 flex flex-row">

              <div class="w-1/2 flex flex-col mr-5">

              <span class="font-hairline text-gray-600 w-full bg-white">Nombres</span>
              <div class="pt-2">
                <el-input placeholder="René Isaac"  v-model="formula"></el-input>
              </div>
              </div>

              <div class="w-1/2 lex flex-col">
              <span class="font-hairline text-gray-600">Apellidos</span>

              <div class="pt-2">
                <el-input placeholder="Cortez Mata"  v-model="input"></el-input>
              </div>
              </div>
            </div>

            <!-- Div que contiene el correo y perfil -->
            <div class="h-24 flex flex-row">
              <div class="w-2/6 mr-3 flex flex-col">
                <span class="font-hairline text-gray-600">Correo</span>

                <div class="pt-2">
                  <el-input placeholder="isaac.cortez@hotmail.com"  v-model="input"></el-input>
                </div>
              </div>

              <div class="w-2/6 mr-3 flex flex-col">
                <span class="font-hairline text-gray-600">Perfil</span>

                <div class="pt-2">
                  <el-input placeholder="Admin"  v-model="input"></el-input>
                </div>
              </div>
              
              <div class="w-2/6 flex flex-col">
                <span class="font-hairline text-gray-600">Identificador</span>

                <div class="pt-2">
                  <el-input placeholder="isaac.cortez@hotmail.com"  v-model="UHGRTR545"></el-input>
                </div>
              </div>

            </div>

          </div>
          <!-- </el-form> -->
        </div>

      </div>

    </div>

    <div class="w-16 flex flex-col justify-end">

      <div class="w-8 h-8 rounded-full m-2 border-solid">
        <img src="./assets/images/salir.png" alt="">
      </div>
    </div>
  </div>
</template>

<script>

export default {
  
  name: 'App',
  components: {
  }
  
}
</script>
