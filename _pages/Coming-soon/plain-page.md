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
    <title>validate password</title>
    <script type="text/javascript">
        function test_str() {
            var res;
            var str =
                document.getElementById("t1").value;
            if (str.match("taylor") && str.length >= 4)
                res = "TRUE";
            else
                res = "FALSE";
                window.location.href = 'secret-page/easter/';
            document.getElementById("t2").value = res;
  
        }
    </script>
</head>
  
<body>
    <p>
        String:
        <input type="text" 
               placeholder="abc"
               id="t1" />
        <br/>
        <br/>
        <input type="button"
               value="Check" 
               onclick="test_str()" />
        <br/>
        <br/> Output:
        <input type="text" 
               id="t2"
               readonly/>
    </p>
</body>
  
</html>