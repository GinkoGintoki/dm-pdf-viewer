<template>
    <div id="app" class="app">
        <dm-pdf-viewer name="document" pdf-viewer-id="first" footer url="/Сертификат (10).pdf"/>
    </div>
</template>

<script>
import DmPdfViewer from './DmPdfViewer.vue'
    export default {
        name: 'App',
        components: {DmPdfViewer}
    }
</script>

<style scoped>
.app {
    margin: 0 auto;
    /*width: 50vw;*/
    /*height: 60vh;*/
    display: flex;
}
</style>