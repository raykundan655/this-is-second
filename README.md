<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    
    <title>Contact Us</title>
    
    <style>
    body{
        background-image: url("https://media.istockphoto.com/id/685111998/photo/young-girl-dancing-to-the-music.jpg?s=612x612&w=0&k=20&c=XA8XG5Fyge1eR-69FeRbXwIj7mVgnhrTLDb9TJhxb24=");
        background-size:cover;
        background-position:center;
        align-items:center;
        display:flex;
        justify-content:center;
        align-items:center;
        background-repeat:no-repeat;
        overflow: hidden;
    }
    label{
            display:block;
            margin-bottom:10px;
        }
    

.contact-container {
  max-width: 700px;
  margin: 32px auto;
  font-family: "Roboto", sans-serif;
  color: #023047;
  padding: 0 32px;
  background-color:rgba(255,255,255,0.77);    /* background blur image /creating a box */
  border-radius: 10px;
  padding:50px;
  width:400px;
}

.contact-container,
.contact-container * {
  box-sizing: border-box;    /*website ko or input box ko proper padding dere h*/
}


.contact-container h2 {
  font-size: 48px;
  margin: 0;
}

.contact-container .sub-heading {
  font-size: 16px;
  margin-top: 8px;
  line-height: 1.8;
  position: relative;
}



.contact-container form {
  display: flex;
  flex-direction: column;
  gap: 8px;
  margin-top: 32px;
}

.contact-container form input,
.contact-container form textarea {
  width: 100%;
  padding: 10px 16px;
  font-size: 16px;
  border: 0;
  border-radius: 4px;
  box-shadow: 0 5px 15px 0 rgba(119, 117, 117, 0.15);
  font-family: "Roboto", sans-serif;
  padding-left: 36px;    /*set padding for send button*/
}

.contact-container form input:focus,                                 /* to add blue outline on clicking*/
.contact-container form textarea:focus {
  outline: 1px solid #0096c7;
}

.contact-container form textarea {
  height: 140px;
  padding-left: 16px;
}



.contact-container .btn-container {
  width: 160px;
  margin-top: 8px;
  transition: all 300ms ease;
}



.contact-container input[type="submit"] {
  background: #023047 ;
  color: #fff;
  text-align: left;
  cursor: pointer;
}

.contact-container .top-section {
  display: flex;
  gap: 16px;
  margin-bottom: 12px;
}

.contact-container .group {
  flex: 1;
  display: flex;
  gap: 8px;
  flex-direction: column;
}


    </style>
  </head>
  <body>
    <div class="contact-container">
      <h2>Get In Touch</h2>
      <p class="sub-heading">
        Have any question,comment,or feedback? Please leave your thoughts about us!
      </p>

      <form action="">
        <div class="top-section">
          <div class="group">
            <label for="fullname">Your Name</label>
            <div class="input-container">
              
              <input type="text" id="fullname" />
            </div>
          </div>

          <div class="group">
            <label for="email">Your Email</label>
            <div class="input-container">
              
              <input type="text" id="email" />
            </div>
          </div>
        </div>
        <div class="group">
            <label for="message">Message</label>
            <textarea name="" id="message"></textarea>
          </div>
  
          <div class="btn-container">
            <input type="submit" value="Send" />
          </div>
  
          
        </form>
      </div>
    </body>
</html>
