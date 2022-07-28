<template>
  <section>
    <div class="container intro-body">
        <div class="row p-2">
            <div class="col-lg-5 col-md-12 col-sm-12 intro-column">
                <div class="intro-text">
                    <h5 style="color:#ffbe00">Fast and Easy Way to Rent a Car</h5>
                    <h1>Need A Ride? Choose Your Comfortable Car</h1>
                    <h6>There are many variations of passages of Lorem ipsum available
                    but the majority have suffered alteration in some</h6>
                </div>
                <div class="intro-btn">
                    <button class="btn-1">Read More</button>
                    <button class="btn-2">Find Your Car</button>
                </div>
            </div>
            <div class="col-lg-7 col-md-12 col-sm-12 d-flex align-items-center car-column">
                <img src="../assets/lamborghini.png" class="img-fluid" alt="lamborghini">
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
@import url('https://fonts.googleapis.com/css2?family=Mochiy+Pop+One&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,600;1,500&display=swap');


.intro-body{
   padding-top: 11rem;
   padding-bottom: 13rem;
}
.intro-text{
    color: white;
}
h5{
    margin-bottom: 15px;
    font-weight: 500;
    font-family: 'Poppins', sans-serif;

}
h1{
    margin-bottom: 25px;
    font-weight: 600;
    font-family: 'Poppins', sans-serif;
}
h6{
    margin-bottom: 70px;
    font-family: 'Poppins', sans-serif;
}
.intro-btn{
    display: flex;
    column-gap: 25px;
}
.btn-1{
    padding: 0.7rem;
    width: 150px;
    border: none;
}
.btn-1:hover{
    background-color: #ced6e0;
}
.btn-2{
    background-color: #ffbe00;
    padding: 0.7rem;
    width: 150px;
    border: none;
}
.btn-2:hover{
    background-color: #ffa502;
}
@media(max-width:1200px){
    h5{
        margin-bottom: 10px;
        font-weight: 500;
        font-family: 'Poppins', sans-serif;
        font-size: 1.1rem;
    }
    h1{
        margin-bottom: 25px;
        font-weight: 600;
        font-family: 'Poppins', sans-serif;
        font-size: 1.5rem;
    }
    h6{
        margin-bottom: 50px;
        font-family: 'Poppins', sans-serif;
        font-size: 0.9rem;
    }
    .btn-1{
        padding: 0.5rem;
        width: 125px;
        border: none;
        font-size: 0.8rem;
    }
    .btn-2{
        background-color: #ffbe00;
        padding: 0.5rem;
        width: 125px;
        border: none;
        font-size: 0.8rem;
    }
    
    .intro-body{
        padding-top: 9rem;
        padding-bottom: 11rem;
    }
}
@media(max-width:991px){
    .intro-text{
        text-align: center;
    }
    .car-column{
        padding: 5rem 0;
    }
    .intro-btn{
        display: flex;
        justify-content: center;
    }
    .intro-body{
        padding: 7rem 0;
    }
    
}
@media(max-width:600px){
    .intro-text{
        text-align: center;
        padding: 0 2rem;
    }
    .car-column{
        padding: 5rem 3rem;
    }
    .intro-btn{
        display: flex;
        justify-content: center;
    }
    .btn-1{
        padding: 0.5rem;
        width: 100px;
        border: none;
        font-size: 0.8rem;
    }
    .btn-2{
        background-color: #ffbe00;
        padding: 0.5rem;
        width: 100px;
        border: none;
        font-size: 0.8rem;
    }
    .intro-body{
         padding: 5rem 0;
    }   
    h5{
        margin-bottom: 10px;
        font-weight: 500;
        font-family: 'Poppins', sans-serif;
        font-size: 0.9rem;
    }
    h1{
        margin-bottom: 25px;
        font-weight: 600;
        font-family: 'Poppins', sans-serif;
        font-size: 1.2rem;
    }
    h6{
        margin-bottom: 50px;
        font-family: 'Poppins', sans-serif;
        font-size: 0.7rem;
    }
}

</style>