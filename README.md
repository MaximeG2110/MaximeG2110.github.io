# MaximeG2110.github.io

<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="UTF-8">
<title>Redirection</title>

<script>
function redirectRandom() {

    var liens = [
        "https://img.freepik.com/vecteurs-libre/je-t-aime-typographie_1142-1621.jpg",
        "https://i.pinimg.com/474x/cb/ae/7e/cbae7e16c2acce094f3ed995b6fec3cf.jpg"
    ];

    var choix = Math.floor(Math.random() * liens.length);
    window.location.href = liens[choix];
}

window.onload = redirectRandom;
</script>

</head>

<body>
<p>Redirection...</p>
</body>
</html>
