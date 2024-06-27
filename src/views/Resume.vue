<template>
  <div class="resume">
    <h1>Resume</h1>
    <section class="summary">
      <h2>Summary</h2>
      <p>
        Highly motivated and detail-oriented software developer with 5+ years of experience in building scalable and efficient applications.
      </p>
    </section>
    <section class="experience">
      <h2>Experience</h2>
      <ul>
        <li>
          <h3>Senior Software Developer, ABC Company (2020-Present)</h3>
          <ul>
            <li>Designed and developed multiple features for a cloud-based project management tool using Vue.js and Node.js</li>
            <li>Improved application performance by 30% through optimization and caching</li>
            <li>Mentored junior developers and provided code reviews</li>
          </ul>
        </li>
        <li>
          <h3>Software Developer, DEF Company (2018-2020)</h3>
          <ul>
            <li>Developed a mobile app for iOS and Android using React Native</li>
            <li>Collaborated with designers to implement UI/UX designs</li>
            <li>Participated in code reviews and ensured adherence to coding standards</li>
          </ul>
        </li>
      </ul>
    </section>
    <section class="education">
      <h2>Education</h2>
      <ul>
        <li>
          <h3>Bachelor of Science in Computer Science, XYZ University (2015-2019)</h3>
          <ul>
            <li>Courses: Data Structures, Algorithms, Computer Systems, and Web Development</li>
          </ul>
        </li>
      </ul>
    </section>
    <section class="skills">
      <h2>Skills</h2>
      <ul>
        <li>Programming languages: JavaScript, Python, Java</li>
        <li>Front-end frameworks: Vue.js, React</li>
        <li>Back-end frameworks: Node.js, Django</li>
        <li>Databases: MySQL, MongoDB</li>
        <li>Operating Systems: Windows, Linux, macOS</li>
      </ul>
    </section>
  </div>
</template>

<script>
export default {
  name: 'ResumeView'
}
</script>

<style scoped>
.resume {
  text-align: center;
  padding: 20px;
}

section {
  margin-bottom: 20px;
}

h2 {
  margin-top: 0;
}

ul {
  list-style: none;
  padding: 0;
  margin: 0;
}

li {
  margin-bottom: 10px;
}

h3 {
  margin-top: 0;
}

.skills ul {
  columns: 2;
  -webkit-columns: 2;
  -moz-columns: 2;
}
</style>