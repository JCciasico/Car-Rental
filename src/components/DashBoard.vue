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
}
#dash-text{
    color: white;
    font-family: 'Poppins','sans-serif';
    font-weight: 600;
}
.dash-body{
    padding: 5rem 0;
}
</style>