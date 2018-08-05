<template>
  <div id="app">
   <grid :data="gridData" :columns="gridColumns"></grid>
  </div>
</template>

<script>
  import Grid from './Grid'
export default {
  name: 'app',
    data(){
      return {
          gridData: [
              { name: 'Chuck Norris', power: Infinity },
              { name: 'Bruce Lee', power: 9000 },
              { name: 'Jackie Chan', power: 7000 },
              { name: 'Jet Li', power: 8000 },
              { name: 'Jet Li', power: 8000 },
              { name: 'Jet Li', power: 8000 },
              { name: 'Jet Li', power: 8000 },
              { name: 'Jet Li', power: 8000 },
              { name: 'Jet Li', power: 8000 },
              { name: 'Jet Li', power: 8000 },
              { name: 'Jet Li', power: 8000 },
              { name: 'Jet Li', power: 8000 },
              { name: 'Jet Li', power: 8000 },
              { name: 'Jet Li', power: 8000 },
              { name: 'Jet Li', power: 8000 },
              { name: 'Bruce Lee', power: 9000 },
              { name: 'Bruce Lee', power: 9000 },
          ],
          gridColumns: ['name', 'power'],
          rowsPerPage: 10,
      }
    },
  components: {
      Grid
  }
}
</script>

<style>
/*#app {*/
  /*font-family: 'Avenir', Helvetica, Arial, sans-serif;*/
  /*-webkit-font-smoothing: antialiased;*/
  /*-moz-osx-font-smoothing: grayscale;*/
  /*text-align: center;*/
  /*color: #2c3e50;*/
  /*margin-top: 60px;*/
/*}*/

/*h1, h2 {*/
  /*font-weight: normal;*/
/*}*/

/*ul {*/
  /*list-style-type: none;*/
  /*padding: 0;*/
/*}*/

/*li {*/
  /*display: inline-block;*/
  /*margin: 0 10px;*/
/*}*/

/*a {*/
  /*color: #42b983;*/
/*}*/
</style>
