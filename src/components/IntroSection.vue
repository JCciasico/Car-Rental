<template>
  <section>
    <div class="container intro-body">
        <div class="row p-2">
            <div class="col-lg-5 col-md-12 col-sm-12 intro-column">
                <div class="intro-text">
                    <h3 style="color:#ffbe00">Fast and Easy Way to Rent a Car</h3>
                    <h1>Need A Ride? Choose Your<br>
                    Comfortable Car</h1>
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

.intro-body{
    padding: 10rem 0;
}
.img{
    width: 900px;
}
.intro-text{
    color: white;
}
h3{
    margin-bottom: 15px;
}
h1{
    margin-bottom: 25px;
}
h6{
    margin-bottom: 70px;
}
.intro-btn{
    display: flex;
    column-gap: 25px;
}
.btn-1{
    padding: 1rem;
    width: 150px;
    border: none;
}
.btn-2{
    background-color: #ffbe00;
    padding: 1rem;
    width: 150px;
    border: none;
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
}
@media(max-width:500px){
    .intro-text{
        text-align: center;
    }
    .car-column{
        padding: 5rem 2rem;
    }
    .intro-btn{
        display: flex;
        justify-content: center;
    }
}

</style>