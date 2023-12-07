<template>
    <div class="text-center m-top-50" style="color: aliceblue;">
        <div class="card bg-color">
            <div class="card-body  padding-t">
                <div class="fs-1">
                    {{name}}
                </div>
                <div class="fs-4">
                    {{subname}}
                </div>
                <div class="text-center">
                        <img
                        src="../assets/Screenshot 2023-12-07 225715.png"
                        alt="Avatar"
                        class="avatar magin-t"
                        width="450"
                        height="300">
                     
                      
                        <blockquote class="blockquote mb-0 padding-text padding-t">
                            <p>{{ discription1 }}</p>
                            <p>{{ discription2 }}</p>
                            <footer class="blockquote-footer">Someone famous in <cite title="Source Title">Source Title</cite></footer>
                          </blockquote> 
                </div>
            </div>
          </div>
    </div>
</template>

<script>
export default {
    // eslint-disable-next-line vue/multi-word-component-names
    name: 'Certificate',
    components: {
    },
    data(){
        return{
            name: 'CERTIFICATE',
            
            subname: 'Training certificates from various companies or institutions',
            discription1:'Basic Cyber Security Training 2023',
            discription2:'BINET Managed Services Company',
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
    .magin-t{
        margin-top: 50px;
    }

</style>