# Four-card-feature-section

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Four Card Feature Section</title>
</head>

<body>
    <div class="layout">
        <div class="content">
            <header class="header">
                <div class="information">
                    <h2 class="top-title">Reliable, efficient delivery</h2>
                    <h2 class="title">Powered by Technology</h2>
                    <p>
                        Our artificial intelligence powered tools use millions of project data points to ensure that
                        your
                        project is successfull
                    </p>
                </div>
            </header>
            <div class="main">
                <div class="row">
                    <article class="item-card">
                        <span class="line-top"></span>
                        <h3>Supervisor</h3>
                        <p>Monitors activity to indentity project roadblocks</p>
                        <img src="icon-supervisor.svg" alt="supervisor">
                    </article>
                </div>
                <div class="row">
                    <article class="item-card">
                        <span class="line-top"></span>
                        <h3>Team Builder</h3>
                        <p>Scans our talent network to create the optimal team of your project.</p>
                        <img src="icon-team-builder.svg" alt="Team builder">
                    </article>
                    <article class="item-card">
                        <span class="line-top"></span>
                        <h3>Karma</h3>
                        <p>Regularity evaluations our talent to ensure quality.</p>
                        <img src="icon-karma.svg" alt="karma">
                    </article>
                </div>
                <div class="row">
                    <article class="item-card">
                        <span class="line-top"></span>
                        <h3>Calculator</h3>
                        <p>Use data from post projects to provide better delivery estimates.</p>
                        <img src="icon-calculator.svg" alt="Calculator">
                    </article>
                </div>
            </div>
        </div>
    </div>

    <style>
        @import url("https://fonts.googleapis.com/css2?family=Poppins:wght@200;400;600&display=swap");
* {
  --colorRed: hsl(0, 78%, 62%);
  --colorGreen: hsl(180, 62%, 55%);
  --colorOrange: hsl(34, 97%, 64%);
  --colorBlue: hsl(212, 86%, 64%);
  --bgMain: hsl(0, 0%, 98%);
  --colorGrayBlue: hsl(229, 6%, 66%);
  --colorDarkBlue: hsl(234, 12%, 34%);
  padding: 0px;
  margin: 0px;
  box-sizing: border-box;
  font-family: "Poppins", sans-serif;
}
body {
  width: 100%;
  height: auto;
  position: relative;
  display: flex;
  justify-content: center;
  align-items: center;
}
.layout {
  width: 100%;
  max-width: 1440px;
  height: auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  background-color: var(--bgMain);
  padding:40px 50px;
  overflow-x: hidden;
}
.layout .content {
  text-align: center;
  /* background-color: red; */
  margin-top: -50px;
}
.layout .content .header {
  width: 100%;
  height: auto;
  color: var(--colorGrayBlue);
  margin-bottom: 30px;
  display: flex;
  justify-content: center;
  align-items: center;
  padding: 40px 35px 20px 35px;
}
.layout .content .header .information {
  max-width: 500px;
}
.layout .content .header .top-title {
  font-size: 30px;
  margin: 0px;
  font-weight: 200;
  margin: 0px;
}
.layout .content .header .title {
  font-size: 30px;
  margin: 0px;
  font-weight: 600;
  color: var(--colorDarkBlue);
}
.layout .content .header p{
    font-size: 15px;
}
.layout .content .main {
  width: auto;
  height: auto;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-wrap: wrap;
  padding: 0px 50px;
  display: flex;
  align-items: center;
  justify-content: center;
  position: relative;
}
.main .item-card {
  background-color: white;
  border-radius: 10px;
  box-shadow: 0px 10px 20px hsla(234, 12%, 34%, 0.445);
  margin: 20px;
  max-width: 320px;
  min-width: 300px;
  height: 220px;
  padding: 20px 30px;
  text-align: left;
  position: relative;
  overflow-x: hidden;
}
.main .item-card .line-top {
  width: 100%;
  height: 4px;
  position: absolute;
  top: 0px;
  left: 0px;
  background-color: var(--colorGreen);
}
.main .row:first-child .item-card .line-top {
  background-color: var(--colorGreen);
}
.main .row:nth-child(2) .item-card:nth-child(1) .line-top {
  background-color: var(--colorRed);
}
.main .row:nth-child(2) .item-card:nth-child(2) .line-top {
  background-color: var(--colorOrange);
}
.main .row:nth-child(3) .item-card .line-top {
  background-color: var(--colorBlue);
}
.main .item-card h3 {
  margin-bottom: 10px;
}
.main .item-card p {
  font-size: 14px;
  font-weight: 400;
  color: var(--colorGrayBlue);
}
.main .item-card img {
  position: absolute;
  width: 50px;
  bottom: 30px;
  right: 30px;
}
@media screen and (max-width: 440px) {
    .layout .content .header{
        margin-bottom: 0px;
    }
  .layout .content .header .top-title,
  .layout .content .header .title {
      font-size: 25px;
  }
  .layout .content .header p{
      padding: 30px;
  }
}

    </style>
</body>
</html>
