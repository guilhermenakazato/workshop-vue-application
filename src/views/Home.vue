<template>
  <v-row no-gutters class="home">
    <v-col>
      <v-card class="pa-2" tile elevation="0">
        <v-card-title class="card-title">
          Gerencie suas tarefas diárias de um jeito mais legal
        </v-card-title>
        <v-card-subtitle class="card-subtitle">
          Com organização e tempo, acha-se o segredo de fazer tudo e bem feito
        </v-card-subtitle>
        <v-card-actions>
          <v-btn class="ma-2" color="secundary"> Criar conta </v-btn>
          <v-btn class="ma-2" outlined color="indigo">
            Já possuo uma conta
          </v-btn>
        </v-card-actions>
      </v-card>
    </v-col>
    <v-col>
      <v-card class="pa-2" tile elevation="0">
        <v-img src="@/assets/images/checklist.svg"></v-img
      ></v-card>
    </v-col>
  </v-row>
</template>
<script>
export default {
  name: "Home",
};
</script>