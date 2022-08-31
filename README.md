<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>Cloud Fila</title>
</head>
<body>
    <div class="nav">
        <span id="logo"><h1>Cloud Fila</h1></span>
        <div class="shearch"><input type="search"  class="shearch" name="" id="shearch" onchange="openpage()" placeholder="Search here...">
            <script src="script.js"></script></div>
    </div>
    <div class="middle">
        <h1>Files</h1>
        <script src="file.js"></script>
        <a href="">
            <div class="file" id="file" onclick="Relationships()">
                <h2>Relationships between different plant groups</h2>
            </div>
    
        </a>
        <a href="">
            <div class="file" id="file" onclick="rootfunctions()">
                <h2>Summary of root functions</h2>
            </div>
    
        </a>
        <a href="">
            <div class="file" id="file" onclick="rootfunctionsbytype()">
                <h2>Summary of root functions by type</h2>
            </div>
    
        </a>
        
    </div>
</body>
</html>
