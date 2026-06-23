# love-site
<!DOCTYPE html>
<html lang="ar">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>رسالة ليكي ❤️</title>
<style>
body {
    margin: 0;
    font-family: 'Arial', sans-serif;
    background: linear-gradient(to right, #ff9a9e, #fad0c4);
    text-align: center;
    color: #333;
}
.container {
    padding: 20px;
}
h1 {
    color: #fff;
}
.gallery img {
    width: 250px;
    margin: 10px;
    border-radius: 15px;
    box-shadow: 0 4px 10px rgba(0,0,0,0.2);
}
.message {
    background: white;
    padding: 20px;
    border-radius: 15px;
    margin-top: 20px;
    font-size: 18px;
    line-height: 1.6;
}
button {
    margin-top: 20px;
    padding: 10px 20px;
    border: none;
    border-radius: 20px;
    background: #ff6b81;
    color: white;
    font-size: 16px;
    cursor: pointer;
}
.hidden {
    display: none;
}
</style>
</head>
<body>

<div class="container">
    <h1>لأجمل واحدة في حياتي ❤️</h1>

    <div class="gallery">
        <!-- حط هنا صوركم -->
        <img src="photo1.jpg">
        <img src="photo2.jpg">
        <img src="photo3.jpg">
    </div>

    <button onclick="showMessage()">اضغطي هنا 💌</button>

    <div id="msg" class="message hidden">
        أنا عارف إني غلطت و أسلوبي مكانش صح...
        بس الحقيقة إني مقدرش أزعلِك ولا أخسرك.
        إنتي مهمة عندي أكتر من أي حاجة،
        و بزعل جداً لما أكون سبب في زعلك.

        أنا آسف بجد،
        و بوعدك إني هكون أحسن علشانك ❤️
    </div>
</div>

<script>
function showMessage() {
    document.getElementById("msg").classList.remove("hidden");
}
</script>

</body>
</html>