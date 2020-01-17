<template>
    <div>
        <b-button :class="visible ? null : 'collapsed'"
                  :aria-expanded="visible ? 'true' : 'false'"
                  :aria-controls="identifier"
                  @click="visible = !visible"
        >
            Toggle Collapse</b-button>
        <b-collapse :id="identifier" v-model="visible" class="mt-2">
            <b-card>
                <p class="card-text">{{answer}}</p>
            </b-card>
        </b-collapse>
    </div>
</template>

<script>
    export default {
        data() {
            return {
                visible: true
            }
        },
        name: "Accordion",
        props:{
            question: String,
            answer: String,
            isActive: Boolean,
            identifier: String,
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