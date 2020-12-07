<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width">
    <title>repl.it</title>
    <link href="style.css" rel="stylesheet" type="text/css" />
    <style>
      body{
        margin:0;

      }
      .nav {
        height: 70px;
        border-bottom: 1px solid black;
        display: flex;
        align-items: center;
      }
      .nav-right-items{
        display: flex;
        margin-left: auto;
      }
      .nav-item{
        margin-left: 10px;
        
      }
      .title{
        text-align: center;
        font-size: 3.5rem;
        font-weight: bold;
      }
      .subtitle{
        text-align: center;
        font-size: 1.25rem;
        font-weight: 300;
      }
      .main{
        width: 800px;
        margin: 0 auto;
        margin-top: 60px;
        
      }
      .map{
        display: flex;
        
      }
      .map-item {
        width: 300px;
        height: 300px;
        border: 1px solid black;
        margin: 20px;
        border-radius: 4px;
        text-align: center
      }
      .map-item-title{
        
        font-size: 1.5rem;
        background: rgba(0,0,0,.03);
        text-align: center;
        height: 53px;
        line-height: 53px;
        border-bottom: 1px solid black;
      }
      .map-item-maprice{
        font-size: 2.5rem;
        font-weight: bold;
        padding: 20px;
      }

      .map-item-butoon{
        padding: .5rem 1rem;
        font-size: 1.25rem;
        line-height: 1.5;
        border-radius: .3rem;
        color: #007bff;
        background-color: transparent;
        background-image: none;
        border-color: #007bff; 
        margin-top: 100px;
        align-items: center;

      }
      .map-item-detail{
        margin-bottom: 5px;
        font-size: 15px;

      }
    </style>
  </head>
  <body>
    <div class="nav">
      <div class="nav-right-items">
        <a href="nav-item">1.학교소개</a>
        <a href="nav-item">2.지도</a>
        <a href="nav-item">3.편의시설 및 도서관</a>
      </div> 
    </div>
    <div class="main">
      <div class="title">
        한림대학교 지도
      </div>
        <div class="map">
        <div class="map-item">
          <div class="map-item-title">
            지도
          </div>
          <div class="map-item-detail">
            10 uesersll
          </div>
          <button class ="map-item-butoon">
            click me
          </button>
        </div>
        <div class="map-item">
          <div class="map-item-title">
            지도
          </div>
          <div class="map-item-detail">
            10 uesersll
          </div>
          <button class ="map-item-butoon">
            click me
          </button>
        </div>
        </div>
      </div>
    </div>
  </body>
</html>
