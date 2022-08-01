<template>

<section>
    <div class="container services-body">
        <div class="row">
            <div class="col-lg-6 col-md-12 d-flex justify-content-center align-items-center car-img">
                <img src="../assets/2503527.jpg" class="img car-box" alt="yellow lambo">
            </div>
            <div class="col-lg-6 order-md-12 d-flex align-items-center justify-content-center">
                <div class="about-text">
                    <h4>About Our Company</h4>
                    <h2>World Largest automotive marketplace</h2>
                    <p id="about-des">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut
                        labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco
                        laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in
                        voluptate velit esse cillum dolore eu fugiat nulla pariatur. 
                    </p>
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

.services-body{
    padding: 5rem 0;
}
.img{
    width: 525px;
}
.car-box{
    
}
.car-img{
    padding: 5rem;

}
.about-text{
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
}
#about-des{
    font-family: 'Poppins','sans-serif';
    margin-bottom: 30px;
    opacity: 0.7;
}
h5{
    font-family: 'Poppins','sans-serif';
    font-weight: 600;
    font-style: italic; 
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
    #about-des{
        font-family: 'Poppins','sans-serif';
        margin-bottom: 30px;
        opacity: 0.7;
        font-size: 0.7rem;
    }
    h5{
        font-family: 'Poppins','sans-serif';
        font-weight: 600;
        font-style: italic; 
        font-size: 0.9rem;
    }
    .about-text{
        padding: 0 1rem;
    }
    .services-body{
        padding: 3rem 0;
    }
}
@media(max-width:600px){
    .img {
            width: 300px;
        }
    .about-text{
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
    #about-des{
        font-family: 'Poppins','sans-serif';
        margin-bottom: 30px;
        opacity: 0.7;
        font-size: 0.7rem;
    }
    h5{
        font-family: 'Poppins','sans-serif';
        font-weight: 600;
        font-style: italic; 
        font-size: 0.9rem;
    }
    #col-des{
        font-family: 'Poppins','sans-serif';
        margin-bottom: 40px;
        opacity: 0.7;
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
}
</style>