<template>
  <div class="text-center m-top-50" style="color: aliceblue;">
    <div class=" bg-color">
      <div class="card-body  padding-t">
        <div class="fs-1">
          {{ name }}
        </div>
        <div class="fs-5">
          My skills that I can do include my mindset.
        </div>
        <blockquote class="blockquote mb-0 padding-text">
          <div class="container">
            <div class="row">
              <div class="col">
                <div class="card color-w">
                  <div class="card-body size-text ">
                    <h5 class="card-title" style="text-align: center;">Hard Skills</h5>
                    <div class="code-container">
                      <pre class="code">
                                <code>
                                  <p><span class="card-text keyword text-l">Programming language:</span> I can write Program in many languages html css java javascript C mt5 Pine Script Python</p>
                                  <p><span class="card-text keyword text-l">Frameworks:</span> vue.js react bootstrap5 antdesige</p>
                                  <p><span class="card-text keyword text-l">Image editing:</span> Experience in image editing.</p>
                                  <p><span class="card-text keyword text-l">Video Editing:</span> Experience in video editing such as Adobe Premiere Pro, Cap Cut.</p>
                                  <p><span class="card-text keyword text-l">Microsoft Office:</span> Experience in using Microsoft Office such as Excel, Word.</p>
                                  <p><span class="card-text keyword text-l">Web Development:</span> I can develop web applications using Vue.js and React.</p>
                                  <p><span class="card-text keyword text-l">IoT:</span> I can design and create innovations Arduino</p>
                                  <p><span class="card-text keyword text-l">Project Management:</span> Able to effectively manage assigned projects.</p>
                                </code>
                              </pre>
                    </div>
                  </div>
                </div>
              </div>
              <div class="col">
                <div class="card color-w">
                  <div class="card-body">
                    <h5 class="card-title">Soft Skills</h5>
                    <div class="code-container">
                      <pre class="code">
                                <code>
                                  <p><span class="card-text keyword text-l">Soft Skills </span><span class="variable"> Development: Enhancing interpersonal and communication skills.</span></p> 
                                  <p><span class="card-text keyword text-l" >Adaptability:</span><span class="variable"> Flexibility and adaptability in various situations.</span></p>
                                  <p><span class="card-text keyword text-l">Collaboration:</span><span class="variable"> Working effectively in a team environment.</span></p>
                                  <p><span class="card-text keyword text-l">Time Management:</span><span class="variable"> Efficiently managing time and priorities.</span></p>
                                  <p><span class="card-text keyword text-l">Problem Solving:</span><span class="variable"> Analyzing and solving complex problems.</span></p>
                                  <p><span class="card-text keyword text-l">Leadership:</span><span class="variable"> Leading and influencing others positively.</span></p>
                                </code>
                              </pre>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </blockquote>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  // eslint-disable-next-line vue/multi-word-component-names
  name: 'Skill',
  components: {
  },
  data() {
    return {
      name: 'SKILLS',
      discrition: 'Hello, my name is Aom, full name is Mr. Suphanat Wiboonpanich. Now I am a student at Maejo University Chiang Mai Province Studying in the field of Computer Science, 3rd year, being a computer science student, batch 27.',
      hardSkill: '',
      softSkill: 'Soft Skills',
    }
  }

}
</script>

<style scoped>
.padding-text {
  padding: 50px;
}

.padding-t {
  padding-top: 100px;
  padding-bottom: 100px;
  padding-left: 20px;
  padding-right: 20px;
}

.bg-color {
  background-color: #1d1d1d;
  color: aliceblue;
}

.color-w {
  background-color: #3b3b3b;
  color: rgb(255, 255, 255);
}

.size-text {
  font-size: 15px;
  text-align: left;
}

.code-container {
  text-align: left;
  /* Aligns code to the left */
  background-color: #2e2e2e;
  /* Dark background color */
  color: #d4d4d4;
  /* Light text color */
  padding: 20px;
  /* Add padding */
  border-radius: 8px;
  /* Rounded corners */
  overflow: auto;
  /* Enable scrolling if content overflows */
}

.code {
  font-family: 'Monaco', monospace;
  /* Use Monaco font or similar */
  font-size: 14px;
  /* Adjust font size as needed */
  white-space: pre-wrap;
  /* Preserve whitespace and wrap lines */
  tab-size: 2;
  /* Set tab size */
  line-height: 1.5;
  /* Set line height for better readability */
}

.comment {
  color: #6a9955;
  /* Green color for comments */
}

.keyword {
  color: #d857cf;
  /* Pink color for keywords */
}

.variable {
  color: #4ec9b0;
  /* Cyan color for variables */
}

.string {
  color: #ce9178;
  /* Orange color for strings */
}

.function {
  color: #4ec9b0;
  /* Cyan color for function names */
}

.methodName {
  color: #dcdcaa;
  /* Light yellow color for method names */
}

.parameter {
  color: #9cdcfe;
  /* Light blue color for parameters */
}

.text-l {
  text-align: left;
}</style>