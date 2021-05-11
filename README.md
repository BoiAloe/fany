<html>
<head>
    <meta charset='utf-8'>
    <meta http-equiv='X-UA-Compatible' content='IE=edge'>
    <title>Nobia</title>
    <meta name='viewport' content='width=device-width, initial-scale=1'>
    <style>
        body {
            background-color: pink;
        }
    </style>
    <script>
        function accionParaCuandoEllaDigaQueSi(){
            alert('ahora ya somos nobios <3');
        }
        function mueveElBoton(){
            width = window.innerWidth;
            height = window.innerHeight;
            newWidth = (Math.random() * width);
            newHeight = (Math.random() * height);
            document.getElementById('btnNo').style.position = "absolute";
            document.getElementById('btnNo').style.left = newWidth + "px";
            document.getElementById('btnNo').style.top = newHeight + "px";    
        }
    </script>
</head>
<body>
    <h3>fany, quieres ser mi nobia?</h3>
    <input type="button" onclick="accionParaCuandoEllaDigaQueSi()" id="btnSi" value="Si" />
    <input type="button" id="btnNo" onmouseover="mueveElBoton()" value="No" />
 <img src="![chuec](https://user-images.githubusercontent.com/84035355/117879877-12b58f00-b26d-11eb-9272-e5c818c1d116.png)
" width="250">
<img src="![bobenamorado](https://user-images.githubusercontent.com/84035355/117879908-1c3ef700-b26d-11eb-81ac-3ee463b1c9a7.png)
" width="250">
</body>
</html>
