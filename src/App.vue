<script>
import testa from './components/header.vue'
import under from './components/underHeader.vue'
import pagina from './components/main.vue'
import fascia from './components/jumbo.vue'
import conto from './components/count.vue'
import carte from './components/cards.vue'

export default {
    components: {
        under,
        testa,
        pagina,
        fascia,
        conto,
        carte
    }
}

</script>
<template>
    <testa />
    <hr>
    <under />
    <pagina />
    <fascia />
    <conto />
    <carte />
</template>
<style></style>