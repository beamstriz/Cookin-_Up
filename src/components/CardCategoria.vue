<script lang="ts">
export default {
    props: {
        categoria: { type: Object, required: true }
    }
}
</script>

<template>
    {{ categoria.nome }}
    {{ categoria.imagem }}
</template>