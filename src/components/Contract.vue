<template>
    <footer>
        <div class="text-center m-top-50" style="color: aliceblue;">
            <div class="card bg-color">
                <div class="card-body  padding-t">
                    <div class="fs-1">
                        {{ name }}
                    </div>
                    <div class="container">
                        <div class="row">
                            <div class="col" style="padding-top: 40px;">
                                <img src="https://scontent.fcnx4-1.fna.fbcdn.net/v/t39.30808-1/356249846_110696228739546_2330496381601105760_n.jpg?stp=dst-jpg_p240x240&_nc_cat=105&ccb=1-7&_nc_sid=5740b7&_nc_eui2=AeHxSIYYAMP57M383CQs98igtRCn5ajnqM21EKflqOeozXWqcBCJscOmeUvK_eTRo1pX8MY6FPdPKmByD4iV8113&_nc_ohc=ODxL7PE6up8AX-eP6Xt&_nc_ht=scontent.fcnx4-1.fna&oh=00_AfAoSxDRTMikkU2MR5BivqJmEGMQF9RJW5UnrrJtEtkcqQ&oe=657A28E8" class="rounded mx-auto d-block" alt="my photo">
                            </div>
                            <div class="col">
                                <blockquote class="blockquote mb-0 padding-text text-a-l">
                                    <p><i class="bi bi-facebook"></i> {{ facebook }}</p>
                                    <p><i class="bi bi-instagram"></i> {{ ig }}</p>
                                    <p><i class="bi bi-line"></i> {{ line }}</p>
                                    <p><i class="bi bi-envelope"></i> {{ email }}</p>
                                    <p><i class="bi bi-telephone"></i> {{ tel }}</p>
                                </blockquote>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </footer>
</template>

<script>
export default {
    // eslint-disable-next-line vue/multi-word-component-names
    name: 'Contract',
    components: {
    },
    data() {
        return {
            name: 'CONTRACT',
            facebook: 'Supanat Wiboonpanit',
            ig: 'aom2545_17',
            line: 'aomza788',
            email: 'irpg17102545aom@gmail.com',
            tel: '086-1191958',
        }
    }

}
</script>

<style scoped>
.bg-color {
    background-color: #2c3e50;
    color: aliceblue;
}

.padding-text {
    padding: 50px;
}

.padding-t {
    padding-top: 50px;
    padding-bottom: 50px;
}
.text-a-l{
    text-align: left;
}

</style>