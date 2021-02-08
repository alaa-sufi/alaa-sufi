<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/twitter-bootstrap/4.5.0/css/bootstrap.min.css"/>
    <style>
      
.about {
  position: relative;
  background: #293742;
  background-image: radial-gradient(circle farthest-corner at 50% 120%, #4f6373 30%, #293742 77.2%);
  filter: progid:DXImageTransform.Microsoft.gradient(startColorstr="#4f6373",endColorstr="#293742",GradientType=1);
  z-index: 0;
  overflow: hidden;
}

.about:after {
  content: "portfolioportfolio";
  position: absolute;
  left: 0;
  top: 20%;
  -webkit-transform: translateY(-50%);
          transform: translateY(-50%);
  font-size: 20vw;
  opacity: 0.2;
  color: #4f6373;
  z-index: -1;
}

@media (max-width: 576px) {
  .about {
    padding: 1.5rem 0;
  }
}

@media (min-width: 577px) {
  .about {
    padding: 2rem 0;
  }
}

@media (min-width: 768px) {
  .about {
    padding: 2.2rem 0;
  }
}

@media (min-width: 992px) {
  .about {
    padding: 2.5rem 0;
  }
}

.about {
  height: 100vh;
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-pack: center;
      -ms-flex-pack: center;
          justify-content: center;
  -webkit-box-align: center;
      -ms-flex-align: center;
          align-items: center;
}

.about .main {
  padding-top: 1.5rem;
  padding-bottom: 1.5rem;
}

.about .main .img img {
  display: block;
}

@media (max-width: 576px) {
  .about .main .img img {
    width: 70%;
  }
}

@media (min-width: 577px) {
  .about .main .img img {
    width: 60%;
  }
}

@media (min-width: 768px) {
  .about .main .img img {
    width: 90%;
  }
}

@media (min-width: 992px) {
  .about .main .img img {
    width: 100%;
  }
}

@media (max-width: 576px) {
  .about .main .img img {
    margin: 1.5rem auto;
  }
}

@media (min-width: 577px) {
  .about .main .img img {
    margin: 2rem auto;
  }
}

@media (min-width: 768px) {
  .about .main .img img {
    margin: 0 0 0 auto;
  }
}

@media (min-width: 992px) {
  .about .main .img img {
    margin: 0 0 0 auto;
  }
}

.about .main .text-about {
  margin: auto;
}

.about .main .text-about h2 {
  color: #ef3365;
  font-weight: bold;
}

@media (max-width: 576px) {
  .about .main .text-about h2 {
    font-size: 3rem;
  }
}

@media (min-width: 577px) {
  .about .main .text-about h2 {
    font-size: 3rem;
  }
}

@media (min-width: 768px) {
  .about .main .text-about h2 {
    font-size: 3.5rem;
  }
}

@media (min-width: 992px) {
  .about .main .text-about h2 {
    font-size: 4rem;
  }
}

.about .main .text-about p {
  color: white;
  font-size: 2rem;
}

@media (max-width: 576px) {
  .about .main .text-about p {
    font-size: 1.5rem;
  }
}

@media (min-width: 577px) {
  .about .main .text-about p {
    font-size: 1.5rem;
  }
}

@media (min-width: 768px) {
  .about .main .text-about p {
    font-size: 1.7rem;
  }
}

@media (min-width: 992px) {
  .about .main .text-about p {
    font-size: 2rem;
  }
}

.about .main .text-about p a {
  cursor: pointer;
  color: #ef3365;
}

.about .footer {
  bottom: 0;
  margin: auto 0 0  0;
  position: absolute;
  bottom: 0;
  right: 15px;
}

@media (max-width: 576px) {
  .about .footer {
    bottom: 1.5rem;
  }
}

@media (min-width: 577px) {
  .about .footer {
    bottom: 2rem;
  }
}

@media (min-width: 768px) {
  .about .footer {
    bottom: 2.2rem;
  }
}

@media (min-width: 992px) {
  .about .footer {
    bottom: 2.5rem;
  }
}

.footer {
  text-align: right;
}

.footer h1 {
  color: white;
  font-weight: 700;
  letter-spacing: -3px;
  line-height: 1;
}

@media (max-width: 576px) {
  .footer h1 {
    font-size: 2.5rem;
  }
}

@media (min-width: 577px) {
  .footer h1 {
    font-size: 3rem;
  }
}

@media (min-width: 768px) {
  .footer h1 {
    font-size: 3.5rem;
  }
}

@media (min-width: 992px) {
  .footer h1 {
    font-size: 4rem;
  }
}

.footer span {
  content: "";
  background: #ef3365;
  width: 10px;
  height: 10px;
  display: inline-block;
  border-radius: 50%;
  line-height: 1;
}
    </style>
  </head>
  <body>
    <!-- about -->
    <div class="about" id="about">
      <div class="container">
          <div class="main row">
            <div class="text-about col-md-7 col-12 text-center text-sm-left">
              <h2>Hey, hi, hello!</h2>
              <p>
                My name is Alaa Sufi<br />
                I am a junior front end developer<br />
                I love all things technical.<br />
                But don't take my word for it<br />
                check my <a href="https://alaa-sufi-portfolio.netlify.app/#projects">projects</a> out.Talk soon!
              </p>
            </div>
            <div class="img col-md-5 col-12 d-none d-md-block">
              <img src="img/about‫‬.png" alt="about" />
            </div>
          </div>
          <div class="footer col-12">
            <h1 ><span></span>about me</h1>
          </div>
      </div>
    </div>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/twitter-bootstrap/4.5.3/js/bootstrap.min.js"></script>
  </body>
</html>
