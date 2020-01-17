<template>
    <b-row>
        <b-col cols="6">
            <p class="white">{{text}}</p>
        </b-col>
        <b-col cols="6">
            <div class="floatLeft">
                <img :src="url" width="100px" height="100px">
            </div>
        </b-col>
    </b-row>
</template>

<script>
    export default {
        name: "ListRow",
        props: {
            url: String,
            text: String,
        }
    }
</script>

<style scoped>
    .floatLeft{
        float: left;
    }
</style>