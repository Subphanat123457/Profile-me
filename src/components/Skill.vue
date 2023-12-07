<template>
    <div class="text-center m-top-50" style="color: aliceblue;">
        <div class="card bg-color">
            <div class="card-body  padding-t">
                <div class="fs-1">
                    {{name}}
                </div>
                <blockquote class="blockquote mb-0 padding-text">
                <p>{{discrition}}</p>
                <footer class="blockquote-footer">Someone famous in <cite title="Source Title">Source Title</cite></footer>
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
            discrition: 'Hello, my name is Aom, full name is Mr. Suphanat Wiboonpanich. Now I am a student at Maejo University Chiang Mai Province Studying in the field of Computer Science, 3rd year, being a computer science student, batch 27.'
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
  padding-bottom: 50px;
}
.bg-color {
  background-color: #1d1d1d;
  color: aliceblue;
}

</style>