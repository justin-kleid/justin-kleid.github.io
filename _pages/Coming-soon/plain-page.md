---
title:  ""
layout: archive
permalink: /secret-page/
author_profile: true
comments: true
classes: wide
header:
    overlay_image: /assets/images/error-banner.jpg
    caption: "Photo Credit: Jose Castillo"
excerpt: "  "
---

<html>
  
<head>
    <title>password validation</title>
    <script type="text/javascript">
        function check_password() {
            var res;
            var str = document.getElementById("input").value;
            if (str.match("taylor"))
                res = "TRUE";
            else
                res = "FALSE (hint: About Me - Anagramss)";
            document.getElementById("output").value = res;
            if (res == "TRUE")
            	window.location.href = 'https://justinkleidermacher.com/secret-page/easter/';
        }
    </script>
</head>
  
<body>
    <p>
        Only certain individuals are allowed here...
        <br>
        <br>Password:
        <input type="text" 
               placeholder="abc"
               id="input" />
        <br/>
        <br/>
        <input type="button"
               value="Verify" 
               onclick="check_password()" />
        <br/>
        <input type="text" 
               id="output"
               readonly/>
    </p>
</body>
  
</html>