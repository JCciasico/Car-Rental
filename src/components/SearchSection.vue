<template>
<section>
    <div class="container search-section">
        <div class="row">
            <div class="col-lg-6 col-md-12 d-flex align-items-center search-body">
                <div class="search-text">
                    <h4>Search your Car</h4>
                    <h2>The every ocasion best rental car</h2>
                    <p id="search-des">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod
                        temporincididunt ut
                        labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco
                        laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in
                        voluptate velit esse cillum dolore eu fugiat nulla pariatur.
                    </p>
                    <div class="text-center">
                        <img src="../assets/car-rental.png" class="img-fluid" alt="">
                    </div>
                </div>
            </div>
            <div class="col-lg-6 col-md-12 form-body">
                <form class="container-fluid p-5 form-con">
                    <div class="row">
                        <div class="col-lg-6 col-md-6 col-sm-6">
                            <label for="validationCustom01">Picking up location</label>
                            <div class="d-flex align-items-center input-con">
                                <input type="text" class="form-control input" placeholder="Your location" required>
                                <i class="fa-solid fa-location-dot icon"></i>
                            </div>
                            <div class="valid-feedback">
                                Looks good!
                            </div>
                        </div>
                        <div class="col-lg-6 col-md-6 col-sm-6">
                            <label for="validationCustom01">Picking up date</label>
                            <div class="d-flex align-items-center input-con">
                                <input type="text" class="form-control input" placeholder="dd/mm/yy" required>
                                <i class="fa-solid fa-calendar-days icon"></i>
                            </div>
                            <div class="valid-feedback">
                                Looks good!
                            </div>
                        </div>
                    </div>
                    <div class="row">
                        <div class="col-lg-6 col-md-6 col-sm-6">
                            <label for="validationCustom01">Picking up time</label>
                            <div class="d-flex align-items-center input-con">
                                <input type="text" class="form-control input" placeholder="10:00 AM" required>
                                <i class="fa-solid fa-clock icon"></i>
                            </div>
                            <div class="valid-feedback">
                                Looks good!
                            </div>
                        </div>
                        <div class="col-lg-6 col-md-6 col-sm-6">
                            <label for="validationCustom01">Dropping off location</label>
                            <div class="d-flex align-items-center input-con">
                                <input type="text" class="form-control input" placeholder="Off your location" required>
                                <i class="fa-solid fa-location-dot icon"></i>
                            </div>
                            <div class="valid-feedback">
                                Looks good!
                            </div>
                        </div>
                    </div>
                    <div class="row">
                        <div class="col-lg-6 col-md-6 col-sm-6">
                            <label for="date">Dropping off date</label>
                            <div class="d-flex align-items-center input-con">
                                <input type="text" class="form-control input" placeholder="dd/mm/yy" required>
                                <i class="fa-solid fa-calendar-days icon"></i>
                            </div>
                            <div class="valid-feedback">
                                Looks good!
                            </div>
                        </div>
                        <div class="col-lg-6 col-md-6 col-sm-6">
                            <label for="validationCustom01">Dropping off time</label>
                            <div class="d-flex align-items-center input-con">
                                <input type="text" class="form-control input" placeholder="04:00 PM" required>
                                <i class="fa-solid fa-clock icon"></i>
                            </div>
                            <div class="valid-feedback">
                                Looks good!
                            </div>
                        </div>
                    </div>
                    <div class="row">
                        <div class="col-lg-6 col-md-6 col-sm-6">
                            <label for="validationCustom01">Type of vehicle</label>
                            <div class="d-flex align-items-center input-con">
                                <input type="text" class="form-control input" placeholder="First name" required>
                                <i class="fa-solid fa-location-dot"></i>
                            </div>
                            <div class="valid-feedback">
                                Looks good!
                            </div>
                        </div>
                        <div class="col-lg-6 col-md-6 col-sm-6">
                            <label for="validationCustom01">Number of passengers</label>
                            <div class="d-flex align-items-center input-con">
                                <input type="text" class="form-control input" placeholder="First name" required>
                                <i class="fa-solid fa-location-dot"></i>
                            </div>
                            <div class="valid-feedback">
                                Looks good!
                            </div>
                        </div>
                    </div>
                    <button class="btn" type="submit">Start Booking</button>
                </form>
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

.search-section{
    padding: 4rem 0;
}
.search-body {
    padding: 1rem 3rem;
}

h4 {
    color: #ffbe00;
    font-family: 'Poppins', 'sans-serif';
    font-weight: 600;
    margin-bottom: 20px;
}

h2 {
    font-family: 'Poppins', 'sans-serif';
    font-weight: 600;
    margin-bottom: 30px;
}

#search-des {
    font-family: 'Poppins', 'sans-serif';
    margin-bottom: 30px;
    opacity: 0.7;
    margin-bottom: 50px;
}
.input{
    border: none;
    background: white;
}
.input-con{
    border: 1px solid #ced6e0;
    padding: 10px 10px;
    margin-bottom: 25px;
    background: white;
}
label{
    margin-bottom: 10px;
    font-family: 'Poppins','sans-serif';
    font-weight: 600;
    font-size: 0.9rem;
}
.form-control:focus{
    border-color: inherit;
    -webkit-box-shadow: none;
    box-shadow: none;
    background: white;

}
.form-body{
    display: flex;
    align-items: center;
}
.icon{
    font-size: 1rem;
    color: #ffbe00;
}
.btn{
    background-color: #ffbe00;
    border-radius: 0px;
    padding: 1.25rem;
    width: 200px;
    font-weight: bold;  
    font-style: 'Poppins','sans-serif';
    margin-top: 15px;
}
.btn:hover{
    background-color: #ffa502;
}
.form-con{
    background-color: #f1f2f6;
    box-shadow: 20px 20px #ffbe00;
}

@media(max-width:1200px) {
    h4 {
        font-family: 'Poppins', 'sans-serif';
        font-weight: 600;
        color: #ffbe00;
        font-size: 1rem;
    }

    h2 {
        font-family: 'Poppins', 'sans-serif';
        font-weight: 600;
        margin: 20px 0;
        font-size: 1.2rem;
    }

    #search-des {
        font-family: 'Poppins', 'sans-serif';
        margin-bottom: 30px;
        opacity: 0.7;
        font-size: 0.7rem;
    }

    h5 {
        font-family: 'Poppins', 'sans-serif';
        font-weight: 600;
        font-style: italic;
        font-size: 0.9rem;
    }
    .btn{
        background-color: #ffbe00;
        border-radius: 0px;
        padding: 1rem;
        width: 175px;
        font-weight: bold;  
        font-style: 'Poppins','sans-serif';
        margin-top: 15px;
    }
}

@media(max-width:600px) {
    .search-text {
        text-align: center;
    }

    h4 {
        font-family: 'Poppins', 'sans-serif';
        font-weight: 600;
        color: #ffbe00;
        font-size: 1rem;
    }

    h2 {
        font-family: 'Poppins', 'sans-serif';
        font-weight: 600;
        margin: 20px 0;
        font-size: 1.2rem;
    }

    #search-des {
        font-family: 'Poppins', 'sans-serif';
        margin-bottom: 30px;
        opacity: 0.7;
        font-size: 0.7rem;
    }

    h5 {
        font-family: 'Poppins', 'sans-serif';
        font-weight: 600;
        font-style: italic;
        font-size: 0.9rem;
    }
    .form-body{
        padding: 0 3rem;
    }
    label{
        margin-bottom: 10px;
        font-family: 'Poppins','sans-serif';
        font-weight: 600;
        font-size: 0.8rem;
    }
    .input-con{
        border: 1px solid #ced6e0;
        padding: 5px 10px;
        margin-bottom: 25px;
        background: white;
    }
    .input{
        font-size: 0.9rem;
    }
    .btn{
        background-color: #ffbe00;
        border-radius: 0px;
        padding: 0.7rem;
        width: 125px;
        font-weight: bold;  
        font-style: 'Poppins','sans-serif';
        margin-top: 15px;
        font-size: 0.8rem;
    }
}

@media(max-width:400px) {
    h5 {
        font-family: 'Poppins', 'sans-serif';
        font-weight: 600;
        font-style: italic;
        font-size: 0.7rem;
    }
}
</style>