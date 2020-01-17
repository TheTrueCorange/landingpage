<template>
    <div id="app">
        <!-- line -->
        <b-container>
            <b-row>
                <b-col cols="12">
                    <headline2 class="section-title text-center"
                               text="Here comes a banner"></headline2>
                </b-col>
            </b-row>
        </b-container>

        <!-- line -->
        <div class="bg__blue">
            <b-container>
                <b-row>
                    <b-col cols="6">
                        <List>
                            <ListElement
                                    :url="require('../src/assets/icons/007-dumbbell_white.png')"
                                    text="100% Gewissheit, wie dein Training aussieht."/>
                            <ListElement
                                    :url="require('../src/assets/icons/007-dumbbell_white.png')"
                                    text="100% Gewissheit, wie dein Training aussieht."/>
                            <ListElement
                                    :url="require('../src/assets/icons/007-dumbbell_white.png')"
                                    text="100% Gewissheit, wie dein Training aussieht."/>
                            <ListElement
                                    :url="require('../src/assets/icons/007-dumbbell_white.png')"
                                    text="100% Gewissheit, wie dein Training aussieht."/>
                        </List>
                    </b-col>

                    <b-col cols="6">
                        <List>
                            <ListElementInverted
                                    :url="require('../src/assets/icons/007-dumbbell_white.png')"
                                    text="100% Gewissheit, wie dein Training aussieht."/>
                            <ListElementInverted
                                    :url="require('../src/assets/icons/007-dumbbell_white.png')"
                                    text="100% Gewissheit, wie dein Training aussieht."/>
                            <ListElementInverted
                                    :url="require('../src/assets/icons/007-dumbbell_white.png')"
                                    text="100% Gewissheit, wie dein Training aussieht."/>
                            <ListElementInverted
                                    :url="require('../src/assets/icons/007-dumbbell_white.png')"
                                    text="100% Gewissheit, wie dein Training aussieht."/>
                        </List>
                    </b-col>
                </b-row>
            </b-container>

        </div>

        <!-- line -->
        <div>

            <b-container>
                <b-row>
                    <b-col cols="12">
                        <CTA_Element text="Hallo du grausame welt, Hallo du grausame welt, Hallo du grausame welt, Hallo du grausame welt"></CTA_Element>
                        <FAQ>
                            <Accordion question="verdammte frage" answer="verdammte antwort" identifier="eins"></Accordion>
                            <Accordion question="verdammte frage" answer="verdammte antwort"></Accordion>
                            <Accordion question="verdammte frage" answer="verdammte antwort"></Accordion>
                            <Accordion question="verdammte frage" answer="verdammte antwort"></Accordion>
                        </FAQ>
                    </b-col>
                </b-row>

            </b-container>
        </div>


        <!-- line -->
        <div>
            <b-container>
                <b-row>
                    <b-col cols="12">
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
    import ListElement from "@/components/ListElement";
    import ListElementInverted from "./components/ListElementInverted";
    import CTA_Element from "@/components/CTA_Element";
    import Accordion from "@/components/Accordion";
    import FAQ from "./components/FAQ";

    export default {
        name: 'app',
        components: {
            Headline2,
            BuyButton,
            List,
            ListElement,
            ListElementInverted,
            CTA_Element,
            Accordion,
            FAQ
        }
    }
</script>

<style>

</style>
