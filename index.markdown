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
}

@media screen and (min-width: 400px) {
    .container {
        width:100%
    }
    .cardText {
        font-size: 12px;
    }
}

@media screen and (min-width: 550px) {
    .container {
        width:100%
    }
    .cardText {
        font-size: 15px;
    }
}

@media screen and (min-width: 650px) {
    .container {
        width:100%
    }
    .cardText {
        font-size: 17px;
    }
}

@media screen and (min-width: 900px) {
    .container {
        width:100%
    }
    .cardText {
        font-size: 25px;
    }
}
</style>

<body> 
    <div>
        <h1 class="title">Bridgedy</h1>
        <img class="appIcon" src="/assets/BridgedyLogo.svg"> 
        <h1 class="subtitle">Import data to Apple Health in a private way</h1>
        <p style="color: gray; text-align: center">We are on Beta.</p>
    </div>
    <div class="container">
      <div id="left">
        <img src="/assets/homeScreenLateral.png"> 
      </div>
      <div id="middle">
      </div>
      <div id="right">
        <p class="cardText">Privacy is a fundamental human right so everyone should have an app to manage his health data in a private way.</p>
        <p class="cardText">Unfortunately many health and fitness apps take advantage of their access to your Apple Health data in their own benefit. With Bridgedy app you can export data to Apple Health in a private way.</p>
      </div>
    </div>
    <div class="container">
      <div id="left">
        <p class="cardText">Bridgedy app syncs perfectly with Apple Health so your health data is always up to date.</p>
        <p class="cardText" style="text-align: right">And Bridgedy does not take your data out of your iPhone so it is totally private and secure.</p>
      </div>
      <div id="middle">
      </div>
      <div id="right">
        <img src="/assets/authorizationScreenSE.png"> 
      </div>
    </div>
</body>

<!-- <body> 
    <div>
        <img class="appIcon" src="/assets/NeckTimerLogo_v2.svg"> 
    </div>
    <div>
        <h1 class="title">Track your back posture with Necktimer app</h1>
        <a href="https://apps.apple.com/us/app/necktimer/id6450180596"><img class="img" src="/assets/DownloadOnAppStoreBlack.svg"></a>
        <p style="color: gray; text-align: center">Now available in the USA, Canada, UK, Germany, The Netherlands and Spain.</p>
        <img class="img1" src="/assets/appHand.svg">
    </div>
    <div class="card">
      <div class="cardText">
        <br>
        <h1 style="color: #F8D8BD; font-weight: 600;">Measure it, improve it</h1>
        <h2 style="color: white; font-weight: 600;">You can only improve what you can measure. That is our main purpose regarding back posture habits, to provide you all the metrics and insights.</h2>
        <img src="/assets/statsCut.svg">
      </div>
    </div>
    <div class="card" style="background: white">
      <div class="cardText" style="text-align: right;">
        <img src="/assets/notificationsCut.svg">
        <br>
        <h1 style="color: #DA5540; font-weight: 600;">Always up to date</h1>
        <h2 style="font-weight: 600;">With NeckTimer Notifications you will be able to get alerts based on your customized maximum time for angle zone. And with Live Activities you can always be in touch with your current back posture metrics while doing something else.</h2>
        <br>
      </div>
    </div>
    <div class="card" style="background: linear-gradient(0deg, rgba(135,175,224,1) 0%, rgba(36,65,94,1) 100%);">
      <div class="cardText">
        <br>
        <h1 style="color: #B4BEF4; font-weight: 600;">Only yours</h1>
        <h2 style="color: white; font-weight: 600;">At NeckTimer we strongly believe that privacy is a fundamental human right. That is why we do not collect any sort of data. All the data keeps in your iPhone.</h2>
        <img src="/assets/lockCut.svg">
      </div>
    </div>
    <div class="card" style="background: white">
      <div class="cardText" style="text-align: right;">
        <img src="/assets/privacyCut.svg">
        <br>
        <h1 style="color: #568DCD; font-weight: 600;">You're in charge</h1>
        <h2 style="font-weight: 600;">The best way to protect your data for us is not taking it out of your iPhone. You are totally in charge of your data and you can delete it whenever you want or export it as a plain text file.</h2>
        <br>
      </div>
    </div>
    <div class="card" style="background: white;">
      <div class="cardText">
        <br>
        <h1 style="color: #459989; font-weight: 600;">A problem to be solved</h1>
        <h2 style="font-weight: 600;">Back pain is the main cause of years lived with disability and is the most common diagnosis responsible for sick leave. In 2020 back pain affected to 610 million people in the world and the projection is that by 2050 more than 840 million people will suffer back pain.</h2>
        <img style="width: 20%; margin-left: auto; margin-right: auto; display: block; margin-top: 30px;" src="/assets/The_Lancet_logo.svg.png">
        <a href="https://www.thelancet.com/journals/lanrhe/article/PIIS2665-9913(23)00098-X/fulltext"><p style="text-align: center; margin-top: 10px; padding-bottom: 20px;">Read full study</p></a>
      </div>
    </div>
</body> -->
