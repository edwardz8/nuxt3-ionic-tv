<template>
    <IonPage>
        <IonHeader>
            <IonToolbar>
                <IonTitle>
                    Home Page
                </IonTitle>
            </IonToolbar>
        </IonHeader>
        <IonContent>
            <h1>Home Page</h1>
            <IonButton color="primary" @click="ionRouter.push('/about')">
                About
            </IonButton>
        </IonContent>
    </IonPage>
</template>

<script setup>
const ionRouter = useIonRouter();
</script>