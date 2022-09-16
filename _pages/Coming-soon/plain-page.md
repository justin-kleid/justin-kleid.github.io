---
title:  ""
layout: archive
permalink: /secret-page/
author_profile: true
comments: true
classes: wide
---

<html>
  
<head>
    <title>passwor validation</title>
    <script type="text/javascript">
        function check_password() {
            var res;
            var str = document.getElementById("input").value;
            if (str.match("taylor"))
                res = "TRUE";
            else
                res = "FALSE (About Me and Anagrams)";
            document.getElementById("output").value = res;
            if (res == "TRUE")
            	window.location.href = 'https://justinkleidermacher.com/secret-page/easter/';
        }
    </script>
</head>
  
<body>
    <p>
        Only certain individuals should be here...
        <br>
        <br>Password:
        <input type="text" 
               placeholder="abc"
               id="input" />
        <br/>
        <br/>
        <input type="button"
               value="Check" 
               onclick="check_password()" />
        <br/>
        <input type="text" 
               id="output"
               readonly/>
    </p>
</body>
  
</html>