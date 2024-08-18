<template>
  <div id="about">
    <div class="container">
      <div class="row">
        <div class="about-col-1">
          <img src="/assets/black.jpg">
        </div>
        <div class="about-col-2">
          <h1 class="sub-title">About me</h1>
          <p>A dedicated and enthusiastic computer science student with a strong foundation in programming and software development. Proficient in multiple programming languages including C++, Java, Python, C, and C#. Adept at problem-solving and data structures, with a keen interest in developing innovative solutions. Eager to gain hands-on experience through an OJT position, contributing to impactful projects while continuing to grow professionally.</p>
          <div class="tab-titles">
            <p class="tab-links active-link" @click="opentab('Skills')">Skills</p>
            <p class="tab-links" @click="opentab('Experience')">Experience </p>
            <p class="tab-links" @click="opentab('Education')">Education</p> 
          </div>
          <div class="tab-contents active-tab" id="Skills">
            <ul>
              <li><span>Programming Languages</span><br>C++<br>Python<br>JAVA</li>
              <li><span>Tools and Technologies</span><br>GIT<br>Visual Studio<br>Eclipse</li>
              <li><span>Microsoft Office</span><br>Word<br>Excel<br>Power Point</li>
            </ul>
          </div>
          <div class="tab-contents" id="Experience">
            <ul>
              <li><span>Project Name: KASABA</span><br>Fornt-End</li>
              <li><span>Lereve Koffi</span><br>Barista</li>
              <li><span>Organizer and Participant</span><br>Seminar: Streamlining Development: Agile Methodologies and Emerging Web Technologies in Action</li>
            </ul>
          </div>
          <div class="tab-contents" id="Education">
            <ul>
              <li><span>2017-2019</span><br>Thy Covenant Montessori School<br>General Academic Strand</li>
              <li><span>2019-Present</span><br>Mindanao State University-Main Campus<br>BS Computer Science</li>
            </ul>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'About',
  methods: {
    opentab(tabname) {
      const tablinks = document.getElementsByClassName("tab-links");
      const tabcontents = document.getElementsByClassName("tab-contents");
      for (let tablink of tablinks) {
        tablink.classList.remove("active-link");
      }
      for (let tabcontent of tabcontents) {
        tabcontent.classList.remove("active-tab");
      }
      event.currentTarget.classList.add("active-link");
      document.getElementById(tabname).classList.add("active-tab");
    }
  }
}
</script>

<style scoped>
/* Add your specific styles for About here */
</style>