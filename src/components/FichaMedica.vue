<template>
  <v-container>
    <v-card max-width="600" class="mx-auto my-12">
      <v-card-title>Aluno Fulano da Silva</v-card-title>
      <v-card-text class="body-text">14 de Dezembro de 1996 (22 anos de idade)</v-card-text>
      <v-divider></v-divider>
      <v-card-text class="body-text">
        <div class="record-item">
          <h3>Problemas de saúde </h3>
          <span style="margin-left: 8px; font-weight: bold; color: black "> Asmático e com histórico de inventite aguda</span>
        </div>

        <div class="record-item">
          <h3>Nome do pai: </h3>
          <span style="margin-left: 8px; font-weight: bold; color: black "> Ciclano de tal</span>
        </div>

      </v-card-text>
      <v-card-actions>
        <v-btn text>Click</v-btn>
      </v-card-actions>
    </v-card>
  </v-container>
</template>

<script>
export default {
  name: 'FichaMedica',
  data: () => ({
    //
  }),
}
</script>

<style>
.body-text {
  text-align: start;
}

.record-item {
  margin: 8px;
  flex-direction: row;
  display: flex;
}
</style>

