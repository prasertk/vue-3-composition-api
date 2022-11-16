<template>
  <!-- <h1>{{title}}</h1>
  <p>{{message}}</p>
  <p>{{year}}</p> -->

  <HomeView />
</template>


<script setup lang="ts">
  import { ref } from 'vue';
  import HomeView from './components/HomeView.vue';

  // const title =ref("Hello World !")
  // const message =ref("Welcome to everybody")
  // const year = ref(2000)

  // setTimeout(() => {
  //   title.value ="Hello Toe !"
  // }, 2000);

</script>

<!-- <script lang="ts">
import { defineComponent,ref,reactive } from 'vue' -->

// export default defineComponent({
  //   //Composition API
  //   setup () {
  //     //ref จะรองรับ premitive type string, number,boolean including object
  //     // let title =ref("Hello World !")
  //     // const message =ref("Welcome to everybody")
  //     // const year = ref(2000)
  //     // console.log(title)
  //     // const data= ref({
  //     //   title: "Hello World!",
  //     //   message:"Welcome to everybody",
  //     //   year:2000
  //     // })
  
  //     //Reactive จะรองรับเฉพาะ Object เท่านั้น !!!
  //     const data= reactive({
  //       title: "Hello World!",
  //       message:"Welcome to everybody",
  //       year:2000
  //     })
  
  
  //     setTimeout(() => {
  //       // title.value ="Hello Toe !"
  //       // data.value.title ="Hello Toe !"
  
  //       data.title="Hello Toe !"
  //     }, 2000);
  
  
  //     // return {title,message,year}
  //     return {data}
  //   },
  
  //   //====Option API====
  //   // data(){
  //   //   return {
  //   //     title: "Hello World!"
  //   //   }
  //   // },
  //   // mounted(){
  //   //   setTimeout(() => {
  //   //     this.title ="Hello Toe !"
  //   //   }, 2000);
  //   // }
  
  // })
  <!-- // </script> -->



<style scoped>

</style>