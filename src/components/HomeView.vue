<template>
    <main>
        <button @click="counter++">Up</button>
        <h3>{{ counter }}</h3>
        <button @click="counter--">Down</button>

        <h3>{{ person.name }}  {{person.age}}</h3>
        <button @click="updatePerson">Update Person</button>
        <h3>{{brand}}</h3>
    </main>
</template>

<script setup lang="ts">
    import { onMounted, reactive, ref } from 'vue';
    const counter = ref(0)

    const person = reactive({name: 'Prasert', age:40})

    const updatePerson =() => {
        person.name='Namo',
        person.age=15
    }

    onMounted(() => {
        setTimeout(() => {
            counter.value =500
            }, 2000)       
    })
    
</script>

<script lang="ts">
   export default {
        data(){
            return {
                brand: "ITGenius"
            }
        },
        mounted(){
            setTimeout(() => {
            this.brand ="Other brand"
            }, 2000)
        }
   }
</script>

<style scoped>

</style>