<template>
    <IonPage>
        <IonHeader>
            <IonToolbar>
                <IonTitle>
                    About Us
                </IonTitle>
            </IonToolbar>
        </IonHeader>
        <IonContent>
            <h1>About Page</h1>
            <IonButton color="primary" @click="ionRouter.push('/')">
                Home
            </IonButton>
        </IonContent>
    </IonPage>
</template>

<script setup>
const ionRouter = useIonRouter();
</script>