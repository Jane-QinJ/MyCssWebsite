# MyCssWebsite
my first css homework: making a website by using css technology
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>MyCssProject</title>
</head>

<body>
<style>
     body{
         background-color:lightgray;
     }
    .top1{
       width: 100%; 
        height: 550px;
       background-repeat: no-repeat;
        background-image: url("https://resource.bcgame-face2face.haorenao.cn/slide01.jpg");
        background-position: center;
    }

    
    #div{
        color:aliceblue;
        text-align: center;
        letter-spacing: 0.3em;
        padding: 15% 50px;
        background-repeat: no-repeat;
    }
    
    .horizontal{
       width: 400px;
       margin: auto auto;
        
    }  

    
    .column1, .column2{float: left; }
    .column1, .column2{
        width: 600px;
        background-position: center;
        background-color:white;
        
       
    }
   .column1{
       
       margin: 2px 20px 30px 90px;
   }
   .column2{

       margin: 2px 90px 30px 70px;
   }
    .wrap1{
     height: 400px;
      width: 100%;
      margin: 10px 0px 10px 30px;
      
    }
    .column1 div, .column2 div{padding: 10px;}
    .column1 p, .column2 p{text-align: left;
    color: lightgray;
    padding: 10px 40px;
    }
    .title{
        text-align: center;
    }
    .title p{text-align:center;}
    button{background: white;
       margin:10px 250px;
       height: 40px;
       width: 120px;
     }
   #col1{
      background-image: url("https://resource.bcgame-face2face.haorenao.cn/slide04.jpg");
      background-repeat: no-repeat;
     
   }
   .wrap1 div{
       text-align: center;
   }
   #col1 div{
       color:white;
   }
    
    .content{
        padding: 100px;
    }
    .line{
        width: 400px;
        margin:auto;
    }
   .pic1, .pic2{float: left;}
   .pic3, .pic4{float: left;}
   
    .pic1{
        border: 10px solid white;
        margin: 0px 40px 40px 100px;
    }
    .pic2{
        border: 10px solid white;
        margin: 0px 40px 40px 40px;
    }
    .pic3{
        border: 10px solid white;
        margin: 0px 40px 40px 100px;
    }
    .pic4{
        border: 10px solid white;
        margin: 0px 40px 40px 40px;
    }

    .footer{
        height: 70px;
        background-color: black;
        color:white;
        text-align: center;
        padding: 20px;
    }
</style>
 
    <div class="top1">
        
        <div id="div" >
       
        <p>A FREE RESPONSIVE WEB SITE TEMPLATE BY <b>TEMPLATED</b></p>
        <br/>
        <div class="horizontal">
           <p><hr/></p>
        </div>
        
    </div>
 
    <div class="container">
       <div class="column1">
        <img src="https://resource.bcgame-face2face.haorenao.cn/pic02.jpg">
          
        <div class="title">
            <p>MAECENAS SAPIEN FEUGIAT EX PURUS</p>

        </div>
       
            <hr/>
        
        <div class="title">
            <h2>Lorem ipsum dolor</h2>
        </div>
        <p>Cras allquot ut sapuen tincidunt, quis malesuada olit facilsis.
            Vostibulum sit amot tortor volit.Nam elementum nibn a liboro pharetra olomontum.
            Maoconas fougiat ox purus,quis volupat lacus olacerat malesuada.</p>
        <button>LEARN MORE</button>
       
    </div>

    <div class="column2">
        <img src="https://resource.bcgame-face2face.haorenao.cn/pic03.jpg">
        <div class="title">
                <p>MAECENAS SAPIEN FEUGIAT EX PURUS</p>
        </div>

        
            <hr/>
        
        <div class="title">
            <h2>Vestibulum sit amet</h2>
        </div>
        <p>Cras allquot ut sapuen tincidunt, quis malesuada olit facilsis.
            Vostibulum sit amot tortor volit.Nam elementum nibn a liboro pharetra olomontum.
            Maoconas fougiat ox purus,quis volupat lacus olacerat malesuada.</p>
        <button>LEARN MORE</button>
        </div>
    </div>

 <div style="clear:both;">   
    <div id="col1" class="wrap1">
        <div class="content">
        <p>NAM VEL ANTE SIT AMET LIBERO SCELERISQUE FACILISIS ELELFEND 
            VITAE URNA</p>
            <div class="line">
            <hr/>
            </div>
        <h2>Morbi maximus justo</h2>
        </div>
    </div>

    <div id="col2" class="wrap1">
    <div class="content">
        <p>NAM VEL ANTE SIT AMET LIBERO SCELERISQUE FACILISIS ELELFEND 
                VITAE URNA</p>
                <div class="line">
                <hr/>
                </div>
        <h2>Morbi maximus justo</h2>
    </div>
    </div>
</div>

<div >
    <div class="pic1">
        <img src="https://resource.bcgame-face2face.haorenao.cn/pic01.jpg">
    </div>

    <div class = "pic2">
        <img src="https://resource.bcgame-face2face.haorenao.cn/pic02.jpg">
    </div>

    <div class="pic3">
        <img src="https://resource.bcgame-face2face.haorenao.cn/pic03.jpg">
    </div>

    <div class="pic4"> 
        <img src="https://resource.bcgame-face2face.haorenao.cn/pic04.jpg">
    </div>
</div>

<div class="footer" style="clear:both;">
    <p>&copy Untitiled.All rights reserved</p>
</div>
</body>

</html>
