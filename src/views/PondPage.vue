<template>
    <ion-page>
        <ion-content :fullscreen="true">
            <ion-grid>
                <ion-row class="ion-align-items-center">
                    <ion-col><h1 id="judul">Kolam</h1> </ion-col>
                    <ion-col class="ion-text-end" style="margin-right: 1rem">
                        <ion-img
                            src="assets/img/sort.svg"
                            style="
                                width: 24px;
                                display: inline-block;
                                margin-right: 1rem;
                            "
                        ></ion-img>
                        <ion-img
                            src="assets/img/Vector.svg"
                            style="width: 24px; display: inline-block"
                        ></ion-img
                    ></ion-col>
                    <!-- <ion-col class="ion-text-end">
                    ></ion-col> -->
                </ion-row>
            </ion-grid>
            <ion-list>
                <ion-item>
                    <ion-card color="dark" style="border-radius: 16px">
                        <ion-card-header>
                            <ion-grid>
                                <ion-row
                                    class="ion-align-items-center"
                                    style="border-bottom: 2px solid black"
                                >
                                    <ion-col id="card-title"
                                        ><strong>Alpha</strong></ion-col
                                    >
                                    <ion-col class="ion-text-end"
                                        ><ion-badge
                                            style="
                                                background-color: green;
                                                padding: 0.5rem;
                                                font-size: 16px;
                                                border-radius: 10px;
                                            "
                                            >Aktif</ion-badge
                                        ></ion-col
                                    >
                                </ion-row>

                                <ion-row
                                    class="ion-align-items-center"
                                    style="margin-top: 10px"
                                >
                                    <ion-col class="ion-text-start" size="auto"
                                        ><ion-img
                                            src="assets/img/calendar.svg"
                                            style="
                                                width: 24px;
                                                display: inline-block;
                                            "
                                        />
                                    </ion-col>
                                    <ion-col
                                        class="ion-text-start"
                                        style="font-size: 16px"
                                        >01-09-2022</ion-col
                                    >
                                </ion-row>
                                <ion-row class="ion-align-items-center">
                                    <ion-col class="ion-text-start" size="auto"
                                        ><ion-img
                                            src="assets/img/timesheet.svg"
                                            style="
                                                width: 24px;
                                                display: inline-block;
                                            "
                                        />
                                    </ion-col>
                                    <ion-col
                                        class="ion-text-start"
                                        style="font-size: 16px"
                                        >90 Hari</ion-col
                                    >
                                </ion-row>
                                <ion-row class="ion-align-items-center">
                                    <ion-col class="ion-text-start" size="auto"
                                        ><ion-img
                                            src="assets/img/fish.svg"
                                            style="
                                                width: 24px;
                                                display: inline-block;
                                            "
                                        />
                                    </ion-col>
                                    <ion-col
                                        class="ion-text-start"
                                        style="font-size: 16px"
                                        >200 Ekor</ion-col
                                    >
                                </ion-row>
                            </ion-grid>

                            <!-- <ion-card-title>Kolam</ion-card-title>
                            <ion-card-subtitle>10</ion-card-subtitle> -->
                        </ion-card-header>
                    </ion-card>
                </ion-item>
                <ion-item>
                    <ion-card color="dark" style="border-radius: 16px">
                        <ion-card-header>
                            <ion-grid>
                                <ion-row
                                    class="ion-align-items-center"
                                    style="border-bottom: 2px solid black"
                                >
                                    <ion-col id="card-title" class="ion-te"
                                        ><strong>Beta</strong></ion-col
                                    >
                                    <ion-col class="ion-text-end"
                                        ><ion-badge
                                            style="
                                                background-color: #952229;
                                                padding: 0.5rem;
                                                font-size: 16px;
                                                border-radius: 10px;
                                            "
                                            >Tidak Aktif</ion-badge
                                        ></ion-col
                                    >
                                </ion-row>
                                <ion-row
                                    class="ion-align-items-center"
                                    style="margin-top: 10px"
                                >
                                    <ion-col class="ion-text-start" size="auto"
                                        ><ion-img
                                            src="assets/img/calendar.svg"
                                            style="
                                                width: 24px;
                                                display: inline-block;
                                            "
                                        />
                                    </ion-col>
                                    <ion-col
                                        class="ion-text-start"
                                        style="font-size: 16px"
                                        >01-09-2022</ion-col
                                    >
                                </ion-row>
                                <ion-row class="ion-align-items-center">
                                    <ion-col class="ion-text-start" size="auto"
                                        ><ion-img
                                            src="assets/img/timesheet.svg"
                                            style="
                                                width: 24px;
                                                display: inline-block;
                                            "
                                        />
                                    </ion-col>
                                    <ion-col
                                        class="ion-text-start"
                                        style="font-size: 16px"
                                        >90 Hari</ion-col
                                    >
                                </ion-row>
                                <ion-row class="ion-align-items-center">
                                    <ion-col class="ion-text-start" size="auto"
                                        ><ion-img
                                            src="assets/img/fish.svg"
                                            style="
                                                width: 24px;
                                                display: inline-block;
                                            "
                                        />
                                    </ion-col>
                                    <ion-col
                                        class="ion-text-start"
                                        style="font-size: 16px"
                                        >200 Ekor</ion-col
                                    >
                                </ion-row>
                            </ion-grid>

                            <!-- <ion-card-title>Kolam</ion-card-title>
                            <ion-card-subtitle>10</ion-card-subtitle> -->
                        </ion-card-header>
                    </ion-card>
                </ion-item>
                <ion-item>
                    <ion-card color="dark" style="border-radius: 16px">
                        <ion-card-header>
                            <ion-grid>
                                <ion-row
                                    class="ion-align-items-center"
                                    style="border-bottom: 2px solid black"
                                >
                                    <ion-col id="card-title"
                                        ><strong>Charlie</strong></ion-col
                                    >
                                    <ion-col class="ion-text-end"
                                        ><ion-badge
                                            style="
                                                background-color: green;
                                                padding: 0.5rem;
                                                font-size: 16px;
                                                border-radius: 10px;
                                            "
                                            >Aktif</ion-badge
                                        ></ion-col
                                    >
                                </ion-row>
                                <ion-row
                                    class="ion-align-items-center"
                                    style="margin-top: 10px"
                                >
                                    <ion-col class="ion-text-start" size="auto"
                                        ><ion-img
                                            src="assets/img/calendar.svg"
                                            style="
                                                width: 24px;
                                                display: inline-block;
                                            "
                                        />
                                    </ion-col>
                                    <ion-col
                                        class="ion-text-start"
                                        style="font-size: 16px"
                                        >01-09-2022</ion-col
                                    >
                                </ion-row>
                                <ion-row class="ion-align-items-center">
                                    <ion-col class="ion-text-start" size="auto"
                                        ><ion-img
                                            src="assets/img/timesheet.svg"
                                            style="
                                                width: 24px;
                                                display: inline-block;
                                            "
                                        />
                                    </ion-col>
                                    <ion-col
                                        class="ion-text-start"
                                        style="font-size: 16px"
                                        >90 Hari</ion-col
                                    >
                                </ion-row>
                                <ion-row class="ion-align-items-center">
                                    <ion-col class="ion-text-start" size="auto"
                                        ><ion-img
                                            src="assets/img/fish.svg"
                                            style="
                                                width: 24px;
                                                display: inline-block;
                                            "
                                        />
                                    </ion-col>
                                    <ion-col
                                        class="ion-text-start"
                                        style="font-size: 16px"
                                        >200 Ekor</ion-col
                                    >
                                </ion-row>
                            </ion-grid>

                            <!-- <ion-card-title>Kolam</ion-card-title>
                            <ion-card-subtitle>10</ion-card-subtitle> -->
                        </ion-card-header>
                    </ion-card>
                </ion-item>
                <ion-item>
                    <ion-card color="dark" style="border-radius: 16px">
                        <ion-card-header>
                            <ion-grid>
                                <ion-row
                                    class="ion-align-items-center"
                                    style="border-bottom: 2px solid black"
                                >
                                    <ion-col id="card-title"
                                        ><strong>Delta</strong></ion-col
                                    >
                                    <ion-col class="ion-text-end"
                                        ><ion-badge
                                            style="
                                                background-color: green;
                                                padding: 0.5rem;
                                                font-size: 16px;
                                                border-radius: 10px;
                                            "
                                            >Aktif</ion-badge
                                        ></ion-col
                                    >
                                </ion-row>
                                <ion-row
                                    class="ion-align-items-center"
                                    style="margin-top: 10px"
                                >
                                    <ion-col class="ion-text-start" size="auto"
                                        ><ion-img
                                            src="assets/img/calendar.svg"
                                            style="
                                                width: 24px;
                                                display: inline-block;
                                            "
                                        />
                                    </ion-col>
                                    <ion-col
                                        class="ion-text-start"
                                        style="font-size: 16px"
                                        >01-09-2022</ion-col
                                    >
                                </ion-row>
                                <ion-row class="ion-align-items-center">
                                    <ion-col class="ion-text-start" size="auto"
                                        ><ion-img
                                            src="assets/img/timesheet.svg"
                                            style="
                                                width: 24px;
                                                display: inline-block;
                                            "
                                        />
                                    </ion-col>
                                    <ion-col
                                        class="ion-text-start"
                                        style="font-size: 16px"
                                        >90 Hari</ion-col
                                    >
                                </ion-row>
                                <ion-row class="ion-align-items-center">
                                    <ion-col class="ion-text-start" size="auto"
                                        ><ion-img
                                            src="assets/img/fish.svg"
                                            style="
                                                width: 24px;
                                                display: inline-block;
                                            "
                                        />
                                    </ion-col>
                                    <ion-col
                                        class="ion-text-start"
                                        style="font-size: 16px"
                                        >200 Ekor</ion-col
                                    >
                                </ion-row>
                            </ion-grid>

                            <!-- <ion-card-title>Kolam</ion-card-title>
                            <ion-card-subtitle>10</ion-card-subtitle> -->
                        </ion-card-header>
                    </ion-card>
                </ion-item>
                <ion-item>
                    <ion-card color="dark" style="border-radius: 16px">
                        <ion-card-header>
                            <ion-grid>
                                <ion-row
                                    class="ion-align-items-center"
                                    style="border-bottom: 2px solid black"
                                >
                                    <ion-col id="card-title"
                                        ><strong>Epsilon</strong></ion-col
                                    >
                                    <ion-col class="ion-text-end"
                                        ><ion-badge
                                            style="
                                                background-color: green;
                                                padding: 0.5rem;
                                                font-size: 16px;
                                                border-radius: 10px;
                                            "
                                            >Aktif</ion-badge
                                        ></ion-col
                                    >
                                </ion-row>
                                <ion-row
                                    class="ion-align-items-center"
                                    style="margin-top: 10px"
                                >
                                    <ion-col class="ion-text-start" size="auto"
                                        ><ion-img
                                            src="assets/img/calendar.svg"
                                            style="
                                                width: 24px;
                                                display: inline-block;
                                            "
                                        />
                                    </ion-col>
                                    <ion-col
                                        class="ion-text-start"
                                        style="font-size: 16px"
                                        >01-09-2022</ion-col
                                    >
                                </ion-row>
                                <ion-row class="ion-align-items-center">
                                    <ion-col class="ion-text-start" size="auto"
                                        ><ion-img
                                            src="assets/img/timesheet.svg"
                                            style="
                                                width: 24px;
                                                display: inline-block;
                                            "
                                        />
                                    </ion-col>
                                    <ion-col
                                        class="ion-text-start"
                                        style="font-size: 16px"
                                        >90 Hari</ion-col
                                    >
                                </ion-row>
                                <ion-row class="ion-align-items-center">
                                    <ion-col class="ion-text-start" size="auto"
                                        ><ion-img
                                            src="assets/img/fish.svg"
                                            style="
                                                width: 24px;
                                                display: inline-block;
                                            "
                                        />
                                    </ion-col>
                                    <ion-col
                                        class="ion-text-start"
                                        style="font-size: 16px"
                                        >200 Ekor</ion-col
                                    >
                                </ion-row>
                            </ion-grid>

                            <!-- <ion-card-title>Kolam</ion-card-title>
                            <ion-card-subtitle>10</ion-card-subtitle> -->
                        </ion-card-header>
                    </ion-card>
                </ion-item>
            </ion-list>
            <ion-fab vertical="bottom" horizontal="end" slot="fixed">
                <ion-fab-button color="tertiary" href="/register">
                    <ion-icon :icon="add" style="font-size: 50px"></ion-icon>
                </ion-fab-button>
            </ion-fab>
        </ion-content>
    </ion-page>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import { IonPage, IonContent } from "@ionic/vue";
import { add } from "ionicons/icons";

export default defineComponent({
    name: "PondPage",
    components: {
        IonContent,
        IonPage,
    },
    setup() {
        return {
            add,
        };
    },
});
</script>
<style scoped>
ion-content {
    background-color: #1f1d2b;
}
#judul {
    margin-left: 1rem;
}
#card-title {
    font-size: 18px;
}
ion-card {
    width: 100%;
}
ion-list {
    background-color: #1f1d2b;
}
</style>
