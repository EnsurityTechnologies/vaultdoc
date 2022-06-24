---
date: "2020-08-20T15:41:15.543Z"
description: Footer
title: Footer
---
<style type="text/css">

.footer-gray {
  width: 100%;
  color: #888;
}

.footer-custom {
  font: normal normal 12px/1.4 sans-serif;
  /*max-width: 1008px;*/
  box-sizing: border-box;
  margin: 0 auto;
  padding: 24px;
}

.footer-custom:after {
  display: table;
  clear: both;
  content: "";
}

.footer-lists:after {
  display: table;
  clear: both;
  content: "";
}

.ftr-hdr {
  color: white;
  font: 22px/1.4  sans-serif;
  margin: 1em 0 0;
}

@media only screen and (min-width: 768px) {
  .ftr-hdr {
    font-size: 18px;
  }
}

.footer-list-wrap {
  width: 50%;
  float: left;
  box-sizing: border-box;
}

@media only screen and (min-width: 568px) {
  .footer-list-wrap {
    width: 33.3333%;
  }
}

@media only screen and (min-width: 768px) {
  .footer-list-wrap {
    width: 25%;
  }
}

.ftr-links-sub {
  padding: 0;
  margin: 0;
}

.ftr-links-sub:after {
  display: table;
  clear: both;
  content: "";
}

.ftr-links-sub li {
  display: block;
  list-style-type: none;
  margin: 0;
  padding: 3px 0;
  color: #888;
  font: normal normal 12px sans-serif;
  text-transform: uppercase;
  /*width: 150px;*/
}

.footer-custom a,
.footer-custom a:link,
.footer-custom a:visited,
.ftr-links-sub li .link {
  text-decoration: none;
  color: #888;
  padding: 5px 0;
  display: block;
}

.footer-custom .footer-legal a {
  display: inline;
}

.footer-custom a:hover,
.footer-custom a:active,
.ftr-links-sub li .link:hover {
  text-decoration: underline;
  color: #888;
  cursor: pointer;
}

@media only screen and (min-width: 768px) {
  .footer-custom a, .footer-custom a:link, .footer-custom a:visited, .ftr-links-sub li .link {
    padding: 0;
  }
}
/* BEGIN EMAIL CAPTURE STYLES*/

.footer-email {
  text-align: center;
}

#ftrEmailForm {
  height: 44px;
}

#ftrEmailForm .error {
  display: none;
  color: red;
  text-align: left;
}

#ftrEmailForm #ftrEmailInput {
  background: none repeat scroll 0 0 #FFF;
  border: 1px solid #D6D6D6;
  box-sizing: border-box;
  color: #888;
  float: left;
  font: normal normal 14px/1.4 sans-serif;
  padding: 5px;
  width: 70%;
  height: 100%;
}

#ftrEmailForm #ftrEmailInput:hover {
  border: 1px solid #888;
}

#ftrEmailForm #ftrEmailInput:focus {
  border: 1px solid #ef9223;
  outline: #ef9223 auto 5px;
}

#ftrEmailForm .button {
  width: 30%;
  height: 100%;
  padding: 5px;
  float: left;
  border: 1px solid #DFDFDF;
  box-sizing: border-box;
  color: #000;
  font: normal bold 18px/1 sans-serif;
  text-align: center;
  text-transform: uppercase;
  background: #FFF;
  background: url(data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiA/Pgo8c3ZnIHhtbG5zPSJod…EiIGhlaWdodD0iMSIgZmlsbD0idXJsKCNncmFkLXVjZ2ctZ2VuZXJhdGVkKSIgLz4KPC9zdmc+);
  background: -webkit-gradient(linear, left top, left bottom, color-stop(0%, white), color-stop(100%, #e1e1e1));
  background: -webkit-linear-gradient(top, white 0, #e1e1e1 100%);
  background: -moz-linear-gradient(top, white 0, #e1e1e1 100%);
  background: -ms-linear-gradient(top, white 0, #e1e1e1 100%);
  background: -o-linear-gradient(top, white 0, #e1e1e1 100%);
  background: linear-gradient(to bottom, white 0, #e1e1e1 100%);
  cursor: pointer;
  vertical-align: middle;
  outline: none;
}

#ftrEmailForm .button:hover,
#ftrEmailForm .button:active {
  background: black;
  color: #FFF;
  outline: none;
}
/* BEGIN SOCIAL STYLES*/

.footer-social {
  text-align: center;
}

.footer-social ul {
  padding: 0;
  display: inline-block;
  list-style-type: none;
}

.footer-social ul:after {
  display: table;
  clear: both;
  content: "";
}

.footer-social li {
  float: left;
  margin: 0 15px 0 0;
  padding: 0;
}

@media only screen and (min-width: 768px) {
  .footer-lists {
    width: 100%;
  }
  .footer-email {
    width: 50%;
    float: left;
    text-align: left;
  }
  .footer-social {
    width: 45%;
    margin-left: 5%;
    float: left;
    text-align: left;
  }
}

.center {
  padding-top:12px;
  margin-left: auto;
  margin-right: auto;
  width: 50%;
}

@media only screen and (min-width: 1008px) {
  .footer-lists {
    width: 66.6666%;
    float: left;
  }
  .footer-email {
    width: 33.3333%;
  }
  .footer-social {
    width: 33.3333%;
    float: right;
    margin-left: 0;
  }
}

.footer-legal {
  padding: 15px 0 0;
  clear: left;
}

.footer-payment {
  text-align: center;
}

@media only screen and (min-width: 768px) {
  .footer-legal {
    width: 66.6666%;
    float: left;
  }
  .footer-payment {
    width: 33.3333%;
    float: left;
  }
}

@media only screen and (min-width: 1008px) {
  .footer-payment {
    text-align: left;
  }
}

.footer-payment ul {
  padding: 0;
  display: inline-block;
  list-style-type: none;
}

.footer-payment ul li {
  display: inline-block;
  margin: 0 6px;
}

@media only screen and (min-width: 1008px) {
  .footer-payment ul li.ftr-stella {
    margin-left: 0;
  }
}


footer{
  background: #fff !important;
}

.contentBorderRadius {
    padding: 0px;
    background:#333;
    border-radius:30px 30px 20px 20px !important;
    max-width: 100% !important;

}
footer.footer.contentBorderRadiusInside {
    background: #333 !important;
    
}

section.finalfooter {
    font-size: 11px;
    background: #000;
    border-radius: 0px 0px 30px 30px;
}

.socailicons {
    display: table;
    width: 100%;
    border-bottom: 1px solid #ddd;
    box-shadow: inset 0px -2px 2px -2px rgb(52 52 52);
    padding-bottom: 30px;
    margin-bottom: 30px;
    padding:30px
}

.footerLogo {
    float: left;
    position: relative;
    top: 5px;
}

.footerlinks {
    display: table;
    float: right;
    position: relative;
}

    .footerlinks ul {
        margin: 0;
        padding: 0;
    }

        .footerlinks ul li {
            list-style: none;
            margin: 0 5px;
            float: left
        }

            .footerlinks ul li a {
                position: relative;
                display: block;
                width: 50px;
                height: 50px;
                text-align: center;
                line-height: 49px;
                background: #000;
                border-radius: 50%;
                font-size: 25px;
                color: #666;
                transition: .5s;
            }

      .footerlinks ul li a::before {
          content: '';
          position: absolute;
          top: 0;
          left: 0;
          width: 100%;
          height: 100%;
          border-radius: 50%;
          background: #61b5f7;
          transition: .5s;
          transform: scale(.9);
          z-index: -1;
      }

      .footerlinks ul li a:hover::before {
          transform: scale(1.1);
          box-shadow: 0 0 15px #61b5f7;
      }

      .footerlinks ul li a:hover {
          color: #1194ff;
          box-shadow: 0 0 5px #1194ff;
          text-shadow: 0 0 5px #1194ff;
      }

.footer h4 {
    font-weight: bold;
    color: #fff;
}

ul.footer-links {
    padding: 0px;
}

    ul.footer-links li {
        list-style: none;
        padding: 5px;
    }

    ul.footer-links a {
        color: #fff;
        text-decoration: none;
        transition: all 0.3s ease;
    }

        ul.footer-links a:hover {
            text-shadow: 1px 1px 1px #61b5f7;
        }

.footer h5 {
    color: #fff;
}

.finalfooter p{
  margin-bottom:5px !important;
  margin-top:5px !important;
}



</style>



<section class="contentBorderRadius">
        <div class="footer contentBorderRadiusInside">
            <div class="container-fluid">
                <div class="row">
                    <div class="col-md-12">
                        <div class="socailicons">
                            <div class="footerLogo">
                                <a href="/"><img src="data:image/png;base64,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" alt="Ensurity Logo"></a>
                            </div>
                            <div class="footerlinks">
                                <ul>
                                    <li>
                                        <a href="https://www.facebook.com/EnsurityTech/" target="_blank">
                                            <img src="data:image/png;base64,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" class="center" ></img>
                                        </a>
                                    </li>
                                    <li>
                                        <a href="https://www.youtube.com/channel/UCPsYVSci8BuAB61cGyzTdcw/featured" target="_blank">
                                            <i class="fa fa-youtube-play"></i>
                                        </a>
                                    </li>
                                    <li>
                                        <a href="https://www.linkedin.com/company/ensurity/" target="_blank">
                                            <i class="fa fa-linkedin"></i>
                                        </a>
                                    </li>
                                    <li>
                                        <a href="https://twitter.com/ensuritytech" target="_blank">
                                            <i class="fa fa-twitter"></i>
                                        </a>
                                    </li>
                                </ul>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="row mobPadding justify-content-center">
                    <div class="col-md-2">
                        <h4>Company</h4>
                        <ul class="footer-links">
                            <li><a href="/About"> About us</a></li>
                            <li><a href="/About/#Leadership"> Leadership</a></li>
                            <li><a href="/#Customers"> Customers</a></li>
                            <li><a href="/About/#Careers"> Careers</a></li>
                            <li><a href="/Products/ThinC_AUTH/#Resources">Resources</a></li>
                            <li><a href="/Contact">Contact Us</a></li>
                        </ul>
                    </div>
                    <div class="col-md-6">
                        <h4>Products</h4>
                        <div class="row">
                            <div class="col-md-12">
                                <ul class="productlinks">
                                    <li>
                                        <a href="/Products/ThinC_AUTH">ThinC-AUTH (Biometric Security Key)</a><br>
                                        <a href="https://www.twitter.com/ThinC_AUTH"><i class="fa fa-twitter" style="color:#5499ff "></i></a>
                                    </li>
                                    <li>
                                        <a href="/Products/XSense">XSense Passwordless</a><br>
                                        <a href="https://twitter.com/XSenseID"><i class="fa fa-twitter" style="color:#5499ff "></i></a>
                                    </li>
                                    <li><a href="/Products/ARC">ARC (Assured Remote Computing)</a></li>
                                </ul>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            <section class="finalfooter">
                <div class="container-fluid">
                    <div class="row">
                    <div class="container">
                    <div class="row">
                        <div class="col-md-6">
                            <p class="footerleft">
                                Copyright © Ensurity. All rights reserved.
                            </p>
                        </div>
                        <div class="col-md-6">
                            <p class="footerright"> <a href="/Policies/privacy">Privacy Policy</a> / <a href="/Policies/cookie">Cookie Policy</a> / <a href="/Policies/terms">Terms of Use</a> / <a href="/Policies/disclaimer">Disclaimer</a> / <a href="/Policies/tc">Terms &amp; Conditions</a> / <a href="/Policies/refund">Refund Policy</a></p>
                        </div>
                    </div>
                    </div>
                    </div>
                </div>
            </section>
        </div>
    </section>
  <!--/.footer-gray-->