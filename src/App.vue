<template>
    <div id="app">
        <!-- line -->
        <b-container>
            <b-row>
                <b-col></b-col>
                <b-col cols="10">
                    <headline2 class="section-title text-center"
                               text="Hallo meine kleine liebe welt Hallo meine kleine liebe welt Hallo meine kleine liebe welt Hallo meine kleine liebe welt"></headline2>
                </b-col>
                <b-col></b-col>
            </b-row>
        </b-container>

        <!-- line -->
        <div class="bg__blue">
            <b-container>
                <b-row>
                    <b-col></b-col>
                    <b-col cols="10">
                        <List></List>
                    </b-col>
                    <b-col></b-col>
                </b-row>

                <BuyButton text="hallo welt" url="http://www.google.com"></BuyButton>
            </b-container>
        </div>

        <!-- line -->
        <div>
            <b-container>
                <b-row>
                    <b-col></b-col>
                    <b-col cols="10">
                        <headline2 class="section-title txt-center" text="hallo w"></headline2>
                    </b-col>
                    <b-col></b-col>
                </b-row>
            </b-container>
        </div>

    </div>
</template>

<script>
    import Headline2 from "@/components/Headline2";
    import BuyButton from "@/components/BuyButton";
    import List from "@/components/List";

    export default {
        name: 'app',
        components: {
            Headline2,
            BuyButton,
            List,
        }
    }
</script>

<style>

</style>
