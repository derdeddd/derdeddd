<!DOCTYPE html>
</html lang="en">
    <head>
        <link rel="stylesheet" href="./style/css/styles.css">

 </head> 
    <body>
        <div class="container">
            <div >
                <h1 class = "header_text">HAPPY BIRTHDAY THOM NGUYEN</h1>
            </div>
            <div class="gif_container">
                <img src="[https://media.giphy.com/media/LnKonfpQ44fNvuGLkA/giphy.gif] alt="Cute animated illustration">
            </div>
            <div class = "buttons">
                <button class="btn" id = "yesButton" onclick="nextPage()">Yes</button>
                <button class="btn" id="noButton" onmouseover="moveButton()">No</button>
                <script>
                    function nextPage() {
                        window.location.href = "yes.html";
                    }
                    
                    function moveButton() {
                        var x = Math.random() * (window.innerWidth - document.getElementById('noButton').offsetWidth);
                        var y = Math.random() * (window.innerHeight - document.getElementById('noButton').offsetHeight);
                        document.getElementById('noButton').style.left = `${x}px`;
                        document.getElementById('noButton').style.top = `${y}px`;
                    }
                </script> 
            </div>
        </div>
       
    </body> 
</html>
