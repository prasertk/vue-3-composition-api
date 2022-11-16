<template>
    <main>
        <button @click="counter++">Up</button>
        <h3>{{ counter }}</h3>
        <button @click="counter--">Down</button>

        <h3>{{ person.name }}  {{person.age}}</h3>
        <button>Update Person</button>
    </main>
</template>

<script setup lang="ts">
    import { reactive, ref } from 'vue';
    const counter = ref(0)

    const person = reactive({name: 'Prasert', age:40})

    const updatePerson =() => {
        
    }

</script>

<style scoped>

</style>