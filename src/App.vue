<template lang="pug">
  v-app
    v-app-bar(app color="primary" dark)
      v-toolbar-title NGS Map
    v-main
      router-view
</template>

<script>
export default {
  name: "App",

  data: () => ({
    //
  }),
};
</script>
