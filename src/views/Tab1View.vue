<script setup lang="ts">
    import {IonPage, IonHeader, IonToolbar, IonButtons, IonBackButton, IonTitle, IonContent} from '@ionic/vue';
</script>

<template>
    <ion-page>
        <ion-header>
            <ion-toolbar>
                <ion-buttons slot="start">
                    <ion-back-button/>
                </ion-buttons>
                <ion-title>Tab 1 Inner View</ion-title>
            </ion-toolbar>
        </ion-header>

        <ion-content fullscreen color="light">
            Tab 1 Inner View
        </ion-content>
    </ion-page>
</template>

<style scoped>

</style>