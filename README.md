<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="myfirst.css">
    <title>i will try my best to work on it</title>
</head>
<body>
  <svg width="190" height="160" style="overflow: visible;">
    <g transform="translate(200,150)">
      <path d="M 10 10 C 20 20, 60 20, 70 10" stroke="black"/>
 </g>
  </svg>
    <div class="container">
      <div class="authorcalc">
        <h3>Mike calculator </h3>
      </div>
        <form name="calc">
            <input type="text" name="result" size="30px" readonly class="viewer">
        </form>
        <table>
            <tr>
                <div class="btn-1">
              <td><button type="button" id="1" onclick="myFunction(this.id)">1</button></td>
              <td><button type="button" id="2" onclick="myFunction(this.id)">2</button></td>
              <td><button type="button" id="3" onclick="myFunction(this.id)">3</button></td>
              </div>
            </tr>
            <tr>
                <div>
              <td><button type="button" id="4" onclick="myFunction(this.id)">4</button></td>
              <td><button type="button" id="5" onclick="myFunction(this.id)">5</button></td>
              <td><button type="button" id="6" onclick="myFunction(this.id)">6</button></td>
              </div>
            </tr>
            <tr>
              <td><button type="button" id="7" onclick="myFunction(this.id)">7</button></td>
              <td><button type="button" id="8" onclick="myFunction(this.id)">8</button></td>
              <td><button type="button" id="9" onclick="myFunction(this.id)">9</button></td>
            </tr>
            <tr>
              <td><button type="button" id="0" onclick="myFunction(this.id)">0</button></td>
              <td><button type="button" id="+" onclick="myFunction(this.id)">+</button></td>
              <td><button type="button" id="-" onclick="myFunction(this.id)">-</button></td>
            </tr>
            <tr>
              <td><button type="button" id="*" onclick="myFunction(this.id)">x</button></td>
              <td><button type="button" id="/" onclick="myFunction(this.id)">÷</button></td>
              <td><button type="button" id="ANS" onclick="compute()">=</button></td>
            </tr>
            <tr>
                <td><button type="button" id="CLEAR" onclick="Clear()">c</button></td>
          <td><button type="button" id="3.141592653589793" onclick="myFunction(this.id)">π</button></td>
          <td><button type="button" id="6.283185307179586" onclick="myFunction(this.id)">τ</button></td>
            </tr>
            <tr>
              <td><button type="button" id="SQRT" onclick="doMath()">√</button></td>
              <td><button type="button" >Mike</button></td>
              <td><button type="button" ></button></td>
            </tr>
          </table>
    </div>
    <div class="author">
        <h1>Mikiyas Dawit</h1><br>
        <h2>2021</h2>
    </div>
    </body>
    <script src="myfirst.js"></script>
</html>
