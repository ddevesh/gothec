<template>
    <div>
        <div class="m-h-10 d-flex flex-column justify-content-between my-5 font-big-1-2">
            <div class="d-flex flex-row justify-content-between">
<nav class="nav">
  <a class="gothec-home-tab  nav-link"  ><g-link to="/">Home</g-link></a>
  <a class="gothec-contact-tab nav-link"><g-link to="/contact">Contact</g-link></a>
</nav>

 

                
               
                <div class="d-flex flex-column justify-content-end">
                    <img src="../assets/logo.png" width="200" />
                </div>
            </div>
            <div>
                <div class="w-3 border-bottom"></div>
            </div>
        </div>

    </div>
</template>

<script>
    export default {
        name: "Header"
    }
</script>

<style scoped>

    .m-h-10 {

        min-height: 10rem;
    }
   
  

</style>