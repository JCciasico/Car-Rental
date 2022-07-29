<template>
    <div class="container">
        <div class="row border  ">
            <div class="col-lg-6 col-md-12 search-body border">
                <div class="search-text">
                    <h4>Search your Car</h4>
                    <h2>The every ocasion best rental car</h2>
                    <p id="search-des">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod temporincididunt ut
                        labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco
                        laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in
                        voluptate velit esse cillum dolore eu fugiat nulla pariatur.
                    </p>
                    <div>
                        <img src="../assets/car-rental.png" class="img-fluid" alt="">
                    </div>
                </div>
            </div>
            <div class="col-lg-6 col-md-12">form</div>
        </div>
    </div>
</template>

<script>
export default {

}
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,600;1,500&display=swap');

.search-body{
    padding: 1rem 3rem;
}
h4{
    color: #ffbe00;
    font-family: 'Poppins','sans-serif';
    font-weight: 600;
    margin-bottom: 20px;
}
h2{
    font-family: 'Poppins','sans-serif';
    font-weight: 600;
    margin-bottom: 30px;
}
#search-des{
    font-family: 'Poppins','sans-serif';
    margin-bottom: 30px;
    opacity: 0.7;
    margin-bottom: 50px;
}
@media(max-width:1200px){
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
    #search-des{
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
}
@media(max-width:600px){
    .search-text{
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
    #search-des{
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
}
@media(max-width:400px){
    h5{
        font-family: 'Poppins','sans-serif';
        font-weight: 600;
        font-style: italic; 
        font-size: 0.7rem;
    }
}

</style>