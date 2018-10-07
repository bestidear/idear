<!DOCTYPE html>

<html lang="en" xmlns="http://www.w3.org/1999/xhtml">
<head>
    <meta charset="utf-8" />
    <title></title>
    <style type="text/css">
        body, html {
            height: 100%;
            margin: 0;
            padding: 0
        }

        .box {
            height: 100%;
            position: relative;
            z-index: 1;
        }

        .fd {
            position: relative;
            height: 500px;
            background-size: cover;
            background-repeat: no-repeat;
            background-position: center center;
            z-index: 1;
            background-attachment: fixed;
        }
        .bg1 {
            background-image: url(images/one.jpg);
        }

        .bg2 {
            background-image: url(images/two.jpg);
        }

        .bg3 {
            background-image: url(images/one.jpg);
        }

        .bg4{
            background-image: url(images/two.jpg);
        }

        .bg5 {
            background-image: url(images/one.jpg);
        }

        .bg6{
            background-image: url(images/two.jpg);
        }
    </style>
</head>
<body>
    <div class="box">
        <div class="fd bg1">
        </div>
        <div class="fd bg2">
        </div>
        <div class="fd bg3">
        </div>
        <div class="fd bg4">
        </div>
        <div class="fd bg5">
        </div>
        <div class="fd bg6">
        </div>
    </div>
</body>
</html>
