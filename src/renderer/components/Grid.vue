<template>

    <div class="grid-father">

        <div class="grid-container-left">
            <div class="grid-left-top">

            </div>
            <div class="grid-right-top">

            </div>
        </div>

        <div class="grid-container-right">
            <div class="grid-left-bottom">

            </div>
            <div class="grid-right-bottom">

            </div>

        </div>


    </div>


</template>

<script>
  export default {
    name: 'Grid'
  }
</script>

<style scoped>

    .grid-father {
        display: flex;
        flex-direction: column;
        flex-wrap: wrap;
        justify-content: flex-start;

    }

    .grid-container-left {
        flex-direction: row;
    }

    .grid-container-right {
        flex-direction: row;
    }

    .grid-left-top {
        height: auto;
        width: auto;
        border-right: 1em solid;
        border-bottom: 1em solid;
    }


</style>
