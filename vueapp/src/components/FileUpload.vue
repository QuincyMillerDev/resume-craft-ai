<script lang="ts" setup>

</script>

<template>
<v-container>
  <v-row class="justify-center">
    <v-form>
      <v-file-input
          class="mx-2 my-2"
          show-size
          variant="outlined"
          counter="1"
          label="Upload Resume/CV">
      </v-file-input>
      <v-textarea
        label="Paste Job Description"
        variant="outlined">
      </v-textarea>
      <v-btn type="submit">Modify my Resume</v-btn>
    </v-form>
  </v-row>
</v-container>
</template>
