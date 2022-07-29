<template>
    <div class="container about-body" id="about">
        <div class="row">
            <div class="col-lg-6 col-md-12 d-flex justify-content-center align-items-center car-img">
                <img src="../assets/yellow-lambo.png" class="img car-box" alt="yellow lambo">
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
                    <div class="row">
                        <div class="col-6">
                            <h5>Famous Brands</h5>
                            <p id="col-des">There are many variations pass ages of lorem ipsum available</p>
                        </div>
                        <div class="col-6">
                            <h5>Best Ratings</h5>
                            <p id="col-des">There are many variations pass ages of lorem ipsum available</p>
                        </div>
                    </div>
                    <button class="btn">Read More</button>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {

}
</script>

<style scoped>

@import url('https://fonts.googleapis.com/css2?family=Mochiy+Pop+One&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,600;1,500&display=swap');

.about-body{
    padding: 3rem 0;
}
.img{
    width: 525px;
}
.car-box{
    box-shadow: -20px 20px #ffbe00;
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
#col-des{
    font-family: 'Poppins','sans-serif';
    margin-bottom: 40px;
    opacity: 0.7;
}
.btn{
    padding: 0.5rem;
    background-color: #ffbe00;
    width: 150px;
    border-radius: 0px;
}
.btn:hover{
    background-color: white;
    color: #ffbe00;
    border: 1px solid #ffbe00;
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
    #col-des{
        font-family: 'Poppins','sans-serif';
        margin-bottom: 40px;
        opacity: 0.7;
        font-size: 0.7rem;
    }
    .btn{
        padding: 0.5rem;
        background-color: #ffbe00;
        width: 120px;
        border-radius: 0px;
        font-size: 0.8rem;
    }
    .about-text{
        padding: 0 1rem;
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
    .btn{
        padding: 0.5rem;
        background-color: #ffbe00;
        width: 120px;
        border-radius: 0px;
        font-size: 0.8rem;
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