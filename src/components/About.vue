<template>
    <div class="text-center m-top-50" style="color: aliceblue;">
        <div class="card bg-color">
            <div class="card-body  padding-t">
                <div class="fs-1">
                    {{name}}
                </div>
                <blockquote class="blockquote mb-0 padding-text">
                <p>{{discrition}}</p>
                
              </blockquote>
            </div>
          </div>
    </div>
</template>

<script>
export default {
    // eslint-disable-next-line vue/multi-word-component-names
    name: 'About',
    components: {
    },
    data(){
        return{
            name: 'ABOUT ME',
            discrition: 'Hello, my name is Aom, full name is Mr. Suphanat Wiboonpanich. Now I am a student at Maejo University Chiang Mai Province Studying in the field of Computer Science, 3rd year, being a computer science student, batch 27.'
        }
    }
}
</script>

<style scoped>
    .bg-color{
        background-color: #2c3e50;
        color: aliceblue;
    }
    .padding-text{
        padding: 50px;
    }
    .padding-t{
        padding-top: 50px;
        padding-bottom: 50px;
    }


</style>