<template>
  <section>
    <div class="container subs-body">
        <div class="row input-content">
            <div class="col-3 sign-cont">
                <i class="fa-solid fa-envelope-open-text icon"></i>
                <span id="signup-text">Sign Up Newsletter</span>
            </div>
            <div class="col-3 sign-des">
                <span>Subscribe to the weekly newsletter for all the latest updates</span>
            </div>
            <div class="col-6 subs-cont">
                <input type="text" name="text" class="text" placeholder="Enter your email address here">
                <button>Subscribe</button>
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
</style>