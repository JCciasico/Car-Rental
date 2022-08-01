<template>
  <section>
    <div class="container p-3">
        <div class="row dash-body">
            <div class="col text-center">
                <i class="fa-solid fa-users icon"></i>
                <h2>42500</h2>
                <span id="dash-text">Happy Clients</span>
            </div>
            <div class="col text-center">
                <i class="fa-solid fa-circle-dollar-to-slot icon"></i>
                <h2>12500</h2>
                <span id="dash-text">Trips Daily</span>
            </div>
            <div class="col text-center">
                <i class="fa-solid fa-hands-holding-child icon"></i>
                <h2>12500</h2>
                <span id="dash-text">Clients Annually</span>
            </div>
            <div class="col text-center">
                <i class="fa-solid fa-gauge-simple-high icon"></i>
                <h2>12500</h2>
                <span id="dash-text">Clients Annually</span>
            </div>
        </div>
        <div class="row gx-4 box-body">
            <div class="text-center p-4">
                <h4>Rent a Car</h4>
                <h2>Choose the Best Rent Car</h2>
            </div>
            <div class="col-lg col-md-12 col-sm-12 box-item">
                <div class="border box-1">
                    <i class="fa-solid fa-quote-right icon-1"></i>
                    <p class="text-des">It is a long established fact that a reader will be distracted by the readable content of a page when looking at its layouts. The point of using
                        is that it has a more normal distribution.
                    </p>
                    <div class="profile-body d-flex align-items-center">
                        <div class="pic p-3">
                            <i class="fa-solid fa-circle-user icon-profile"></i>
                        </div>
                        <div class="profile-info">
                            <span>Shin Nouzen</span>
                            <span>Head of Designer</span>
                        </div>
                    </div>
                </div>
            </div>
            <div class="col-lg col-md-12 col-sm-12 box-item">
                <div class="border box-1">
                    <i class="fa-solid fa-quote-right icon-1"></i>
                    <p class="text-des">It is a long established fact that a reader will be distracted by the readable content of a page when looking at its layouts. The point of using
                        is that it has a more normal distribution.
                    </p>
                    <div class="profile-body d-flex align-items-center">
                        <div class="pic p-3">
                            <i class="fa-solid fa-circle-user icon-profile"></i>
                        </div>
                        <div class="profile-info">
                            <span>Shin Nouzen</span>
                            <span>Head of Designer</span>
                        </div>
                    </div>
                </div>
            </div>
            <div class="col-lg col-md-12 col-sm-12 box-item">
                <div class="border box-1">
                    <i class="fa-solid fa-quote-right icon-1"></i>
                    <p class="text-des">It is a long established fact that a reader will be distracted by the readable content of a page when looking at its layouts. The point of using
                        is that it has a more normal distribution.
                    </p>
                    <div class="profile-body d-flex align-items-center">
                        <div class="pic p-3">
                            <i class="fa-solid fa-circle-user icon-profile"></i>
                        </div>
                        <div class="profile-info">
                            <span>Shin Nouzen</span>
                            <span>Head of Designer</span>
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

.icon{
    color: #ffbe00;
    font-size: 2.5em;
    padding: 1rem;
}
h2{
    color: white;
    font-family: 'Poppins','sans-serif';
    font-weight: 600;
}
#dash-text{
    color: white;
    font-family: 'Poppins','sans-serif';
    font-weight: 600;
}
.dash-body{
    padding: 5rem 0;
}
.box-body{
    padding: 2rem 0;
}
.box-item{
    margin-bottom: 60px;
}
.box-1{
    background-color: #f1f2f6;
    box-shadow: -10px 10px #ffbe00;
}
.icon-1{
    color: #ffbe00;
    font-size: 2.5em;
    padding: 1rem 1.5rem;
}
h4{
    color: #ffbe00;
    font-family: 'Poppins','sans-serif';
}
.text-des{
    padding: 0 2rem;
    color: black;
}
.icon-profile{
    font-size: 4em;
    color: #ffbe00;
}
.profile-info{
    display: flex;
    align-items: start;
    flex-direction: column;
}
.profile-body{
    padding-bottom: 1rem;
    padding-left: 1rem;
}
</style>