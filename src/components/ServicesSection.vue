<template>

<section>
    <div class="container services-body" id="services">
        <div class="row">
            <div class="col-lg-6 col-md-12 d-flex justify-content-center align-items-center car-img" data-aos="zoom-out">
                <img src="../assets/ca-cropped.jpg" class="img car-box" alt="yellow lambo">
            </div>
            <div class="col-lg-6 order-md-12 d-flex align-items-center justify-content-center">
                <div class="service-text" data-aos="zoom-in">
                    <h4>Best Services</h4>
                    <h2>Providing Amazing Services Our Clients</h2>
                    <p id="service-des">There are many variations of passages of lorem ipsum available, but the majority have suffiered alteration
                        in some form, by injecting humour, or randomise words.
                    </p>
                    <div class="box-container">
                        <div class="row text-center box-item">
                            <div class="col box">
                                <i class="fa-solid fa-car icon"></i>
                                <span id="services-item">Luxury Limousine Selection</span>
                            </div>
                            <div class="col box">
                                <i class="fa-solid fa-headset icon"></i>
                                <span id="services-item">24/7 Order Available</span>
                            </div>
                            <div class="col box">
                                <i class="fa-solid fa-clock icon"></i>
                                <span id="services-item">Fast Car Delivery Services</span>
                            </div>
                        </div>
                        <div class="row text-center">
                            <div class="col box">
                                <i class="fa-solid fa-user-shield icon"></i>
                                <span id="services-item">High Safety and Nurity</span>
                            </div>
                            <div class="col box">
                                <i class="fa-solid fa-money-bill-1-wave icon"></i>
                                <span id="services-item">Fixed Price & Bonus System</span>
                            </div>
                            <div class="col box">
                                <i class="fa-solid fa-user-tie icon"></i>
                                <span id="services-item">Professional Car Driver</span>
                            </div>
                        </div>
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

.services-body{
    padding: 5rem 0;
}
.img{
    width: 525px;
}
.car-img{
    padding: 5rem;

}
.service-text{
    padding:  0rem;
}
h4{
    font-family: 'Poppins','sans-serif';
    font-weight: 600;
    color: #ffbe00;
}
h2{
    font-family: 'Poppins','sans-serif';
    font-weight: 600;
    margin: 30px 0;
    color: white;
}
#service-des{
    font-family: 'Poppins','sans-serif';
    margin-bottom: 30px;
    color: white;
}
h5{
    font-family: 'Poppins','sans-serif';
    font-weight: 600;
    font-style: italic; 
}
#services-item{
    color: white;
    font-family: 'Poppins','sans-serif';
}
.box{
    display: flex;
    flex-direction: column;
    justify-content: start;
    row-gap: 10px;
}
.box-container{
    padding-top: 3rem;
}
.box-item{
    margin-bottom: 30px;
}
.icon{
    color: #ffbe00;
    font-size: 3em;
}
@media(max-width:1200px){
    .img {
            width: 325px;
    }
    h4{
        font-family: 'Poppins','sans-serif';
        font-weight: 600;
        color: #ffbe00;
        font-size: 1rem;
    }
    h2{
        font-family: 'Poppins','sans-serif';
        font-weight: 600;
        margin: 20px 0;
        font-size: 1.2rem;
    }
    #service-des{
        font-family: 'Poppins','sans-serif';
        margin-bottom: 30px;
        font-size: 0.7rem;
    }
    h5{
        font-family: 'Poppins','sans-serif';
        font-weight: 600;
        font-style: italic; 
        font-size: 0.9rem;
    }
    .service-text{
        padding: 0 1rem;
    }
    .services-body{
        padding: 3rem 0;
    }
    .icon{
        color: #ffbe00;
        font-size: 2em;
    }
    #services-item{
        font-size: 0.7rem;
    }
}
@media(max-width:600px){
    .img {
            width: 300px;
        }
    .service-text{
        text-align: center;
    }
    h4{
    font-family: 'Poppins','sans-serif';
    font-weight: 600;
    color: #ffbe00;
    font-size: 1rem;
    }
    h2{
        font-family: 'Poppins','sans-serif';
        font-weight: 600;
        margin: 20px 0;
        font-size: 1.2rem;
    }
    #service-des{
        font-family: 'Poppins','sans-serif';
        margin-bottom: 30px;
        font-size: 0.7rem;
    }
    h5{
        font-family: 'Poppins','sans-serif';
        font-weight: 600;
        font-style: italic; 
        font-size: 0.9rem;
    }
    .icon{
        color: #ffbe00;
        font-size: 1.75em;
    }
    #services-item{
        font-size: 0.7rem;
    }
}
@media(max-width:400px){
    .img{
        width: 250px;
    }
    h5{
        font-family: 'Poppins','sans-serif';
        font-weight: 600;
        font-style: italic; 
        font-size: 0.7rem;
    }
    .icon{
        color: #ffbe00;
        font-size: 1.5em;
    }
    #services-item{
        font-size: 0.7rem;
    }
}
</style>