<template>
    <div class="text-center m-top-50" style="color: aliceblue;">
      <div class="">
        <div class="padding-t bg-color">
          <div class="fs-1">{{ name }}</div>
          <div class="fs--">{{ subname }}</div>
          <div class="text-center">
            <div class="row">
              <div class="col padding-0">
                <!-- Replace the image with a code snippet or other content -->
                <div class="card color-w">
                  <div class="card-body">
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
              <div class="col">
                <blockquote class="blockquote mb-0 padding-text padding-t">
                  <p>{{ discrition }}</p>
                </blockquote>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </template>
  
  <script>

  export default {
    // eslint-disable-next-line vue/multi-word-component-names
    name: 'Concept',
    data() {
      return {
        name: 'CONCEPT',
        subname: 'My attitude and my concept of myself and work',
        discrition:
          "I believe I can work as a team. Likes to study and gain new knowledge. I like to ask things that I don't know, or sometimes I like to do it myself first rather than asking at all. I like solving problems. Able to accept criticism I like working that isn't too stressful. Have a passion for new things Be an optimistic person I like to tell myself that whatever I can't do, I can do it. Nothing is too difficult to do.",
      };
    },
};
  </script>
  
  <style scoped>
  .padding-text {
    padding: 50px;
  }
  .padding-t {
    padding-top: 100px;
    padding-bottom: 50px;
  }
  .bg-color {
    background-color: #1d1d1d;
    color: aliceblue;
  }
  .padding-0 {
    padding: 0px;
  }
  .code-container {
    text-align: left; /* Aligns code to the left */
    background-color: #2e2e2e; /* Dark background color */
    color: #d4d4d4; /* Light text color */
    padding: 20px; /* Add padding */
    border-radius: 8px; /* Rounded corners */
    overflow: auto; /* Enable scrolling if content overflows */
  }
  .color-w {
    margin: 85px;
    background-color: #3b3b3b;
    color: rgb(255, 255, 255);
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
  