<template>
    <section class="contact" id="contact">
        <h1 class="heading"> <span>contact </span>me</h1>

        <link rel="stylesheet" href="https://formspree.io/f/xpznoejl">
        <section class="form-group">
        <div class="box-container">
        <div class="box">
        <label for="user">Name:</label>
        <input type="text" required class="form-control" id="user">
        </div>

        <div class="form-group">
        <label for="pwd">Email address:</label>
        <textarea name="form-control"  rows="1"></textarea>
        <input type="email" class="form-control" id="pwd">
        </div>

        <div class="form-group">
        <label for="comment">Messege:</label>
        <textarea class="form-control" rows="5" id="comment"></textarea>
        <button type="button" class="btn btn-warning">Submit</button>
        </div>
        </div>

        <div class="box-container">
        <div class="content-f">
            <h3>contact info</h3>
            <div class="info">
            <h4><i class="fas fa-envelope"></i>mayilanozipho@gmail.com</h4>
            <h4><i class="fas fa-phone"></i>+27 68 326 4041</h4>
            <h4><i class="fas fa-phone"></i>+27 71 500 9730</h4>
            <h4><i class="fas fa-map-pin"></i><a href="https://www.google.com/search?q=314+imam+haron+road&oq=314&aqs=chrome.6.69i57j46i512j0i67j46i175i199i512j0i512l6.3586j1j15&sourceid=chrome&ie=UTF-8#">314 imam haron rd, lansdowne, cape town - 7780</a></h4>
            </div>
        </div>
        </div>
    </section>
    </section>

</template>

<script>
export default {
name:'ContactVue'
}
</script>