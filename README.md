body {
    text-align: center;
    max-width: auto;
    background-image: url('https://wallpaperaccess.com/full/307348.jpg');
}
.red {
    color: red; 
}
.red-small {
    color: red;
    font-size: 120px;
}
.green {
    color: green;
}
.green-small {
    color: green;
    font-size: 10px;
}
/*---navbar---*/
h1 {
    font-size: 100px;
}
#google-flexbox {
    display: flex;
    justify-content: center;
}
.google-container {
    display: grid;
    margin: -123 670 0 0;
}
.google-background {
    height: 235px;
    width: 516px;
    margin: 200px 0px 0px 692px;
}
.google-lights {
    height: 235px;
    width: 567px;
    margin: -248px 0px 0px 664px;
}
.g-size { 
    width: 96px;
    height: 100px;
    margin: -155 0 0 794;
}
.green-mint-size { 
    height: 51px;
    width: 51px;
    margin: -125 0 0 580;
}
.green-mint-size:hover {
    display: grid;
    justify-content: center;
    animation-name: rotate-mint;
    animation-duration: 3s;
    animation-timing-function: linear;
    animation-iteration-count: infinite;
    position: relative;
    left: 300px;
}
@keyframes rotate-mint {
    0% {
        transform: rotate(0deg);
    }
    50% {
        transform: rotate(180deg);
    }
    100% {
        transform: rotate(360deg);
    }
}
.red-mint-size { 
    height: 50px;
    width: 50px;
    margin: -124 0 0 930 
}
.red-mint-size:hover {
    display: grid;
    justify-content: center;
    animation-name: rotate-mint;
    animation-duration: 3s;
    animation-timing-function: linear;
    animation-iteration-count: infinite;
    position: relative;
}
@keyframes rotate-mint {
    0% {
        transform: rotate(0deg);
    }
    50% {
        transform: rotate(180deg);
    }
    100% {
        transform: rotate(360deg);
    }
}
.present-size {
    height: 60px;
    width: 60px;
    margin: -178 0 0 783.5;
}
#present-jump-grid:hover {
    display: grid;
    justify-content: center;
    animation-name: jump;
    animation-duration: 0.7s;
    position: relative;
}
@keyframes jump {
    0% {
        bottom: 0px;
    }
    50% {
        bottom: 20px;
    }
    100% {
        bottom: 0px;
    }
}
.santa-hat-sizing { 
    height: 60px;
    width: 60px;
    margin: -149 0 0 1053;
}
.l-size { 
    height: 156px;
    width: 126px;
    margin: -202 0 0 979;
}
.search-bar-container {
    display: grid;
    width: 1255px;
    margin: -30 0 0 650;
}
.topnav input[type=text] {
  float: right;
  padding: 6px;
  border: none;
  margin: -77 715 0 0;
  font-size: 17px;
  width: 480px;
  position: relative;
  z-index: 101;
}
.search-bar-oval {/*435px or 475px from botom of screen*/
    width: 600px;
    height: 120px;
    margin: 40 0 0 0;
    position: relative;
    z-index: 100;
}
.magnifying-glass {
    margin: -78 0 0 25;
    position: relative;
    z-index: 101;
    width: 40px;
}
#google-and-search-flexbox {
    min-width: 545px;
    display: flex;
    flex-direction: column;
    align-items: center;
}
.footer {
  position: fixed;
  top: 890;
  left: 0;
  bottom: 0;
  width: 100%;
  background-color: #76B7E1;
  color: white;
  text-align: center;
}
