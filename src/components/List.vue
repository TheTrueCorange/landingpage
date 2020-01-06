<template>
    <div>
        <b-container>
            <slot></slot>
        </b-container>
    </div>
</template>

<script>
    import ListRow from "@/components/ListRow";

    export default {
        name: "List",
        components:{
            ListRow
        }
    }
</script>

<style scoped>

    .red {
        background: red;
    }

    .green {
        background: green;
    }

    .icon-size {
        width: 100%;
        height: 100%;
    }


</style>