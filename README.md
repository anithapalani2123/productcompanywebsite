# Web Design for a Software Product Company

## AIM:

To design a static website for a software product company company.

## DESIGN STEPS:

### Step 1:

Requirement collection.

### Step 2:

Creating the layout using HTML and CSS.

### Step 3:python

Updating the sample content.

### Step 4:

Choose the appropriate style and color scheme.

### Step 5:

Validate the layout in various browsers.

### Step 6:

Validate the HTML code.

### Step 6:

Publish the website in the given URL.

## PROGRAM :
```
#css code:
* {
  box-sizing: border-box;
  font-family: Arial, Helvetica, sans-serif;
}
body {
  background-color: black;
  color: rgb(226, 186, 52);
}

.banner {
  display: block;
  width: 120%;
  height: 320px;
  text-align: center;
  font-size: 40px;
  background-image: url("https://images.firstpost.com/wp-content/uploads/2021/09/iqoo-z5.jpg");
  
  background-size: 83.3% 100%;
  background-repeat: no-repeat;
   margin: 0px 0px 0px 0px;
  padding-top: 150px;
  
  color: rgb(226, 186, 52);
}

.menu {
  display: block;
  width: 100%;
  height: 50px;
  font-size: larger;
  background-color: black;
  text-align: center;
  padding-top: 15px;
  margin: 0px 0px 0px 0px;
  border-width: 1px;
}

.menuitem {
  display: inline-block;
  margin-left: 10px;
  margin-right: 10px;
}
.menuitemselected {
  display: inline-block;
  margin-left: 10px;
  margin-right: 10px;
  color: orangered;
}

.menuitem a {
  text-decoration: none;
  color: wheat;
}

.content {
  display: block;
  width: 100%;
  background-color: black;
  min-height: 500px;
  margin: 0px 0px 0px 0px;
  border-width: 1px;
  border-color: black;
  border-style: solid;
  
  background-image: url("https://st1.bgr.in/wp-content/uploads/2019/07/Xiaomi-Mi-A3-Snapdragon-665-SoC.jpg");
  
  background-size: 78% 88%;
  background-repeat: no-repeat;

}
#para1 {
  font-family: Arial, Helvetica, sans-serif;
  text-align: center;
  font-size: 150%;
  color: rgb(226, 186, 52);
}
.homecontent {
  min-height: 500px;
  margin: 10px 10px 10px 10px;
}
.homecontent i {
  text-align: left;
}
.homecontent img {
  float: right;
  width: 300px;
  height: 500px;
  margin-left: 10px;
  
}

.contenttext {
  text-align: center;
}

.productcontent {
  min-height: 500px;
  margin: 10px 10px 10px 10px;
}

.productcontent h1 {
  text-align: left;
}

.productitems {
  display: block;
}

.productitem {
  display: inline-block;
  width: 30%;
  height: 250px;
  text-align: center;
}

.productitem img {
  width: 100px;
  height: 100px;
  display: block;
}
.productitem .itemimage {
  display: block;
  margin-left: auto;
  margin-right: auto;
  width: 100px;
  margin-bottom: 5px;
}

.productitem .itemname {
  display: block;
}
.productitem .itemprice {
  display: block;
}

.footer {
  display: block;
  width: 100%;
  height: 40px;
  background-color: black;
  text-align: center;
  padding-top: 10px;
  margin: 0px 0px 0px 0px;
  color: white;
}
#homepage code:
<!DOCTYPE html>
<html lang="en">
  <head>
    <title> Homepage | ZISTRIZAG India</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/zlogo.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">ZISTRIZAG Z5 5G SMARTPHONES</div>
      <div class="menu">
        <div class="menuitemselected"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a>People</a></div>
        <div class="menuitem"><a>Contact Us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1><i>ABOUT ZISTRIZAG</i></h1>
          <img src="./img/zistrizag.jpg"/>
           <br/>
          <br/>
          <br/>
          <br/>
          <br/>
          <br/>
          <br/>
            <br/>
            <br/>
            <br/>
            <br/>
            <br/>
            <br/>
            <br/>
            <br/>
            <br/>
            <br/>
            
            <p id="para1"><strong>ZISTRIZAG is a technology company that creates great products based on a design-driven value, with smart devices and intelligent services as its core.</strong></p>
            
            
                         
            
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2021 ZISTRIZAG smartphones private limited, Developed by Anitha palani.
      </div>
    </div>
  </body>
</html>
#productpage code:
<!DOCTYPE html>
<html lang="en">
  <head>
    <title> Products | ZISTRIZAG India</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/zlogo.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">ZISTRIZAG Z5 5G SMARTPHONES</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitemselected"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a>People</a></div>
        <div class="menuitem"><a>Contact Us</a></div>
      </div>
      <div>
        
        <div class="productcontent">    
          <h1>Our  Products</h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQgf8rg593EtEYJ4SFlJ64PZZphYfKoxlRZrs0vXU1Fy3jZ80K159E0-PyaR6HOxQDHQKE&usqp=CAUs">
                  </div>
                  <div class="itemname">Zistrizag Z5 5G 8GB RAM 256GB</div>
                  <div class="itemprice">Price: Rs.35,000.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTYHwYnp7au-kJZD3oJIqepDucU_nWSWJxWYN0MIkxze9GAj8Gwlsyb4GPNKt2j9wrvF80&usqp=CAU">
                  </div>
                  <div class="itemname">Zistrizag Z3 4GB RAM 64GB</div>
                  <div class="itemprice">Price: Rs.15,000.00</div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="https://imagevars.gulfnews.com/2021/11/04/Tesla-Pi-Phone_17ceba1b344_large.jpg">
                </div>
                <div class="itemname">Zistrizag Z7 5G 8GB RAM 256GB</div>
                <div class="itemprice">Price: Rs.59,999.00 </div>
            </div>
            <div class="productitem"> 
              <div class="itemimage">
              <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQTQrXco8wrZkrKrF02P9CD2a6sMupdcnnKgA&usqp=CAU">
              </div>
              <div class="itemname">Zistrizag Z5 5G 8GB RAM 128GB  BLACK</div>
              <div class="itemprice">Price: Rs.25,000.00 </div>
          </div>
          <div class="productitem"> 
            <div class="itemimage">
            <img src="https://imgk.timesnownews.com/story/Poco_X2_image_3_2.jpg?tr=w-400,h-300,fo-auto">
            </div>
            <div class="itemname">Zistrizag  Z3 6GB RAM 64GB Purple Shine</div>
            <div class="itemprice">Price: Rs.20,000.00 </div>
        </div>
        <div class="productitem"> 
          <div class="itemimage">
          <img src="https://images.indianexpress.com/2021/02/Poco-M3-Launch.jpg">
          </div>
          <div class="itemname">Zistrizag 4GB RAM 64GB yellow </div>
          <div class="itemprice">Price: Rs.12,000.00 </div>
      </div>
      <div class="productitem"> 
        <div class="itemimage">
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcR_GqF7b1FVH_IIClV_KaqxjiQNXOI6G6hGVnOF4lu1CIrxsdR8oti3hxjfjGScQMq673E&usqp=CAU">
        </div>
        <div class="itemname">Zistrizag 4GB RAM 64GB Blue Matte </div>
        <div class="itemprice">Price: Rs.16,000.00 </div>
    </div>
    <div class="productitem"> 
      <div class="itemimage">
      <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRd_wdANjBCD1A5A5B37OU95Rp3mZNxhX9URIBrCENF8JdShimApuqfHLjfeVF_LqWw7t4&usqp=CAU">
      </div>
      <div class="itemname">Zistrizag Z7 8GB RAM 256GB </div>
      <div class="itemprice">Price: Rs.65,990.00 </div>
  </div>
  <div class="productitem"> 
    <div class="itemimage">
    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQbPCv_dlF5CBVA3bIh_AqKg4kzmI_ebUJOH2YC-AzB0y3bVvztiVatnczGk9o6CQNWNvI&usqp=CAU">
    </div>
    <div class="itemname">Zistrizag  8GB RAM 256GB AQUA BLUE</div>
    <div class="itemprice">Price: Rs.45,000.00 </div>
</div>
<div class="productitem"> 
  <div class="itemimage">
  <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRHfbV-wDWheCsIGdCvzkzPUSFWEmOz58xLsibT45O98vgsOc6QA7OXwV3Zf7MVMDWRXlY&usqp=CAU">
  </div>
  <div class="itemname">Zistrizag Z5 5G 8GB RAM 128GB</div>
  <div class="itemprice">Price: Rs22,000.00 </div>
</div>
<div class="productitem"> 
  <div class="itemimage">
  <img src="https://en.letsgodigital.org/uploads/2020/11/samsung-smartphone-surround-display-sliding-camera-1024x676.jpg">
  </div>
  <div class="itemname">Zistrizag ORANGE FIRE 6GB RAM 128GB  </div>
  <div class="itemprice">Price: Rs.33,000.00 </div>
</div>
<div class="productitem"> 
  <div class="itemimage">
  <img src="https://c4.wallpaperflare.com/wallpaper/740/264/862/best-smartphones-review-xiaomi-mi-mix-wallpaper-preview.jpg">
  </div>
  <div class="itemname">Zistrizag 6GB RAM 64GB  BLACK </div>
  <div class="itemprice">Price: Rs.17,000.00 </div>
</div>



          </div>
          </div>        
      </div>
      <div class="footer">
        Copyright &#169; 2021 ZISTRIZAG  Smartphones Private Limited, Developed by Anitha palani.
      </div>
    </div>
  </body>
</html>
#peoplepage code:
<!DOCTYPE html>
<html lang="en">
  <head>
    <title> People | ZISTRIZAG India</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/zlogo.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">ZISTRIZAG Z5 5G SMARTPHONES</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitemselected"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a>Contact Us</a></div>
      </div>
      <div>
        
        <div class="productcontent">    
          <h1>people:</h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="https://im.rediff.com/money/2014/sep/19sundar4.jpg">
                  </div>
                  <div class="itemname">Sundar pichai</div>
                  <div class="itemprice">Designation: CEO </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="data:image/jpeg;base64,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">
                  </div>
                  <div class="itemname">Satya Nadella</div>
                  <div class="itemprice">Designation: CIO </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="https://cdn.vox-cdn.com/thumbor/wbW7RhMCs1VTnTOwiRmzhRSJRfk=/1400x1050/filters:format(jpeg)/cdn.vox-cdn.com/uploads/chorus_asset/file/23051237/acastro_211129_4896_0001.jpg">
                </div>
                <div class="itemname">Parag Agrawal</div>
                <div class="itemprice">Designation: CTO </div>
            </div>
            <div class="productitem"> 
              <div class="itemimage">
              <img src="data:image/jpeg;base64,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">
              </div>
              <div class="itemname">Elon Musk</div>
              <div class="itemprice">Designation: Senior Project Manager</div>
          </div>
          <div class="productitem"> 
            <div class="itemimage">
            <img src="data:image/jpeg;base64,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">
            </div>
            <div class="itemname">Kevin Systrom</div>
            <div class="itemprice">Designation: Senior Product Manager</div>
        </div>
        <div class="productitem"> 
          <div class="itemimage">
          <img src="data:image/jpeg;base64,/9j/4AAQSkZJRgABAQAAAQABAAD/2wCEAAoHCBUVFRgSEhUYGBgYGBgYGBoYGRgYGhoYGhgaGRgYGBkcIS4lHB4rIRgYJjgmKy8xNTU1GiQ7QDszPy40NTEBDAwMEA8QHhISGjEhJSE0NjQ1NDQ0NDQ0NDQxNDExNDQ0NDQxNDQ0NDQxNDQ0NDQ0NDQ0NDQ0MTQ0NDQxNDQ/NP/AABEIAQAAxQMBIgACEQEDEQH/xAAcAAABBQEBAQAAAAAAAAAAAAABAAIDBQYEBwj/xABFEAABAwEFBAcFBQYFAwUAAAABAAIRAwQSITFRBUFhcQYTIoGRobEyQsHR8AcjUmJyFDOisuHxFRaCksIk0uI0RFOjs//EABkBAAMBAQEAAAAAAAAAAAAAAAABAgMEBf/EACcRAAICAgIBAwQDAQAAAAAAAAABAhEhMQMSUUFxgRMiQmEUMpEE/9oADAMBAAIRAxEAPwDtCKaiFwnrBCIQRCBMcmpyamICMJJloqlgmBETiQB3k5JCY5zgMTgFXW3bdJmF6SN0FZ3au0WPMjE4gkPc5uXgqJ9TMueSTz8DqqUTKU60amr0lfehojmPqUrL0lqElr2tnMHEHeSFlWMOBGA1J9ApWSfZeM8ZkDhM8s1XUjuzVnpOR7mF2cDOO4DgruxW9lRoe05xhpO7zXnrgW+0MSMj8HDPUHcm2K0vDoLyM8Zz4EapUNSZ6aUFmbP0jktvYiMSOcOnuxWj61sB0iDEHWVJommPTXJ5CYUABBEpBAARCSSoQwoQiUkACEkkkAGUQUyUQVB0EkpNKbKIKBMfKEpJJkiCyXSTajC8MbBiZnED8x1CtOkdvDGdWCQ54kxuZ45lYo3niCM4ga6NAGQGMniU4qzHkl6IY6sxzpzOgbHnuyK6qGzKlT92yMzMeU/BbPov0TZdbUqAXnEYuOQyyK0tusVNhhkEDDHAExohy8CjFN0zzRmwauRGnsgAccMk4dH6k+zBGkg+Rhb1pI/snl2HqkpM0fCjzl+warSQLw1EEjnG5RP2RXEkMvDWYPivS4bEYFN6to3I7sPoo8rqucwkll3O8I35YcVa7L2z2GU6h7DXscTuaA7yG9bmtYKb/aYCThksZ0g2B1N6pRHYI7bM40IG9vBUpJ7IlxuOUbRlRrheY4OGoIPogVg+jG03NfdHb3nW7Hmt4HSJCTVBGXZAKQSSSKEkkUECAUESgqFYEkkkCsYCnBNupyk6hyQQRCQh4KitNdtNjqj/AGWiTx0HipAs/wBMHm4ynMAuLnakNGHdJTSIm6Rnn2l1ao4mJdiScbo3TqInBdmyqAfUY0ey3tE4XnnIFx0zgDKdSqt7rmDSWhxx3uOHp6K+6PtF6eIVtUjli7kbax1gxw4NjHLw8fFGvWLpP14rla7tfWEBSzj9YSsLOyMVsE5H01T4wyzwzSH0csdU6+MBv3E8kFWAtw8M8u9B+RMog6geqTsNwG8Z98oAlshF4GBuj54qfbdmY9oe1oEkgjccN45LkY3HD6lS3zBBwlOLxRElbs8l2pYXWW0TTJAJvMI3A5t7vSF6Hs209ZSZU/E0SNHDMdxVb0x2ZfpAtHaZ2mxwGI44KDojaZY+mTMXXtP5XNHngtr7KzCusq8mhSSKEqaG2JyCBKQTomxFBFJOgsCSSSBCJQRSCg6xIhJEIEOCzG3CHWjEghjAIOuJcTwy81qGrDdJK16rUaMDMcwMAPVOKyY8r+0qrRSL3dZOGHKNwWn6P04GA/vuA+t6zlB964ziXO0JnDuw8hqtpsmgGtBjd5JzdIy4o27LUGSPrwXTcAwnGJ+Z4LjFUN8uPPBQ19tUaZ7RJMYwCcN2KxR13RaU2Ddhp88VIGhozAz5+Kw9o6YuvFzG4ZAEbpzBCZQ6XV3OwYyOTgI8c1aiyHyI3AAcAYjcQVIaZ3jyXDsm3GowOeAHY4Nyw344jkrB1YBsu0KmkV2ZDcgzP1mnsAcIylVFv2/TYCThmMMd8D5yuSj0qpkTB8MfDf3IUSXJF1tEAAcCsZZos1pMTcc4tPAOMjuBPmtT+2srsvtMz5LJdJhL26uAH8Q+ZWkfBnyas15QRAgRph4YfBBXRFjSikUggLEkUkoQAEkYSQICKQCdCzOsCISRCBBaF5ztqqHWl43BxGGZg5jvPkt7bdpUqBb1peL3s3W3oje6MY5ArNbQ6Muc51oo1Gva6XgRBAmZacnDPQqotJkckJOOCs2dRDqjWNHvCfPDBb6lTgQOXKFi+jDZqg469+IiNVuqQkjy571HI8k8McFTbabnYDESCcS3wwxXO2z0m41DO+HGYG8xuHNan9maRiBjvhVNq6OUqhl17OSc5O6RkUolyKF+27CwkMu3ssnOGuN1p04rnrWdj+20MH5qbnROjmOAhWr+g9EOLw7GTvgQc8IzxK7Tsdof1hkOylpiQIjDI960l1WiYJt5D0ZaYg+KtNt1gxjnbg0+m9RMYGuLgIkzCh2469Te13vNPpksTSjz/qn2l5ugmdwEwOO4d5XUei2Euq3TnEZd7XEK2s2xuspvF4m81wbhdAJyNwZkcT4Kp/yhXY8mYzulgcCBHZEgDfrhguhVWzmkneiOiypZsn3hmCCCDwIXX0nHYo1o94A88H/A+C6LDse0OMVG44TGUjNw4nBdfSSwuFle0+0yHNI1BjDuKSasrr9pfOTU6d+oHDdnG5AqzMYikiEBYAjCQTkgsbCSckihWMCKICMLI7QFEBKEQECZy2qgC4OImGeriPgpqdM0SQ2A1wkCcL/vNjQ+qmY0FwB1+N7/ALlz7UD3sDaV0G8O07c0GTHPVQ8G1XEzGz2BtrqtaIAkxpMH4rU2aoJVc+kGvfh2iQHHkI+anpEgjwMIkzniqtF8x2CURJn4rhY+BnA58l0seMADxMpWaJEjXkaH60Ti0nE/2RptBI3b+7im221hrYYMeOCrNA1nCOG0mDH1CfbqQfSdIxBBB0Bw8FyVHC8LzsTgeE7l316rGtOOF0tcN0b1KQOqK3ZlFzWgRv7s47laOp7nOcI4+hXFYKrD+7deEAwcwd4+tV0VKhnPLcdNVViUbO6i1jRh54kqh6SEXHx+En4rpqViCScMt+eqptqWi/LAcxH1zTjkmUaZ0bDDzSvvPae4ujRo7LWjuHmrFQ2ZkMYNGjx3qZbLRzSf3MCQSRTIEAklKUoHYoSSSQIsRsd/BEbHfqtl1TURTCXQPryMcNjv18k4bHfr5LXljU0tan0QfXkYnaOz3U2Cp7UOAgZ4zkueyPBbdaWkkEC9LSBpG4rb22ytqMcwmLwwOhGLT3GFjhUAe6lUaGvYQHD0cDvacwd/cVlONHTwcrlHr6lDWJ6x97OccZ3DRS2Z+7LI/wBUzaECsQ0gAtaTGUgkH0HinsGIgfXBQyvU7nuwHyTqZmT3f3UDcROh9Auqzj69VJonR1ZDX4lc1WzSxwJ7TvJTGpGWaY941HGck6ByMpadhAk1usqNrDHsmWu/DIIy4KmtdutBmm+8yRExAjULevfAJAmPrwVbWh+DhmAYwP8AZaKXkykreCq6L0nMN0kwDmTiZ1WmtGE/XeqylRDSXjHIxOZ4Kwv3mwTOiiWXZcXRXW2o7IYSMVWsb29MZJ4N3qztjgI/vguWy0u1Lt4d6ZKo6Im7ZvGbGbdbh7rfQJ3+DM0VjZbY1zGPnNjD/CE51qbqtsHC5Oyr/wAHbol/hDdFZ/tbdVG62N1CYrZXHZbdEBs1ui7H21uoQbbW6hILZz/4a3RJdX7czUJJ4C2VbulrN0+CDeljdHeCoupCPVN0WSlI7XxcaLp/S1u4O8FC7pZ+V3gqs0m6JopDRXkzcYr0LX/Nf5HeC47dtxlYAVaN+MiQQ4cGuGI5ZKEUhoj1Q0RklJLKKq1Gnea+nTuYXXCSb2cOJMmcx4LostUYeGal2hQmm+BiAHD/AEmfSfFcdhqTiOOWm5ZyRtGRcU2yMNMeGSkpOhR2Z+UaSd+7MJX8fXnOEws6KciHaFoDBeJO+IVKdoV3C8yz1XcSLrSOZMEK7tQvvGEtEE68vFddxjsDjrw7006Lik9mbdbbbHsNbwLmqGrb7UfcYObmj0lXltY9o+7cCBuOYx3KtfaHk3OzjlMeqpNeDX7aKk7XqDB9J4j3mAub4jLNaCyvkN45/MplCzBgvvOO7SUaNYGQBgOHxSbTMJJIZUF950UFWzl5DROGJjCRlE6FdNncMSOKm2Vjfd+YN9SfVXFGUpUrHft1eABAAEAY4AYAJhtVo19VYXUrqujHHgrv2m0a+qaalc+8rO6ldToMeCqLax95IMrfjKtbqddQGPBU9VV/GUlbXUkDwc0ogpqKSRo2ElIIFEJkseEQgEQgQC2QRqCPFZizPLHFkxBPqtQFmdosio8cSfj8VMhxLuy1Ac9Z8onz8l0XRmI4RyVBZKxw7WPGfVXDKoIjGRvGuqyZd2dwpgnLMd434JjqR92ThrOR3Bc1KsWm6cBqdD9ZqxbVyPjjPcoo1jKjjq2dxGLjnuxPGVWjZ7WOLy9x44BXNR4GP9N+WC4atpBBO4SVRr2VZK62MeTdB7M4xu4BPrtaxmPDxU9KsIk4YmN0clTWmvffJ9lpgZnEbk4owmzpFS6y9lwnDkrXYY+6nV7j6BZp1UvdGQEADynmtXspkUWcQXf7nEjyhbRwYSydKSMIpioEIwlCcgKBCKSKBgSRSQBxQknQlCCgJBOISAQSEBEJEQLzsBqcB4lVFs6TWSlg6qHnRgLvMYJpEt0W6o9ssIfeGjfT+nkoB02sulXncHzVxanMeyzvI7NajeAO8k34PG64FKapWVxtN0UTGkGYw8f7Kxsjgcpn6zjFCpYCztNBczUCSP1YeahfTLe03EZ4R5FYvJpTRZVbPfB7WO47xwJXBW2i6n2KjSNHHFp3qFu1rph0+kc5zUtTa7HCDdPMT9YJdR2QO2w1w7JBy0+guV9v3bpmCdOKFd1BxwYAZ92QI4RgoDZ6ehPMmJ4KqQuzJ37SvC5Tz952ERvUMQ0EnDdjv+JUbccGDDgIHeuqnZQCC+S4+ywYkngPinhCpsFmpE45SczuEYuPAZrZ0i0t7GTSWQc2uZ2S1w3ER6FZjaN6i1pPtvfTbDfcZfbeEnMnBdvSXaAsVsYT+5tFNoqDMtdTN1tQcQ0tB4DgtIrtGzOUuskmXiSAIIBBBBEgjIg5EHeEUDsScmoyihWFJBFAWJJJJAWUNbpFZGZ12ngwF58gq6v01oN9inUfxN1g8zPksCmvKqkQ5s11fp1UP7uhTb+tz3+l1Vtp6X2t2VQMGjGNb/EZd5qgc5REqkiHJ+TotdvqVDNWo95/M5zvUrkmEnFNVIk6LOJdJyC9e2PTFq2ZRLZ6yixrmR+KnNNw5FoI7xovJ6LIHdJXpP2X28mi6mcqb3Sd117b2eoLHeISkk1Q4y6u0X2zq15oIOYEHWR9YJtbZodjTIY7ODJaTw/CeWHBcWwbc20tIsbGNAd2jUquc9gLjBYxsBgOJF69vwMLSMAH3bi1zmiL4dMkZh5utB8OS5/oyOr+TB4aZnatnyFWlI1Lb7T3hcL9i2J+RLD+So5o/wBpWtuTkSPNJ9lnNrThvg/zCVlbRtSMQ/o3RAkWl0Z9p0+Ycoxsqgw+2ahnJsu8gtsdnMmbjOd1g+CD6AE3fLD6CfZgooy1PZz3YMZcb+J4x7mDPvVlZtn9XLgCXEYvcZdy0A4BXYpwNPH4rmtAgE7vj81LZaikUTNnOq1mNdiQ5r3aBtNwdHiAFU/a1UmrQjICoB4sW/s1nFFhc8dt3afwAxDOQPnKwnT6y32NecXMY554XngegXVxRaRw881JqjN7I6UWizs6phY5gMtFRrnXZzDSHCBwVtZ+ndUfvqDD+hz2GOTi4HyWMaU8OVtGaZ6jYOlFlqAfeBjvw1OyQeeR7lbsqsdi17CODmn4rxjrE1royw5YJdR9j226fqESw6HwXinXu/E7/c75ropbTrM9irUbye75o6j7HsKS8n/zFa91pq/7v6IJdQ7IqC8lBIJU8TOgVGdjKmajJTnlRqkAlPRpyY8Uym1dNEgTHJDYEr3RgFr/ALPXltK1xupucccDFN5HIwHY8VjStr0L/wDRWwlphzhTkQCDUovZv0BPilEl6KnoXtR9nqQ1p+8bdgyA4ibpBGIIkjDUr0fZVN1f72oxovPAHtXg0aA5CW5jE48lRdHNjFjIqAPa09kx2mOvGCyR+GQVparXWcUy2Xsc9rDuLS+br2jGQSII/NOqtqnaJuydlpa57mtwh7gMcDBgjmumTGCz7oZWqkmGuffYdWuAJI75CuW2huef9sBzXDLDZ6kMxVEhf9ZKOq8MY6oWuIAxDcT/AEThaW5yNdcMsE91UEhkgyDOmAnDjgnCuysXI2outmetW3KjiDTDQwSSW0zfEAxF4me/CQq13SapcNxzBUb7JfZ2Xp3EwQ2eMFaUWOk4klmIIxBIEfmgycws/wBIujjnXuovON0PaLrSRi69ee44CACN+a7VGN6R5rnJ+ryaCja/2llOsOy2oxr4zDdzmzwcHeCrtq2HrhccCDUY4/paf3bfADvcUOi9iq0bNUs9Ui80F7DN7svMOaf0uxw1Wn2wwNuvA9lzGnW7eASWHQm7Vnzy0RI0JCKmtlO7VqNHuvePBzgoVLNUJNIToSSEMDkZQcElQDwUE1JSKxqLMimuSYcCqAYWyURTS3p6BguQn0juTSg04hAHQ4r0L7NLO19ntF8TdqsIEmAbpkxrAheduXpH2W/ubQPzsP8A9ZRHZMtG0slMAMAEDFx8/mFO5l6i8AAw1z2YTde2SwjvAKbZjhyZ8/8AtXbYmQByHpj6pp7f7E/Rfozdvf1Lm9czrKDw0ktwc0u99h3YmS2d2CW1bO6i3rqZ6ykcb4iWzk1wGQzgjNXTKTX2emH4gsaeRu58MFRutTxfbZmOdIIc0QQSR2gA6AGmRqcAYCiUIyRfFyyg/wBFc+1VHBwpAGIku7DeZeQACNOKgp7TZSkOqdZUcCS5oN0AES1nCSJJIlTUdhW20Y1CxjAYDSZgCPdHMLtsHRZoqvNR1+4GNGHvGXOgZAeynHhjHO2E/wDolPGkV1mtteu9tOm0MYSQXGXOIgknSctVrW0LrC29i5waSTJMwDJ5SmULE1jx1eEAnxMD0Tyw9jHM3u6J+Kt7Rmv6v4RBtVtxj67ReuS8sBu3g0guZO4EtHeuupaWVQHMPZLgDIgte2ey4biDEoWymerayJvvpMPIvDn+TSo9pNAcagAa8DtAzdqCQAHxlng4YjQ5JCPEOkFK7arQ3K7WqebifiuBXfTVl23VsCLxY/GM3U2ucZBgiZxHlkqVSa+wEgimMBJnw+aQEj24KMqUqIIAEJIpKgI3JMSekECGuTyg8ItyCAEgUUiEASOOC9G+yw/dWrg5nmxwXmzDgvRvsrf2LWNDRPiKg+CI7FLRvKpuFw1YI54j5rtrPuU3vHusee8Mw9Fz25mDj+ENcP8ASSY9U+1vmg8/iDB/vqMbH8SFr5YS38IkqUrrG09GsZ4QD6FUm3duUrFRNao0uL3llNjSGl0NxJdButAAneZEK72nVAqCnvLXv7mVKbD/APo3wXnX2p0XXKL57Laj2kbgXNBB8j4IpNUyU6Ydnfag4VAa9BnVl3auF99oMAubewdETBz4L0ezlrn1XNIc1z2Oa4ZFppMII5hfOGWJyyXsv2b21z7KQ8klhY0E6BsBF4G1RoGsguIOAYOOpTi3tAaNd6gfBRjN8fgHm0rocO3/AKfVyPX4H+PyPtPt0Ruvucf9NN0eZCjtxBzjNo/in4KSsPvKfKp/KPmuW0EXw1w94ehKFtEs8q+02gG2tjmiA6iyeLmue30urKLdfanTE2Z439a09wpkDzcsK1TdqzVqsAKanuQu6Y/WiBADkx5xTt6jfmefwVAEFJJJADXJBWVSysOIw5LiqUC3iECsYEGjMIhAHFABhAooFACYvQ/ss/8AdjUWf+Z4+K8+YF6D9luDrTxFIeBJ+KI7E9HpDjLXdw+vFQ2ow3qzka1Et/T17CfMeacx2Dx+b5f0TtqACkXxix7HjmKjcELXywlv4Rn+me33WetZzRYypUcyo245xBLajmNaABvvMa4cllOlFq2hWs9+12dlGgXB47TG1C7JrWsc6/mcrq9JtOxqNcPNVgdeaac7wy8HwD+sNPNoVUOh9jEvLHOdeu3nvcYEgdmcu5PSYo5dHjFmpsuy9jic4Dg3s8N8r2PolZeqpvEXQRTcARBDTTBl3GQVLZeiVmL79xxAd2ZeRlGitbLZWCpVaBAAY2JJyDic/wBSGqE3Y1jfbOt1o8I+K6GmXnk3zdKib7wP4m/D5KWn7bubR5EpfkyvxXuyR5++p8KdU+bB8VBbmy5v6v8Aj/VTDGt+ml/M/wD8VFVMuHMnwbHwQtkmA+0+n/09N2lcjucwk+bfJectXqn2k0ZsZP4KrHfxOZ8V5WxStI1e2EphCemkIENTCMTzUgTAgB4CCMpKhHV14G5OD2nguMlOCKJHVaG9q5oghdARLUUNMhhCFOWDkonsIQMaCvQ/szZDKj9ahb4Ma5eeL077PKEWIv1tLvAU2tQiZaNq8w9zdSw/xD5Lot4miR+J9EeNenK5rXg9juLP+XyXRbj91A/+ShHfXpoWvlhLf+E9dpbgNSfOfWFz0qcXZJOBdG6SWn4rst7oa8/ldHhPwULBEEjLDuRJ0l7jjt+w+y5cSXeZhctGbr6m9z3nmGm43+Vd+z8m/wCn1XDYT/09Lixs85M+apkIY14MuG5zR4R81LZh2j+r/iFzUWXbhGTyXcpMgeY8F22Mdon8x8oHwKnbZbxFAZ+9qHSnSHi55+ShJ7Y5P9Y+K7rOfvK3A0m9/V3v+YXMYvzo2fEg/BOqFt0ZXp+y9YKkatd3B98+q8gYvcOk1mvWSoyMTQf4hg+S8NY5TVRRTeX7kkIFFApDGhMbuUn9VE3JAiQpJhckqA//2Q==">
          </div>
          <div class="itemname">Andy Jassy </div>
          <div class="itemprice">Designation:Senior software Architect </div>
      </div>
     
      </div>
      <div class="footer">
        Copyright &#169; 2021 ZISTRIZAG  Smartphones Private Limited, Developed by Anitha palani.
      </div>
    </div>
  </body>
</html>
#contactpage code:
<!DOCTYPE html>
<html lang="en">
  <head>
    <title> contact | ZISTRIZAG India</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/zlogo.png" type="image/x-icon" />
  </head>
  <body>
    
        <div class="container">
            <div class="banner">ZISTRIZAG Z5 5G SMARTPHONES</div>
          
          <div class="menu">
            <div class="menuitem"><a href="/static/home.html">Home</a></div>
            <div class="menuitem"><a href="/static/products.html">Products</a></div>
            <div class="menuitem"><a href="/static/People.html">People</a></div>
            <div class="menuitemselected"><a href="/static/contact.html">Contact Us</a></div>
          </div>
          
          <h1>Chat with us ( Whatapp No: 9100000000 )</h1>
          <h1>Email Us (Reply in 24h): Zistrizag@gmail.com</h1>
          <h1>24*7: 1800-342-0099</h1>
          <h1>24*7: 1800-342-0088</h1>
          <h1>24*7( only for Z5-series customers ): 1800-342-0076</h1>


          <div class="footer">
            Copyright &#169; 2021 ZISTRIZAG smartphones private limited, Developed by Anitha palani.
          </div>
        </div>
      </body>
    </html>
```

## OUTPUT:

### Home Page:

![output](./images/zss1.PNG)
![output](./images/zss2.PNG)

### Products Page:

![output](./images/ZZSS3.PNG)
![output](./images/ZZSS4.PNG)
![output](./images/ZZSS5.PNG)

### People Page:
![output](./images/zzss6.PNG)
![output](./images/zzss7.PNG)

### Contact Page:
![output](./images/zzss8.PNG)

## Result:

Thus a website is designed for the software product company and the HTML,CSS code are validated.
