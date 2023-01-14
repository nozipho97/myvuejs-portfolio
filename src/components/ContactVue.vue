<template>
    
    <section id="contact">
  
        <h1 class="section-header">Contact</h1>
        
        <div class="contact-wrapper">
        
        <!-- Left contact page --> 
          
          <form id="contact-form" class="form-horizontal" role="form">
             
            <div class="form-group">
              <div class="col-sm-12">
                <input type="text" class="form-control" id="name" placeholder="NAME" name="name">
              </div>
            </div>
      
            <div class="form-group">
              <div class="col-sm-12">
                <input type="email" class="form-control" id="email" placeholder="EMAIL" name="email">
              </div>
            </div>
      
            <textarea class="form-control" rows="10" placeholder="MESSAGE" name="message" required></textarea>
            
            <button class="btn btn-primary send-button" id="submit" type="submit" value="SEND">
              <div class="alt-send-button">
                <i class="fa fa-paper-plane"></i><span class="send-text">SEND</span>
              </div>
            
            </button>
            
          </form>
          
        <!-- Left contact page --> 
          
            <div class="direct-contact-container">
      
              <ul class="contact-list">
                <li class="list-item"><i class="fa fa-map-marker fa-2x"><span class="contact-text place">314 Imam Haron Rd</span></i></li>
                
                <li class="list-item"><i class="fa fa-phone fa-2x"><span class="contact-text phone"><a href="tel:068 326 4041" title="Give me a call">(068)326 4041 </a></span></i></li>
                
                <li class="list-item"><i class="fa fa-envelope fa-2x"><span class="contact-text gmail"><a href="email:#" title="Send me an email">mayilanozipho@gmail.com</a></span></i></li>
                
              </ul>
      
            </div>
          
        </div>
        
      </section>  
        

</template>

<script>
export default {
name:'ContactVue'
}
</script>

<style scoped>
body {
    margin: 0;
    padding: 0;
    background-color: sandybrown;
    padding-bottom: 100px;
    
  }

section{
    background-color: saddlebrown;
}
  
  #contact {
    width: 100%;
    height: 100%;
  }
  
  .section-header {
    text-align: center;
    margin: 0 auto;
    padding: 40px 0;
    font: 300 60px 'Oswald', sans-serif;
    color: sandybrown;
    text-transform: uppercase;
    letter-spacing: 6px;
  }
  
  .contact-wrapper {
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    margin: 0 auto;
    padding: 20px;
    position: relative;
    max-width: 840px;
  }
  
  /* Left contact page */
  .form-horizontal {
    /*float: left;*/
    max-width: 400px;
    font-family: 'Lato';
    font-weight: 400;
  }
  
  .form-control, 
  textarea {
    max-width: 400px;
    background-color: sandybrown;
    color: #fff;
    letter-spacing: 1px;
  }
  
  .send-button {
    margin-top: 15px;
    height: 34px;
    width: 400px;
    overflow: hidden;
    transition: all .2s ease-in-out;
  }
  
  .alt-send-button {
    width: 400px;
    height: 34px;
    transition: all .2s ease-in-out;
  }
  
  .send-text {
    display: block;
    margin-top: 10px;
    font: 700 12px 'Lato', sans-serif;
    letter-spacing: 2px;
  }
  
  .alt-send-button:hover {
    transform: translate3d(0px, -29px, 0px);
  }
  
  /* Begin Right Contact Page */
  .direct-contact-container {
    max-width: 400px;
  }
  
  /* Location, Phone, Email Section */
  .contact-list {
    list-style-type: none;
    margin-left: -30px;
    padding-right: 20px;
  }
  
  .list-item {
    line-height: 4;
    color: #aaa;
  }
  
  .contact-text {
    font: 300 18px 'Lato', sans-serif;
    letter-spacing: 1.9px;
    color: #bbb;
  }
  
  .place {
    margin-left: 62px;
  }
  
  .phone {
    margin-left: 56px;
  }
  
  .gmail {
    margin-left: 53px;
  }
  
  .contact-text a {
    color: #bbb;
    text-decoration: none;
    transition-duration: 0.2s;
  }
  
  .contact-text a:hover {
    color: sandybrown;
    text-decoration: none;
  }
  
  
  
  /* Begin Media Queries*/
  @media screen and (max-width: 850px) {
    .contact-wrapper {
      display: flex;
      flex-direction: column;
    }
    .direct-contact-container, .form-horizontal {
      margin: 0 auto;
    }  
    
    .direct-contact-container {
      margin-top: 60px;
      max-width: 300px;
      
     }
  }
  
  @media screen and (max-width: 569px) {
  
    .direct-contact-container, .form-wrapper {
      float: none;
      margin: 0 auto;
    }  
    .form-control, textarea {
      
      margin: 0 auto;
    }
   
    
    .name, .email, textarea {
      width: 280px;
    } 
    
    .direct-contact-container {
      margin-top: 60px;
      max-width: 280px;
    }  
   
  }
  
  @media screen and (max-width: 410px) {
    .send-button {
      width: 99%;
    }
  }
</style>