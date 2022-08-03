<template>
  <section>
    <div class="container subs-body">
        <div class="row input-content">
            <div class="col-lg-3 col-md-6 sign-cont">
                <i class="fa-solid fa-envelope-open-text icon"></i>
                <span id="signup-text">Sign Up Newsletter</span>
            </div>
            <div class="col-lg-3 col-md-6 sign-des">
                <span>Subscribe to the weekly newsletter for all the latest updates</span>
            </div>
            <div class="col-lg-6 col-md-12 subs-cont">
                <input type="text" name="text" class="text" placeholder="Enter your email address here">
                <button>Subscribe</button>
            </div>
        </div>
        <div class="row">
            <div class="col social-con">
                <img src="../assets/car-jcc.png" alt="jcc logo" class="image">
                <p id="social-text">There are many variations of passages of Lorem ipsum available
                    but the majority have suffered alteration in some for by injected humour</p>
                <div class="social-icon">
                    <div class="box">
                        <i class="fa-brands fa-facebook-f icon-1"></i>
                    </div>
                    <div class="box">
                        <i class="fa-brands fa-twitter icon-1"></i>
                    </div>
                    <div class="box">
                        <i class="fa-brands fa-google icon-1"></i>
                    </div>
                    <div class="box">
                        <i class="fa-brands fa-instagram icon-1"></i>
                    </div>
                </div>
            </div>
            <div class="col"></div>
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

.sign-cont{
    display: flex;
    align-items: center;
    justify-content: center;
    column-gap: 20px;
    padding: 1rem;
    border-right: 2px solid #ffbe00 ;
}
.subs-body{
    padding-bottom: 1rem;
}
.icon{
    color: #ffbe00;
    font-size: 1.7rem;
}
#signup-text{
    font-size: 1rem;
    font-family: 'Poppins','sans-serif';
    margin-top: 5px;
}
.input-content{
    background-color: #f1f2f6;
    padding: 1rem 0;
}
.sign-des{
    display: flex;
    align-items: center;
    padding: 0.5rem 3rem;
    font-size: 0.8rem;
    font-family: 'Poppins','sans-serif';
}
.subs-cont{
    display: flex;
    align-items: center;
    justify-content: center;
}
.text{
    width: 400px;
    height: 45px;
    padding: 1rem;
    font-size: 0.7rem;
    border: 1px solid #dfe4ea;
}
button{
    padding: 0.7rem 2rem;
    border: none;
    background-color: #ffbe00;
    font-size: 0.8rem;
    font-family: 'Poppins','sans-serif';
    border: 1px solid #ffbe00;
}
button:hover{
    background-color: white;
    border: 1px solid #ffbe00;
    cursor: pointer;
}
.image{
    width: 100px;
    height: 60px;
}
.social-con{
    padding: 3rem 1rem;
    color: white;
}
#social-text{
    padding: 0 1rem;
    padding-top: 1rem;
}
.social-icon{
    padding: 0.3rem 1rem;
    display: flex;
    align-items: center;
    column-gap: 10px;
}
.box{
    background-color: #808080;
    padding: 0.5rem 0;
    width: 35px;
    display: flex;
    align-items: center;
    justify-content: center;
}
.box:hover{
    cursor: pointer;
    color: #ffbe00;
}
.icon-1{
    font-size: 0.9rem;
}
@media (max-width:600px) {
   .sign-cont{
    border: none;
   }
}
</style>