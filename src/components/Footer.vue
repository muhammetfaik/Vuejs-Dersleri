<template>
    <footer>
        <p>{{ copyright }}</p>
    </footer>
</template>

<script>

export default {
  data () {
    return {
      copyright: 'Compyright 2017 Vue Ninjas'
    }
  }
}
</script>

<style>
footer{
  background: #222;
  padding: 6px;
}
p{
    color: lightgreen;
    text-align: center
}
</style>
