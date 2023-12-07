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
                <img
                  src="../assets/code-removebg-preview.png"
                  alt="Avatar"
                  class="avatar">
              </div>
              <div class="col">
                <blockquote class="blockquote mb-0 padding-text padding-t">
                  <p>{{ discrition }}</p>
                  <footer class="blockquote-footer">Someone famous in <cite title="Source Title">Source Title</cite></footer>
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
  </style>
  