---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---
<style>
.appIcon {
    display: block;
    margin-left: auto;
    margin-right: auto;
    margin-top: 5%;
    width: 15%;
    border-radius: 20%;
}
.otherAppIcon {
    display: block;
    margin-left: auto;
    margin-right: auto;
    width: 15%;
    border-radius: 20%;
}
.title {
    display: block;
    text-align: center;
    margin-left: auto;
    margin-right: auto;
    margin-top: 10%;
    font-size: 50px;
    font-weight: 600;
    width: 80%;
    font-family: -apple-system;
}
.subtitle {
    display: block;
    text-align: center;
    margin-left: auto;
    margin-right: auto;
    margin-top: 10%;
    font-size: 40px;
    font-weight: 600;
    width: 80%;
    font-family: -apple-system;
}
.text {
    display: block;
    text-align: left;
    margin-left: auto;
    margin-right: auto;
    margin-top: 10%;
    font-size: 20px;
    font-weight: 300;
    width: 100%;
    font-family: -apple-system;
}
.img {
    display: block;
    margin-left: auto;
    margin-right: auto;
    margin-top: 30px;
    margin-bottom: 15px;
    width: 20%;
}
.otherImg {
    margin-top: -40px;
    margin-bottom: 0px;
}
.anotherImg {
    display: block;
    margin-top: 30px;
    margin-bottom: 15px;
    margin-left: auto;
    margin-right: auto;
}
.img1 {
    display: block;
    margin-left: auto;
    margin-right: auto;
    width: 100%;
    border-radius: 20%;
}
.card {
  background: linear-gradient(0deg, rgba(212,138,83,1) 0%, rgba(179,80,75,1) 100%);
  border-radius: 20px;
  font-family: -apple-system;
  width: 100%;
  margin-top: 10%;
  margin-left: auto;
  margin-right: auto;
}
.cardText {
  text-align: left;
  width: 90%;
  margin-left: auto;
  margin-right: auto;
  font-family: Helvetica;
  vertical-align: center;
  text-align: left;
}
.cardTextTitle {
  text-align: left;
  width: 90%;
  margin-left: auto;
  margin-right: auto;
  font-family: Helvetica;
  font-weight: bold;
  vertical-align: center;
  text-align: left;
}
.container {
    margin-top: 120px;
    height: 100%; 
    width:80%; 
    margin-left: auto; 
    margin-right: auto;
    text-align: center;
    font-family: -apple-system;
    vertical-align: center;
}
#left, #middle, #right {display: inline-block; *display: inline; zoom: 1; vertical-align: middle; font-size: 12px;}
#left {width: 35%}
#middle {width: 10%}
#right {width: 35%}

@media screen and (min-width: 350px) {
    .container {
        width:100%
    }
    .cardText {
        font-size: 9px;
    }
    .cardTextTitle {
        font-size: 15px;
    }
}

@media screen and (min-width: 400px) {
    .container {
        width:100%
    }
    .cardText {
        font-size: 12px;
    }
    .cardTextTitle {
        font-size: 19px;
    }
}

@media screen and (min-width: 550px) {
    .container {
        width:100%
    }
    .cardText {
        font-size: 15px;
    }
    .cardTextTitle {
        font-size: 21px;
    }
}

@media screen and (min-width: 650px) {
    .container {
        width:100%
    }
    .cardText {
        font-size: 17px;
    }
    .cardTextTitle {
        font-size: 23px;
    }
}

@media screen and (min-width: 900px) {
    .container {
        width:100%
    }
    .cardText {
        font-size: 25px;
    }
    .cardTextTitle {
        font-size: 31px;
    }
}
</style>

<body> 
    <div>
        <h1 class="title">Bridgedy</h1>
        <img class="appIcon" src="/assets/BridgedyLogo.svg"> 
        <h1 class="subtitle">Export data to Apple Health in a private way</h1>
        <a href="https://itunes.apple.com/WebObjects/MZStore.woa/wa/viewSoftware?id=6476464397"><img class="anotherImg" src="/assets/DownloadAppStore_white.svg"></a>
        <p style="color: gray; text-align: center">Now available in the USA, Canada, UK, the Netherlands and Spain.</p>
    </div>
    <div class="container">
      <div id="left">
        <img src="/assets/homeScreen.png"> 
      </div>
      <div id="middle">
      </div>
      <div id="right">
        <p class="cardTextTitle">Privacy</p>
        <p class="cardText">Unfortunately many health and fitness apps take advantage of their access to your Apple Health data in their own benefit.</p>
        <p class="cardText">With Bridgedy app you can export data to Apple Health in a private way.</p>
      </div>
    </div>
    <div class="container">
      <div id="left">
      <p class="cardTextTitle" style="text-align: right">Apple Health</p>
        <p class="cardText" style="text-align: right">Bridgedy app syncs perfectly with Apple Health so your health data is always up to date.</p>
        <p class="cardText" style="text-align: right">And Bridgedy does not take your data out of your iPhone so it is totally private and secure.</p>
      </div>
      <div id="middle">
      </div>
      <div id="right">
        <img src="/assets/authorizationScreenSE.png"> 
      </div>
    </div>
    <div class="container">
      <div id="left">
        <img src="/assets/widgetScreen.png"> 
      </div>
      <div id="middle">
      </div>
      <div id="right">
        <p class="cardTextTitle">Accessible and handy</p>
        <p class="cardText">Bridgedy app is designed with people with other abilities in mind.</p>
        <p class="cardText">And it also brings features like interactive widgets to make your life easier.</p>
      </div>
    </div>
    <div class="container">
      <div id="left">
      <p class="cardTextTitle" style="text-align: right">Teaming up with Necktimer</p>
        <p class="cardText" style="text-align: right">Bridgedy is committed to foster human beings health so it has team up with Necktimer app.</p>
      </div>
      <div id="middle">
      </div>
      <div id="right">
        <img class = "otherImg" src="/assets/necktimerApp.png">
        <a href="https://apps.apple.com/us/app/necktimer/id6450180596"><img class="otherImg" src="/assets/DownloadAppStore_white.svg"></a>
      </div>
    </div>
</body>
