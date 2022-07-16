<template>
  <v-container>
    <v-row no-gutters>
      <v-col sm="10" class="mx-auto">
        <v-card class="pa5">
          <v-card-title class="justify-center">Add New Posting</v-card-title>
          <v-divider></v-divider>
          <v-form ref="form" class="pa-5" enctype="multipart/form-data">
            <v-text-field label="Title" prepend-icon="mdo-note" :rules="rules"></v-text-field>
          </v-form>
        </v-card>
      </v-col>
    </v-row>
  </v-container>
</template>