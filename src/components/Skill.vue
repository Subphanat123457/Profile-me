<template>
    <div class="text-center m-top-50" style="color: aliceblue;">
        <div class="card bg-color">
            <div class="card-body  padding-t">
                <div class="fs-1">
                    {{name}}
                </div>
                <blockquote class="blockquote mb-0 padding-text">
                  <div class="container">
                    <div class="row">
                      <div class="col">
                        <div class="card color-w">
                          <div class="card-body size-text padding-t">
                            <h5 class="card-title" style="text-align: center;">Hard Skills</h5>
                            <div class="code-container">
                              <pre class="code">
                                <code>
                                  <p class="card-text keyword text-l">1. Programming Languages:</p> <p class="card-text string">Expertise in multiple programming languages.</p> 
                                  <p class="card-text " >2. Photo Editing: Experience in editing images.</p>
                                  <p class="card-text ">3. Video Editing: Experience in editing videos.</p>
                                  <p class="card-text ">4. Microsoft Office: Experience in using Microsoft Office.</p>
                                  <p class="card-text ">5. Web Development: Proficient in developing web applications using Vue.js and React.</p>
                                  <p class="card-text ">6. Project Management: Capable of managing assigned projects effectively.</p>
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
                                  <span class="comment">// Your code goes here</span>
                                  <span class="keyword">const</span> <span class="variable">message</span> = <span class="string">'Hello, Vue.js!'</span>;
                          
                                  <span class="function">function</span> <span class="methodName">greet</span>(<span class="parameter">name</span>) {
                                    <span class="keyword">return</span> <span class="string">`Greetings, ${name}!`</span>;
                                  }
                          
                                  <span class="comment">// Call the function</span>
                                  <span class="keyword">console</span>.<span class="function">log</span>(<span class="function">greet</span>(<span class="string">'User'</span>));
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
    data(){
        return{
            name: 'SKILL',
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
  text-align: left; /* Aligns code to the left */
  background-color: #2e2e2e; /* Dark background color */
  color: #d4d4d4; /* Light text color */
  padding: 20px; /* Add padding */
  border-radius: 8px; /* Rounded corners */
  overflow: auto; /* Enable scrolling if content overflows */
}

.code {
  font-family: 'Monaco', monospace; /* Use Monaco font or similar */
  font-size: 14px; /* Adjust font size as needed */
  white-space: pre-wrap; /* Preserve whitespace and wrap lines */
  tab-size: 2; /* Set tab size */
  line-height: 1.5; /* Set line height for better readability */
}

.comment {
  color: #6a9955; /* Green color for comments */
}

.keyword {
  color: #d857cf; /* Pink color for keywords */
}

.variable {
  color: #4ec9b0; /* Cyan color for variables */
}

.string {
  color: #ce9178; /* Orange color for strings */
}

.function {
  color: #4ec9b0; /* Cyan color for function names */
}

.methodName {
  color: #dcdcaa; /* Light yellow color for method names */
}

.parameter {
  color: #9cdcfe; /* Light blue color for parameters */
}
.text-l{
  text-align: left;
}

</style>