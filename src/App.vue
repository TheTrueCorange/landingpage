<template>
    <div id="app">
        <!-- line -->
        <b-container>
            <b-row>
                <b-col></b-col>
                <b-col cols="10">
                    <headline2 class="section-title text-center"
                               text="Gym 4 Life"></headline2>
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
                        <List>
                            <ListRow
                                    :url="require('../src/assets/icons/007-dumbbell_white.png')"
                                    text="100% Gewissheit, wie dein Training aussieht."
                                    :url2="require('../src/assets/icons/007-dumbbell_white.png')"
                                    text2="100% Gewissheit, wie dein Training aussieht."/>
                            <ListRow
                                    :url="require('../src/assets/icons/007-dumbbell_white.png')"
                                    text="100% Gewissheit, wie dein Training aussieht."
                                    :url2="require('../src/assets/icons/007-dumbbell_white.png')"
                                    text2="100% Gewissheit, wie dein Training aussieht."/>
                            <ListRow
                                    :url="require('../src/assets/icons/007-dumbbell_white.png')"
                                    text="100% Gewissheit, wie dein Training aussieht."
                                    :url2="require('../src/assets/icons/007-dumbbell_white.png')"
                                    text2="100% Gewissheit, wie dein Training aussieht."/>
                        </List>
                    </b-col>
                    <b-col></b-col>
                </b-row>
            </b-container>
            <CTA_Element text="Hallo du grausame welt, Hallo du grausame welt, Hallo du grausame welt, Hallo du grausame welt">
            </CTA_Element>
        </div>

        <!-- line -->
        <div>
            <b-container>
                <b-row>
                    <b-col></b-col>
                    <b-col cols="10">
                        <BuyButton text="hallo welt" url="http://www.google.com"></BuyButton>
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
    import ListRow from "@/components/ListRow";
    import CTA_Element from "@/components/CTA_Element";

    export default {
        name: 'app',
        components: {
            CTA_Element,
            Headline2,
            BuyButton,
            List,
            ListRow,
        }
    }
</script>

<style>

</style>
