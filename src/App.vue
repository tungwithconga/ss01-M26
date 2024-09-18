<script setup>
 
 import Header from "./components/Header.vue"
 import FooterComponent from "./components/FooterComponent.vue"
 import ListCourseVue from "./components/baitap/ListCourse.vue"
 import ColorBox from "./components/baitap/ColorBox.vue"
 import Card from "./components/baitap/Card.vue"
 import Calculation from "./components/baitap/Calculation.vue"
 import Userinfo from "./components/baitap/Userinfo.vue"
 import FormatName from "./components/baitap/FormatName.vue"
 import AdminIndex from "./components/baitap/AdminIndex.vue"
 import UserLayout from "./components/baitap/UserLayout.vue"
 
</script>
<template>
<div>
   <h1>Hello World</h1>
   <Header></Header>
   <footer-component></footer-component>


   Bai1:<ListCourseVue></ListCourseVue>
   Bai2:<ColorBox></ColorBox>
   Bai3:<Card></Card>
   Bai4:<Calculation></Calculation>
   Bai5:<Userinfo></Userinfo>
   Bai6:<format-name></format-name>
   Bai7:<admin-index></admin-index>
   Bai8:<user-layout></user-layout>
   
</div>
</template>
