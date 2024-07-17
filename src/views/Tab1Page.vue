<template>
    <ion-page>
        <ion-header>
            <ion-toolbar>
                <ion-title>Tab 1</ion-title>
            </ion-toolbar>
        </ion-header>
        <ion-content :fullscreen="true">
            <ion-button router-link="/tabs/tab1/view">Go To Inner View</ion-button>
        </ion-content>
    </ion-page>
</template>

<script setup lang="ts">
    import {IonPage, IonHeader, IonToolbar, IonTitle, IonContent, IonButton} from '@ionic/vue';
</script>
