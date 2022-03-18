<template>
  <q-page class="flex flex-center">
    <img
      alt="Quasar logo"
      src="~assets/quasar-logo-vertical.svg"
      style="width: 200px; height: 200px"
    >
      <q-btn
        outline
        rounded
        class="float-right"
        color="primary"
        label="Botão teste"
        @click="link"/>
  </q-page>
</template>

<script>
export default {
  name: 'PageIndex',

  methods: {
    link() {
      alert('Clicou aqui');
    },
  },
};
</script>
