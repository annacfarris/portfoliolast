<script setup>
import { RouterLink, RouterView } from 'vue-router'
import Home from '@/components/Home.vue'
</script>
<template>
  <nav>
  <div class=header>
    <h1 id="title">Anna Edwards Professional Portfolio</h1>
    <div class="nav-bar">
       <RouterLink to="/"><h2>Home</h2></RouterLink>
      <RouterLink to="/about"><h2>About</h2></RouterLink>
      </div>
    <h3 id="subtitle">UX Researcher and Project Manager</h3>
      
  </div>
</nav>

<RouterView />
</template>


<style>
@import './assets/base.css'; 
body {
  background-color: #f3e9dc;
  font-weight: normal;
  padding-top: 60px;
  padding-bottom: 40px;
}
#title {
  font-family: didot;
  color: #60412b;
  font-size: 40px;
  padding-left: 20px;
  display: inline-block;
  
}
#subtitle {
  font-family: didot;
  color: #60412b;
  font-size: 20px;
  padding-left: 20px;
  opacity: 0.75;
  padding-bottom: 10px;
  
}

.header{
  width: 100%;
  position: fixed;        
  background: #d3c0b2;
  padding-top: 2px;
  z-index: 2;
  top:0;
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);
}
nav h2{
  color: #857b74;
  text-decoration: none;
  padding-right:35px;
  padding-bottom: 5px;
  padding-top:19%;
  display: inline-block;
  font-size: 18pt;
  font-family: didot;
}
nav h2:hover{
  color: white;
  text-shadow: 1px 1px 1px #857b74;
}
.nav-bar {
  
 float:right;

}

.words {
  font-size: 30px;
  font-family: didot;
  color: #6A4D51;
  opacity: 0.85;
  text-align: center;
  margin-left: auto;
  margin-right: auto;
  text-shadow: 2px 2px 2px #857b74;
}

.flexbox{
  height: 1000px;
  width: 1200px;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  flex-wrap: wrap;
  margin-left: auto;
  margin-right: auto;
}
.flexbox div {
  width: 40%;
  height: 45%;
}

#portimg1, #portimg2 {
  height:450px;
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);
}
#portimg3, #portimg4 {
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);
}
#subhead1 {
  padding-left: 260px;
  color:#9d4b14;
  opacity:0.8;
  text-decoration: underline;
}
.phototitle{
  font-style: italic;

}
#subhead2{
  padding-left: 260px;
  color:#9d4b14;
  opacity:0.8;
  text-decoration: underline;
}
.paragraph {
  padding-left: 260px;
  color:#9d4b14;
  font-size: 18pt;
}
.flex-container {
  display: flex;
  flex-direction: row;
  justify-content: center;
  gap: 30px;
  
}
.flex-container div {
  background-color: #c5b0a3;
  padding: 25px;
  border-radius: 25px;
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);
}
main h2{
  color:#9d4b14;
  
}
main h3{
  color:#9d4b14;
}
main p {
  color:#9d4b14;
  font-style: italic;
}
.formbody {
  background-color: #c5b0a3;
  margin: 0;
  font-family: -apple-system, Arial, sans-serif;
  font-size: 1rem;
  font-weight: 400;
  line-height: 1.5;
  color: #9d4b14;
  text-align: left;
  padding: 30px;  
  padding-bottom: 10px;
  border: 1px solid #ced4da;
  border-radius: 0.25rem; 
  max-width: 100%;
  display: block;
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);
  
}
.formgroup {
  margin-bottom: 1rem;
}
.forminput{
  position: relative;
  display: -ms-flexbox;
  display: flex;
  -ms-flex-wrap: wrap;
  flex-wrap: wrap;
  -ms-flex-align: stretch;
  align-items: stretch;
  width: 100%;
}
.formcontrol{
  display: block;
    width: 60%;
    height: calc(1.5em + 0.75rem + 2px);
    padding: 0.375rem 0.75rem;
    font-size: 1rem;
    font-weight: 400;
    line-height: 1.5;
    color: #495057;
    background-color: #fff;
    background-clip: padding-box;
    border: 1px solid #ced4da;
    outline: none;
    border-radius: 0.25rem;
    transition: border-color 0.15s ease-in-out, box-shadow 0.15s ease-in-out;
}
.formcontrol:focus{
  border: 1px solid #313131;
}
#formbutton {
    display: inline-block;
    font-weight: 400;
    background-color: #9d4b14;
    color: #212529;
    text-align: center;
    vertical-align: middle;
    cursor: pointer;
    border: 1px solid transparent;
    padding: 0.375rem 0.75rem;
    font-size: 1rem;
    line-height: 1.5;
    border-radius: 0.25rem;
    transition: color 0.15s ease-in-out, background-color 0.15s ease-in-out, border-color 0.15s ease-in-out, box-shadow 0.15s ease-in-out;
    border: 1px solid #313131;
    box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);
}
#formbutton:hover{
  background-color: #a08e83;
}
.form-h3{
  font-family: didot;
  font-size: 20pt;
}
.formlabel {
  font-family: didot;
  font-size: 15pt;
}
#Message{
  height:100px;
}

</style>