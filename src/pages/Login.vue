<template>
  <q-page>
	<div class="row justify-center">
      <div class="col-12 col-md-8">
        
      </div>
      <div class="col-12 col-md-auto">
       
      </div>

      <div class="col-12 col-md-3">
        <div class="grid-3">

         <div class="column" style="height: 100vh">
          <div class="col-12 col-md-7"></div>
          <div class="col ">
             
              <div class="column items-center"  >
                   <q-input color="white" label="Username" label-color="white">
                     <template v-slot:prepend>
                        <q-icon name="mdi-account" class="text-white" />
                   </template>
                  </q-input>
                 
                   <q-input color="white" label="Password" label-color="white" type="password">
                     <template v-slot:prepend>
                        <q-icon name="mdi-lock" class="text-white" />
                   </template>
                  </q-input>
   					 <q-btn flat style="background:white" label="Login" color="blue"/>

					<div>
						
					</div>
                 </div>

          </div>
        </div>

      </div>
    
      </div>
    </div>
  </q-page>
</template>

<script>
export default {

}
</script>

<style lang="sass">
.grid-3
	background: $blue
	height: 100vh
.q-field__native
	color: white
	width: 13vw
.q-btn
	margin-top:40px
	width: 15vw
</style>