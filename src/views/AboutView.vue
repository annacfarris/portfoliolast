<template>
    <main>
        <br><br><br><br><br><br>
        <div class="about">
            <div class="aboutwords">
            <br><br><br>
            <h1>I'm Anna</h1>
            <h1>Edwards</h1>
            <br>
            <p>I am recently graduated with a</p>
            <p>Bachelor's degree in Computer</p> 
            <p>Science with a concentration in</p>
            <p>Human-Centered Design. I am</p>
            <p>fascinated by the innerworkings of the</p>
            <p>human mind and strive to create</p>
            <p>designs that humans can seamlessly</p>
            <p>interact with.</p>
            </div>
            <img id ="aboutimg" src="src\assets\portfolioaboutphoto.png">

        </div> 
        
        <div class="flexbox2">
          <div class="one2">
            <h1>What have I done?</h1>
            <p>I have been working as a remote project</p>
            <p>consultant and project manager for AV Painting</p>
            <p>in Seattle, WA, for a year. After graduating in May</p>
            <p>2022, I will begin a remote summer job at</p> 
            <p>Girls Who Code as a summer course advisor.</p> 
          </div>
          <div class="two2">
            <h1>What will I do?</h1>
            <p>My ideal job will utilize my out-of-the-box ideas in a</p>
            <p>way that provides complete support to the client.</p>
            <p>I want to design physical and technological products</p>
            <p>that are not only user-friendly but are user-assistive.</p>
            <p>I hope to do this while working in the UX Research</p>
            <p>field.</p>
            <br>
            <p>To compliment my human-centered computer </p>
            <p>science studies, I have taken several courses in</p>
            <p>anthropology, psychology, sociology, research, and </p>
            <p>ethics. </p>
            
          </div>
          <div class="three2">
            <div class="left">
              <h1>UX Research</h1>
              <h1>UX Design</h1>
              <h1>Prototyping</h1>
              <h1>Webflow</h1>
            </div>
            <div class="right">
              <h1>Vue.JS</h1>
              <h1>Miro</h1>
              <h1>Back-End Dev</h1>
              <h1>Front-End Dev</h1>
            </div>
          </div>
          <div class="four2">
            <h1>Related Courses</h1>
            <p>Logic and Algorithms</p>
            <p>Data Structures and Algorithms</p>
            <p>Computers & Their Impact on Society</p>
            <p>Human-Centered Design</p>
            <p>Web App Design and Development</p>
            <p>Rapid Prototyping</p>
            <p>Intro to Info Security & Privacy</p>
            <p>Intro to Cognitive Science</p>
            <p>Interactive System Design & Implementation</p>
            <p>Design & Implementation of Object-oriented Systems</p>
            <p>Intro to Computer Networks</p>
            <p>Software Architecture & Design</p>
            <p>Intro to Operating Systems & Networking</p>
            <p>Argument-Based Research</p>
          
          </div>
          
        </div>
        <br><br><br>
    
    </main>
</template>
 
<style> 
@import '@/assets/base.css';
.about{
  text-align: center;
}
.aboutwords h1{
  color:#8b4a1e;
  font-family: didot;
  font-size: 50pt;
  text-align: left;
  line-height: .85;
}
.aboutwords {
  float:left;
  padding-left: 150px;
}
.aboutwords p {
  font-family: didot;
  font-size: 20pt;
  text-align: left;
  color:#8b4a1e;
  opacity: 0.75;
  
}
#aboutimg {
  border-radius: 10px;
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);
}

.flexbox2{
  height: 800px;
  width: 1200px;
  display: flex;
  flex-direction: column;
  /*justify-content: space-between;*/
  flex-wrap: wrap;
  margin-left: auto;
  margin-right: auto;
  align-items: center;
  align-content: space-between;
  justify-content: center;
  
}

.flexbox2 div {
  width: 40%;
  height: 34%;
}

.flexbox2 h1 {
  color:#8b4a1e;
}
.flexbox2 p {
  opacity: .8;
  font-size: 14pt;
  font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
  line-height: 1.8;
}
.left {
  float: left;
}
.right{
  float:right;
}

.flexbox2 h1 {
  font-family: didot;
  
}
</style>