

<script setup>
import { RouterLink, RouterView } from 'vue-router'

</script>

<template>
<main>
  <div class="main"> 
    <br><br><br>
    <div class="words">
      <h1>"User-centered design means understanding what your users need, how they think, and how they behave - and incorporating that understanding into every aspect of your process."</h1>
    </div>
    <br><br><br>
    <h1 id="subhead1">Notable Design Projects</h1>
    <br>
    <div class="flexbox">
      <div class="one">
        <img id ="portimg1" src="src\assets\portpic1.png">
        <h2 class="phototitle">Web Design - Design an application for movie fanatics</h2>
      </div>
        <div class="two"><img id ="portimg2" src="src\assets\portpic2.png">
        <h2 class="phototitle">Graphic Design</h2>
      </div>
      <div class="three"><img id ="portimg3" src="src\assets\portpic3.png">
        <h2 class="phototitle">Research - User Journey for someone trying to fact check an article on social media</h2>
      </div>
      <div class="four"><img id ="portimg4" src="src\assets\portpic4.png">
        <h2 class="phototitle">Web Design - Design concept for a virtual classroom environment</h2>
      </div>
    </div>
    <div>
      <br><br><br><br>
      <h1 id=subhead2>My Experience</h1>
      <br>
      <div class="paragraph">
        <p>My professional experiences include project management, customer relations,</p>
        <p>and administrative assisting. My academic experiences include computer science,</p>
        <p>human-computer interaction, anthropology, and psychology.</p>
      </div>
    </div>
    <br><br><br>
    <div class="flex-container">
      <div>
        <h2>Self-Employed</h2>
        <h3>Personal Mentor and Tutor</h3>
        <p>November 2017 — May 2021</p>
      </div>
      <div>
        <h2>UNCC</h2>
        <h3>CIS Teaching Assistant</h3>
        <p>August 2021 — Present</p>
      </div>
      <div>
        <h2>AV Painting</h2>
        <h3>Project Manager and Customer Relations</h3>
        <p>June 2021 — Present</p>
      </div>
      <div>
        <h2>Girls Who Code</h2>
        <h3>Summer Course Advisor</h3>
        <p>June 2022 — August 2022</p>
      </div>
    </div>

  </div> 

</main>
<footer>
  <br><br><br><br>
  <div class="formbody">
    <h3 class="form-h3">Let's Connect!</h3>

    <div class="formgroup">
      <label for="Name" class="formlabel">Your name:</label>
      <div class="forminput">
        <input type="text" id="Name" name="Name" class="formcontrol" required>
      </div>
    </div>

    <div class="formgroup">
      <label for="Email" class="formlabel">Your email address:</label>
      <div class="forminput">
        <input type="email" id="Email" name="Email" class="formcontrol" required>
      </div>
    </div>

    <div class="formgroup">
      <label for="Message" class="formlabel">Your message:</label>
      <div class="forminput">
        <textarea id="Message" name="Message" class="formcontrol" rows="6" maxlength="3000" required></textarea>
      </div>
    </div>

    <div class="formgroup">
      <button type="submit" id="formbutton">Send Message</button>
    </div>

  </div>
</footer>
</template>

