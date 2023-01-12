<template >
  <div id="about-section">
    <div class="Heading">
        <h3 calss="About">About</h3>
    </div>
      <div class="about">
        <div class="container">
          <div class="child1">
            <h1>Nozipho Mayila</h1>
            <p>25 Years And I Am A Student At Life Choices Academy Doing Front End Development. A Very Dedicated Young Lady With A Passion In Web Programming.</p>
            <div class="row">
              <div class="info">
                <h3><span>Name: </span> Nozipho Mayila</h3>
                <h3><span>Qualification: </span>Qualified programmer</h3>
                <h3><span>Post: </span>Front end developer</h3>
                <h3><span>Language: </span>English</h3>
              </div>
            </div>
          </div>
        </div>
      </div>    
          <div class="child2">
            <img alt="logo" src="https://i.postimg.cc/SRRk1Pw0/Nozipho-Mayila-picture-1.jpg">
          </div>
        </div>

  <div class="progress-bar">
    <h1 class="heading"><span>My</span> skills</h1>
    <div class="container">
        <div class="progress">
            <div class="progress-bar bg-warning"
                style="width:90%;">
                HTML
            </div>
      </div><br>

        <div class="progress">
            <div class="progress-bar bg-warning"
                style="width:90%;">
                CSS
            </div>
        </div><br>
        <div class="progress">
            <div class="progress-bar bg-warning"
                style="width:85%;">
                BOOTSTRAP
            </div>
        </div><br>
        <div class="progress">
            <div class="progress-bar bg-warning"
                style="width:75%;">
                PYTHON
            </div>
        </div><br>
        <div class="progress">
            <div class="progress-bar bg-warning"
                style="width:65%;">
                VUE 
            </div>
        </div><br>
        
    </div>
  </div>

</template>
<script>
export default {
    name: "AboutVue"
  }

</script>
<style scoped>

#about-section{
    padding-top:125px;
}
.about{
    border: 1px solid black;
    margin: 1rem;
    padding: 2rem 2rem;
    text-align: center;
    
  }
  
  .child1{
    display: inline-block;
    border: 1px solid red;
    padding: 1rem 1rem;
    vertical-align: middle;
  }
  
  .child2{
    display: inline-block;
    border: 1px solid red;
    padding: 1rem 1rem;
    vertical-align: middle;
  }
   
   
</style> 