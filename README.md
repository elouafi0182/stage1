# deliverble 1
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>HTML/BEM</title>
</head>
<style>
    li{
        display: inline-block;
    }
    ul{
        display: flex;
        justify-content: space-around;
    }
    .container {
        display: grid;
        grid-template-columns: auto auto auto;
        padding: 10px;
    }
    .item {
        padding: 20px;
        font-size: 30px;
        text-align: center;
        height:200px;
    }
    div {
        display: inline-block;
    }

    div label {
        display: flex;
    }
    .grid-container {
        display: grid;
        grid-column-gap: 10px;
        grid-template-columns: auto auto auto;
        padding: 10px;
    }
    .grid-item {
        padding: 20px;
        font-size: 50px;
        text-align: center;
        height: 250px;
    }

    #section-left {
        overflow:hidden;
        margin-left:35%;
        width:250px;
    }
    #section-right {
        width:250px;
        margin-right:32%;
        float:right;
    }
    section {

        height:200px;
    }
    .footer {
        position: fixed;
        left: 0;
        bottom: 0;
        width: 100%;
        background-color: black;
        color: white;
        text-align: center;
    }
</style>
<body class="page">
<!-- Header and navigation -->
<header class="header page__header"><ul class="menu">
    <li class="menu__item">
        <a class="link menu__link" href="/link">link</a>
    </li>
    <li class="menu__item">
        <a class="link menu__link" href="/link">link</a>
    </li>
    <li class="menu__item">
        <a class="link menu__link" href="/link">link</a>
    </li>
    <li class="menu__item">
        <a class="link menu__link" href="/link">link</a>
    </li>
</ul>
    <div class="grid-container">
        <div class="grid-item">1</div>
        <div class="grid-item">2</div>
        <div class="grid-item">3</div>

    </div>

</header>
<center>Introduction</center><br>
    <section id="section-right">Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget dolor. Aenean massa. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus.</section>
    <section id="section-left">Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget dolor. Aenean massa. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus.</section>
<center>Some subtitile</center>
<div class="container">

    <div class="item">4</div>
    <div class="item">5</div>
    <div class="item">6</div>

</div>

<center>Another subtitle</center><br><br>
<center><div>
    <form>
        <label><input type="text" /></label><br/>
        <label><input type="text" /></label><br/>
    <label> <input type="text" /></label><br/>
    <label><textarea rows="4" cols="21">

</textarea></label>
    </form>

</div>
<div>
    <form>

    <label><input type="text" /></label><br/>
    <label> <input type="text" /></label><br/>
    <label><input type="text" /></label><br>
        <label><input type="checkbox" >i agree </label>
      </form>
    <input type="submit" style="float: right;">
</div>


</center><br><br>
<!-- footer -->
<footer class="footer page__footer">...</footer>
</body>

</html>
