# formdesign1
form design using html
<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="style.css">
<style>
body {
  font-family: "Lato", sans-serif;
}

.sidenav {
  height: 120%;
  width: 250px;
  position: absolute;
  z-index: 1;
  top: 0;
  left: 0;
  background-color: rgb(214, 14, 107);
  overflow-x: visible;
  padding-top: 20px;
}

.sidenav a {
  padding: 6px 6px 6px 32px;
  text-decoration: none;
  font-size: 25px;
  color: #b81919;
  display: block;
}

.sidenav a:hover {
  color: #1b00b3;
}

.main {
  margin-left: 200px; /* Same as the width of the sidenav */
}

@media screen and (max-height: 450px) {
  .sidenav {padding-top: 15px;}
  .sidenav a {font-size: 18px;}
}
</style>
</head>
<body>
<div class="sidenav">
  <!DOCTYPE html>
<html>
<head>
    <style>
        .center-aligned-text {
          text-align: center;
          position = absolute;
        }
    </style>
</head>
<body>
    <div class="center-aligned-text">
      <h1 style="color:rgb(2, 2, 8)">work on your Ideas here</h1> 
    </div>
  <button id="Layout-button";
  <buttonstyle="background-color: black;color:darkblue"
</button>
  <img id="Image" src="layout.jpg" style="width:1500px;height:1500px;"hidden>
  <script>
    const LayoutButton = document.getElementById("Layout-button");
    const myImage = document.getElementById("Image");
    LayoutButton.addEventListener("click", () => {
       myImage.hidden = !myImage.hidden;
    });
 </script>
  <a href="#"><img src="559907.png" width="29"> Layout </a>
  <a></a>
  </button>
  <button id="Label-button";
  <button style="background-color: rgb(27, 29, 29);color:darkblue"
</button>
<img id="Image1" src="c:\Users\Admin\Desktop\vs form\form design\labels.jpg" style="width:1500px;height:1500px;"hidden>
<script>
  const Labelbutton = document.getElementById("Label-button");
  const myImage1 = document.getElementById("Image1");
  Labelbutton.addEventListener("click", () => { 
    myImage1.hidden = !myImage1.hidden;
  });
</script>
  <a href="#"><img src="4229803.png" width="29"> Label</a>
  <a></a>
</button>
<button id="textbox-button";
<button style="background-color: rgb(133, 18, 108);color:rgb(8, 8,90 )"
</button>
  <img id="Image2" src="text.jpg" style="width:1500px;height:1500px;"hidden>
  <script>
    const textboxButton = document.getElementById("textbox-button");
    const myImage2 = document.getElementById("Image2");
    textboxButton.addEventListener("click", () => {
       myImage2.hidden = !myImage2.hidden;
    });
 </script>
  <a href="#"><img src="3815460.png" width="29"> Text Box</a>
  <a></a>
  </button>
<button id="Button-button";
<button style="background-color: rgb(17, 155, 59);color:rgb(67, 67, 82)"
</button>
  <img id="Image3" src="button.jpg" style="width:1500px;height:1500px;"hidden>
  <script>
    const buttonButton = document.getElementById("Button-button");
    const myImage3 = document.getElementById("Image3");
    buttonButton.addEventListener("click", () => {
       myImage3.hidden = !myImage3.hidden;
    });
 </script>
  <a href="#"><img src="1536958.png" width="29"> Button</a>
  <a></a>
</button>
<button id="checkBox-button";
<button style="background-color: rgb(12, 82, 82);color:darkblue"
</button>
  <img id="Image4" src="check.jpg" style="width:1500px;height:1500px;"hidden>
  <script>
    const checkboxbutton = document.getElementById("checkBox-button");
    const myImage4 = document.getElementById("Image4");
    checkboxbutton.addEventListener("click", () => {
       myImage4.hidden = !myImage4.hidden;
    });
 </script>
  <a href="#"><img src="12397365.png" width="29"> Check Box</a>
  <a></a>
</button>
<button id="radio-button";
<button style="background-color: hsl(188, 89%, 4%);color:rgb(51, 51, 241)"
 </button>
  <img id="Image5" src="radio.jpg" style="width:1500px;height:1500px;"hidden>
  <script>
    const radiobutton = document.getElementById("radio-button");
    const myImage5 = document.getElementById("Image5");
    radiobutton.addEventListener("click", () => {
       myImage5.hidden = !myImage5.hidden;
    });
 </script>
  <a href="#"><img src="8458883.png" width="29">Radio button</a>
  <a></a>
</button>
<button id="table-button";
<button style="background-color: rgb(62, 165, 131);color:rgb(139, 0, 58)"
 </button>
  <img id="Image6" src="table.jpg" style="width:1500px;height:1500px;"hidden>
  <script>
    const tablebutton = document.getElementById("table-button");
    const myImage6 = document.getElementById("Image6");
    tablebutton.addEventListener("click", () => {
       myImage6.hidden = !myImage6.hidden;
    });
 </script>
  <a href="#"><img src="3602109.png" width="29"> Table</a>
  <a></a>
</button>
<button id="navigation-button";
<button style="background-color: rgb(21, 9, 65);color:rgb(0, 139, 12)"
 </button>
  <img id="Image7" src="navi.jpg" style="width:1500px;height:1500px;"hidden>
  <script>
    const navigationbutton = document.getElementById("navigation-button");
    const myImage7 = document.getElementById("Image7");
    navigationbutton.addEventListener("click", () => {
       myImage7.hidden = !myImage7.hidden;
    });
 </script>
  <a href="#"><img src="6054629.png" width="29"> Navigation</a>
  <a></a>
</button>
<button id="image-button";
<button style="background-color: rgb(16, 125, 133);color:rgb(139, 0, 30)"
 </button>
  <img id="Image8" src="image.jpg" style="width:1500px;height:1500px;"hidden>
  <script>
    const imagebutton = document.getElementById("image-button");
    const myImage8 = document.getElementById("Image8");
    imagebutton.addEventListener("click", () => {
       myImage8.hidden = !myImage8.hidden;
    });
 </script>
  <a href="#"><img src="1375106.png" width="29"> Image</a>
  <a></a>
</button>

</div>


<head>
  <title>Publish and Preview Mode</title>
  <style>
      .modes-container {
          position: relative;
          width: 100%;
          height: 100px;
      }

      .publish-button, .preview-button {
          position: absolute;
          top: 10px;
      }

      .publish-button {
          right: 10px;
      }

      .preview-button {
          right: 80px;
      }

      .publish-mode, .preview-mode {
          display: none;
      }

      .mode-content {
          text-align: center;
          text-size-adjust: 125px;
          padding: 100px;
          background-color: #9cade9;
      }
  </style>
</head>
<body>
  <div class="modes-container">
      <button class="publish-button" onclick="switchMode('publish')">Publish</button>
      <button class="preview-button" onclick="switchMode('preview')">Preview</button>

      <div class="publish-mode mode-content"></div>      
          <h1><em>Publish Mode</em></h1>
          <p><strong>is the content in Publish Mode.</strong>
          <I>It was published by K.Rajaganapathy.MCA EGSPEC</I></p>
      </div>

      <div class="preview-mode mode-content">
          <h1><i>Preview Mode</i></h1>
          <p><strong>click any option to view their styles</strong></p>
      </div>
  </div>

  <script>
      function switchMode(mode) {
          if (mode === 'publish') {
              document.querySelector('.publish-mode').style.display = 'block';
              document.querySelector('.preview-mode').style.display = 'none';
          } else if (mode === 'preview') {
              document.querySelector('.publish-mode').style.display = 'none';
              document.querySelector('.preview-mode').style.display = 'block';
          }
      }
  </script>
</body>
   
</body>
</html>
