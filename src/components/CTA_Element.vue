<template>
    <div class="cta_element background white thisWidth">
        {{text}}
    </div>
</template>

<script>
    export default {
        name: "CTA_Element",
        props:{
            text: String
        }
    }
</script>

<style scoped>

    .background{
        background-color: #1e3250;
    }

    .thisWidth{
        max-width: 80%;
        margin: auto;
    }

</style>