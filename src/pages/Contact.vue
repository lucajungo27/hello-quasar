<template>
  <q-page >
<h1>Page de contact</h1>
    <div>
      <p>Je suis {{nom}} et dans 10 ans j'aurais {{age + 10}} ans</p>
    </div>
    <img
      alt="Quasar logo"
      src="~assets/quasar-logo-full.svg"
    >
  </q-page>
</template>

<script>
export default {
  name: 'PageContact',
  data () {
    return {
      nom: 'Pedro',
      age: 33
    }
  }
}
</script>

<style lang ="sass" scoped>
img
  border: 3pxsolid $secondary
</style>
