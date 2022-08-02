<template>
    <section>
        <div class="container blog-body" id="blog">
            <div class="text-center">
                <h4>Blog & News</h4>
                <h2>Our Blog Content</h2>
            </div>
            <div class="row gx-4">
                <div class="col-lg col-md-6 col-sm-6 col-xs-12 card-container">
                    <div class="border bg-light" data-aos="fade-right">
                        <img src="../assets/londonyellow.jpg" class="card-img-top" alt="">
                        <div class="row icon-header">
                            <div class="col icon-box">
                                <i class="fa-solid fa-user icon"></i>
                                <span id="title">Nouzen</span>
                            </div>
                            <div class="col icon-box">
                                <i class="fa-solid fa-calendar-days icon"></i>
                                <span id="title">02/08/2022</span>
                            </div>
                            <div class="col icon-box">
                                <i class="fa-solid fa-comments icon"></i>
                                <span id="title">45</span>
                            </div>
                        </div>
                        <div class="card-title">
                            <span>London Airport launches additional flights to Spain</span>
                        </div>
                    </div>
                </div>
                <div class="col-lg col-md-6 col-sm-6 col-xs-12 card-container">
                    <div class="border bg-light" data-aos="zoom-in">
                        <img src="../assets/snow2.jpg" class="card-img-top" alt="">
                        <div class="row icon-header">
                            <div class="col icon-box">
                                <i class="fa-solid fa-user icon"></i>
                                <span id="title">Nouzen</span>
                            </div>
                            <div class="col icon-box">
                                <i class="fa-solid fa-calendar-days icon"></i>
                                <span id="title">02/08/2022</span>
                            </div>
                            <div class="col icon-box">
                                <i class="fa-solid fa-comments icon"></i>
                                <span id="title">45</span>
                            </div>
                        </div>
                        <div class="card-title">
                            <span>Egypt stuck more than 150 tourists from Antartica</span>
                        </div>
                    </div>
                </div>
                <div class="col-lg col-md-6 col-sm-6 col-xs-12 card-container">
                    <div class="border bg-light" data-aos="fade-left">
                        <img src="../assets/vintage.jpg" class="card-img-top" alt="">
                        <div class="row icon-header">
                            <div class="col icon-box">
                                <i class="fa-solid fa-user icon"></i>
                                <span id="title">Nouzen</span>
                            </div>
                            <div class="col icon-box">
                                <i class="fa-solid fa-calendar-days icon"></i>
                                <span id="title">02/08/2022</span>
                            </div>
                            <div class="col icon-box">
                                <i class="fa-solid fa-comments icon"></i>
                                <span id="title">45</span>
                            </div>
                        </div>
                        <div class="card-title">
                            <span>Lamborghini Vintage super luxury car collection in Japan</span>
                        </div>
                    </div>
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

.blog-body{
    padding: 3rem 0;
    padding-bottom: 5rem;
}
h2{
    font-family: 'Poppins','sans-serif';
    font-weight: 600;
    padding-bottom: 2rem;
}
h4{
    font-family: 'Poppins','sans-serif';
    font-weight: 600;
    color: #ffbe00;
    padding: 2rem 0;
}
.card-title{
    padding: 0rem 2rem;
    padding-bottom: 2rem;
    font-family: 'Poppins','sans-serif';
    font-weight: 600;
}
.card-title:hover{
    color: #ffbe00;
    cursor: pointer;
}
.icon-header{
    padding: 1rem 1rem;
}
.icon-box{
    display: flex;
    justify-content: center;
    align-items: center;
    column-gap: 5px;
}
#title{
    font-family: 'Poppins','sans-serif';
    font-size: 0.8rem;
}
.card-container{
    margin-bottom: 25px;
}
@media(max-width:1200px){
    #title{
        font-size: 0.5rem;
    }
    .card-title{
        font-size: 0.8rem;
    }
}
@media(max-width:500px){
    #title{
        font-size: 0.8rem;
    }
    .card-title{
        font-size: 1rem;
    }
    .card-container{
        padding: 0 2.5rem;
    }
}
@media(max-width:400px){
    #title{
        font-size: 0.6rem;
    }
    .card-title{
        font-size: 1rem;
    }
    .card-container{
        padding: 0 2.5rem;
    }
}
</style>