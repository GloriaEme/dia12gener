<template>
    <v-row>
        <v-col>
          <h2> MASCOTAS</h2>
            <v-list>

            </v-list-item v-for="mascota in mascotas">
            {{ mascota.nombre }} - {{ mascota.edat }} - {{ mascota.especie }}
        </v-col>
        <v-col>
          <h2> ACCIONS</h2>
          <v-btn v-on ordenar a-z></v-btn>
        </v-col>
    </v-row>
</template>
<script>
export default{
    data(){
        return{
             mascotas: [
                {nombre: "Fido", edad: 3, especie: "perro"},
                {nombre: "Whiskers", edad: 5, especie: "gato"},
                {nombre: "Nemo", edad: 2, especie: "pez"},
                {nombre: "Polly", edad: 7, especie: "loro"},
                {nombre: "Gizmo", edad: 1, especie: "hamster"},
                {nombre: "Thumper", edad: 4, especie: "conejillo de indias"},
                {nombre: "Squirt", edad: 6, especie: "tortuga"},
                {nombre: "Daisy", edad: 3, especie: "cobaya"},
                {nombre: "Mittens", edad: 2, especie: "gato"},
                {nombre: "Buddy", edad: 8, especie: "perro"},
                {nombre: "Lucy", edad: 5, especie: "iguana"},
                {nombre: "Simba", edad: 4, especie: "gato"},
                {nombre: "Toby", edad: 3, especie: "perro"},
                {nombre: "Shadow", edad: 6, especie: "gato"}
                ]
        }
    }       
    }
</script>