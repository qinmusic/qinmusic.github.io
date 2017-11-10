<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>轻忆•音乐</title>
    <script src="jquery-3.2.1.min.js"></script>
</head>
<body>

</body>
<script type = "text/javascript">
    var songs;
    $(function(){
        $.getJSON("./mtyyw.json", function (data) {
            songs = data;
            alert(songs.first().id);
        });
    });
</script>
</html>
