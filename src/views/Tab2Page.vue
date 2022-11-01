<template>
    <ion-page>
        <ion-content :fullscreen="true">
            <h1 id="judul">Home</h1>
            <ion-list :inset="true">
                <ion-item>
                    <ion-card color="dark">
                        <ion-card-header>
                            <ion-grid>
                                <ion-row style="border-bottom: 2px solid black">
                                    <ion-col>Kolam</ion-col>
                                    <ion-col class="ion-text-end"
                                        ><ion-badge>Aktif</ion-badge></ion-col
                                    >
                                </ion-row>
                                <ion-row>
                                    <ion-col>01-09-2022</ion-col>
                                </ion-row>
                                <ion-row>
                                    <ion-col>01-09-2022</ion-col>
                                </ion-row>
                                <ion-row>
                                    <ion-col>01-09-2022</ion-col>
                                </ion-row>
                            </ion-grid>

                            <!-- <ion-card-title>Kolam</ion-card-title>
                            <ion-card-subtitle>10</ion-card-subtitle> -->
                        </ion-card-header>
                    </ion-card>
                </ion-item>
                <ion-item>
                    <ion-card color="dark">
                        <ion-card-header>
                            <ion-card-title>Kolam</ion-card-title>
                            <ion-card-subtitle>10</ion-card-subtitle>
                        </ion-card-header>
                    </ion-card>
                </ion-item>
                <ion-item>
                    <ion-card color="dark">
                        <ion-card-header>
                            <ion-card-title>Kolam</ion-card-title>
                            <ion-card-subtitle>10</ion-card-subtitle>
                        </ion-card-header>
                    </ion-card>
                </ion-item>
                <ion-item>
                    <ion-card color="dark">
                        <ion-card-header>
                            <ion-card-title>Kolam</ion-card-title>
                            <ion-card-subtitle>10</ion-card-subtitle>
                        </ion-card-header>
                    </ion-card>
                </ion-item>
                <ion-item>
                    <ion-card color="dark">
                        <ion-card-header>
                            <ion-card-title>Kolam</ion-card-title>
                            <ion-card-subtitle>10</ion-card-subtitle>
                        </ion-card-header>
                    </ion-card>
                </ion-item>
            </ion-list>
        </ion-content>
    </ion-page>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import { IonPage, IonContent } from "@ionic/vue";

export default defineComponent({
    name: "Tab2Page",
    components: {
        IonContent,
        IonPage,
    },
});
</script>
<style scoped>
#judul {
    margin-left: 1rem;
}
ion-card {
    width: 100%;
}
</style>
