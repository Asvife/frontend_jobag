<template>
<div >
  <v-card
      max-width="1200"
      class="mx-auto"
      outlined
  >
    <v-list-item three-line>
      <v-list-item-content>
        <div class="text-overline mb-4 txt_anuncio">
          San Isidro, Lima
        </div>
        <v-list-item-title class="text-h5 mb-1 txt_anuncio">
          Desarollador Backend
        </v-list-item-title>
        <v-list-item-subtitle>Claro</v-list-item-subtitle>
      </v-list-item-content>

      <v-list-item-avatar
          size="80"
          color="grey"
      >
        <v-img
            max-height="80"
            max-width="80"
            src="data:image/jpeg;base64,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"></v-img>
      </v-list-item-avatar>
    </v-list-item>
  </v-card>
  &nbsp;
  <v-card max-width="1200" class="mx-auto">
        <v-card-title class="txt_anuncio"> Detalles del Aviso</v-card-title>
    <v-card-title class="txt_parrafo" >
      <p class="txt_parrafo" >
        Nuestro cliente en tecnología de la información con más de 39 años en el sector, enfocado en proyectos de Medio de Pago - POS.<br />

        Se encuentra en búsqueda de un PROGRAMADOR FRONT END<br />

        Requisitos:<br />


        - Experiencia en Angular<br />
        - Nivel avanzado en HTML5, CSS3, JavaScript, JQuery<br />
        - Experiencia en creación de mockups, wireframe y prototipos<br />
        - Experiencia en consumo API REST<br />
        - Experiencia UX (Opcional)<br />
        - Conocimiento GIT<br />

        Ofrecemos:<br />

        • Ingreso a planilla<br />
        • Trabajo remoto

      </p>
    </v-card-title>

    <v-dialog
        v-model="dialog"
        persistent
        max-width="290"
    >
      <template v-slot:activator="{ on, attrs }">

        <div class="text-center">
          <v-btn
              color="#EA4E4E"
              dark
              v-bind="attrs"
              v-on="on"
          >
            Postularme
          </v-btn>
        </div>
      </template>

      <v-card>
        <v-card-title class="text-h6">
          ¿Tus datos están al día?
        </v-card-title>
        <v-card-text> Mantén tu información actualizada, así las empresas podran contactarte.</v-card-text>
        <v-card-actions>

          <v-btn
              color="#19AE1F"
              text
              @click="dialog = false"
              to="/watch_job/postulation"
          >
            Aceptar
          </v-btn>
          <v-btn
              color="#F90C0C"
              text
              @click="dialog = false"
          >
            Revisar
          </v-btn>
        </v-card-actions>
      </v-card>
    </v-dialog>

  </v-card>

</div>
</template>

<script>
export default {
  name: "watch_job"
}
</script>

<style scoped>
.txt_anuncio{
  font-family:"Roboto";
  color:#1955AE;
}
.txt_parrafo{
  font-family:"Roboto";
  font-size: 17px;
}

.center {
  font-family:"Roboto";
  font-size: 17px;
  color:#FFFFFF;
  display: flex;
}
</style>