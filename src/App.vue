<template>
    <div id="app">
        <!-- line -->
        <b-container>
            <b-row>
                <b-col></b-col>
                <b-col cols="8">
                    <headline2 class="section-title text-center"
                               text="Here comes a banner"></headline2>
                </b-col>
                <b-col></b-col>
            </b-row>
        </b-container>

        <!-- line -->
        <div class="bg__blue">
            <b-container>
                <b-row>
                    <b-col></b-col>
                    <b-col cols="8">
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

        </div>

        <!-- line -->
        <div>

            <b-container>
                <b-row>
                    <b-col></b-col>
                    <b-col cols="8">
                        <CTA_Element text="Hallo du grausame welt, Hallo du grausame welt, Hallo du grausame welt, Hallo du grausame welt"></CTA_Element>
                        <FAQ>
                            <Accordion question="verdammte frage" answer="verdammte antwort"></Accordion>
                            <Accordion question="verdammte frage" answer="verdammte antwort"></Accordion>
                            <Accordion question="verdammte frage" answer="verdammte antwort"></Accordion>
                            <Accordion question="verdammte frage" answer="verdammte antwort"></Accordion>
                        </FAQ>
                    </b-col>
                    <b-col></b-col>
                </b-row>
            </b-container>
        </div>


        <!-- line -->
        <div>
            <b-container>
                <b-row>
                    <b-col></b-col>
                    <b-col cols="10">
                        <BuyButton text="kauf meinen scheiß"></BuyButton>
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
    import Accordion from "@/components/Accordion";
    import FAQ from "./components/FAQ";

    export default {
        name: 'app',
        components: {
            CTA_Element,
            Headline2,
            BuyButton,
            List,
            ListRow,
            Accordion,
            FAQ
        }
    }
</script>

<style>

</style>
