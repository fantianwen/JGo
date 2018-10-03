<template>
    <div class="go-board">
        <div v-for="rowIndex in this.data.go_array.row">
            <div v-for="columnIndex in this.data.go_array.column">
                <GoGrid class="go-grid">
                </GoGrid>

            </div>

        </div>

    </div>
</template>

<script>
  import Grid from './Grid'

  export default {
    name: 'Goban',
    components: {
      GoGrid: {Grid}
    },
    data () {
      return {
        go_array: {
          'row': 19,
          'column': 19
        }
      }
    }

  }
</script>

<style scoped>


</style>
