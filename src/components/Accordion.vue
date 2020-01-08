<template>
    <div>
        <b-button @click="toggleActive" v-b-toggle.collapse-1 variant="primary">{{question}}</b-button>
        <b-collapse id="collapse-1" class="mt-2">
            <b-card>
                <p class="card-text">{{answer}}</p>
            </b-card>
        </b-collapse>
    </div>
</template>

<script>
    export default {
        name: "Accordion",
        props:{
            question: String,
            answer: String,
            isActive: Boolean,
        },
        methods:{
            toggleActive: function(){
                this.isActive = !this.isActive;
            }
        }
    }
</script>

<style scoped>

</style>