<!DOCTYPE html>
<html lang="en">
    <head>
        <link rel="stylesheet" href="./style/css/styles.css">
        
    </head> 
    <body>
        <div class="container">
            <div >
                <h1 class = "header_text">happy birthday thom nguyen</h1>
            </div>
            <div class="gif_container">
                <img src="<iframe src="https://giphy.com/embed/4R9iPofhP6lQzmTlhA" width="480" height="480" frameBorder="0" class="giphy-embed" allowFullScreen></iframe><p><a href="https://giphy.com/gifs/happy-birthday-youre-awesome-you-are-on-your-4R9iPofhP6lQzmTlhA">via GIPHY</a></p>" alt="Cute animated illustration">
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
