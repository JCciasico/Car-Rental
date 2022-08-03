<template>
  <section>
    <div class="container">
        <div class="row">
            <div class="col-12 credit-des">
                <span>Developed by JCC</span>
                &nbsp;<i class="fa-brands fa-github icon"></i>
            </div>

        </div>
    </div>
  </section>
</template>

<script>
export default {

}
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,600;1,500&display=swap');

.credit-des{
    padding: 0.7rem;
    color: white;
    font-family: 'Poppins','sans-serif';
    display: flex;
    align-items: center;
    column-gap: 5px;
}
span{
    margin-top: 5px;
}
.icon{
    font-size: 1.5rem;
}
@media(max-width:500px){
    .credit-des{
        display: flex;
        align-items: center;
        justify-content: center;
    }
}
</style>