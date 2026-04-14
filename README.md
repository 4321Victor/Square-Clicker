<div>
  <button id = "button" type="button" onmouseleave="myFunction4()" onClick="myFunction()" onmouseover="myFunction3(1)" onmousedown="myFunction2(1)">
    <h1 id = "button2">
      0
    </h1>
  </button>
  <script>
    let a = 0
    let b = 0
    let c = 50
    let d = 0
    let e = 0
    function myFunction() {
      a = a + f
      document.getElementById("button2").innerHTML = a
      e = -100
      myFunction2(0)
    }
    function myFunction2(setTo) {
      b = setTo
    }
    function
    myFunction3(setTo) {
      d = setTo
    }
    function myFunction4() {
      myFunction2(0)
      myFunction3(0)
    }
    document.getElementById("button").style.borderWidth = 5
    document.getElementById("button").style.position = "fixed"
    document.getElementById("button2").style.position = "relative"
    setInterval(function() {
      c = 0.9 * c + (50 + (b + d) * 5) / 10
      e = e / 1.05
      document.getElementById("button").style.backgroundColor = "rgb(255, " + 25.5 * (60 - c) + ", " + 25.5 * (60 - c) + ")"
      document.getElementById("button").style.left = (50 - c / 2) + "vw"
      document.getElementById("button").style.top = (30 - c / 2) + "vh"
      document.getElementById("button").style.width = c + "vw"
      document.getElementById("button").style.height = c + "vh"
      document.getElementById("button2").style.top = e + "px"
    }, 0)
  </script>
</div>
<div>
  <button id = "button3" type="button" onmouseleave="myFunction4A()" onClick="myFunctionA()" onmouseover="myFunction3A(1)" onmousedown="myFunction2A(1)">
    <h5 id = "button4">
      2 points every click will cost you 10 points
    </h5>
  </button>
  <script>
    let f = 1
    let g = 0
    let h = 20
    let i = 0
    let j = 0
    let k = 0
    function myFunctionA() {
      if (a >= f * 10) {
        a = a - f * 10
        document.getElementById("button2").innerHTML = a
        e = -100
        f = f + 1
        document.getElementById("button4").innerHTML = f + 1 + " points every click will cost you " + f * 10 + " points"
        j = -100
      } else {
        k = 2.5
      }
      myFunction2A(0)
    }
    function myFunction2A(setTo) {
      g = setTo
    }
    function myFunction3A(setTo) {
      i = setTo
    }
    function myFunction4A() {
      myFunction2A(0)
      myFunction3A(0)
    }
    document.getElementById("button3").style.borderWidth = 5
    document.getElementById("button3").style.position = "fixed"
    document.getElementById("button4").style.position = "relative"
    setInterval(function() {
      h = 0.9 * h + (20 + (g + i) * 2.5) / 10
      j = j / 1.05
      document.getElementById("button3").style.backgroundColor = "rgb(255, " + 51 * (25 - h) + ", " + 51 * (25 - h) + ")"
      document.getElementById("button3").style.left = (50 - h / 2 + (Math.random() * k * 2 - k)) + "vw"
      document.getElementById("button3").style.top = ((75 - h / 2) + (Math.random() * k * 2 - k)) + "vh"
      document.getElementById("button3").style.width = h + "vw"
      document.getElementById("button3").style.height = h + "vh"
      document.getElementById("button4").style.top = j + "px"
      if (k > 0.05) {
        k = k - 0.05
      }
    }, 0)
  </script>
</div>
