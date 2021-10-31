# HTML-CSS-WEB
HTML CSS YEMEK TARİFİ SİTESİ
/******* HTML *******/
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Yemek Tarifler | Keşkül Tarifi</title>
    <link rel="stylesheet" href="css/style.css">
</head>
<body>
    <!-- HEADER START -->
    <header id="head">
        <img src="https://cdn.yemek.com/mncrop/940/625/uploads/2014/08/keskul-yemekcom.jpg" alt="Keşkül Resmi"> 
        <h1> Osmanlı'dan Miras: Keşkül Tarifi </h1>
    </header>
    <!--  HEADER END  -->

    <!--  SECTION START  -->
    <section>
        <h3> Keşkül Tarifi İçin Malzemeler </h3>
        <ul class="list">
            <li> <strong> 1 litre </strong> süt</li>
            <li> <strong> 1/2 su bardağı </strong> toz şeker </li>
            <li> <strong> 3 yemek kaşığı </strong> pirinç unu </li>
            <li> <strong> 1 çay bardağı </strong> toz badem </li>
        </ul>
        <h4> Servisi için : </h4>
        <ul class="list">
            <li> <strong> 12 adet </strong> badem </li>
            <li> <strong> 1 yemek kaşığı </strong> file antep fıstığı </li>
        </ul>
        <h4 > Keşkül Tarifinin Püf Noktası </h4>
        <p class="list"> Keşkül de sütlaç ve tavuk göğsü gibi piştikten sonra çok yoğun bir kıvamda <br>
            olmamalı. İçerisinde pirinç unu olduğu ve soğuyunca kıvamını bulacağı için <br>
            kontrollü olarak pişirin. Eğer buğday nişastası kullanırsanız daha tok ve yoğun bir <br>
            kıvamı olacaktır, dilerseniz pirinç unu yerine 2 yemek kaşığı tepeleme buğday <br>
            nişastası da kullanabilirsiniz. </p>
        <h4> Keşkül Tarifi Nasıl Yapılır? </h4>
        <ol class="list">
            <li> Toz şeker, pirinç unu ve toz bademi derin bir tencereye aktarın. </li>
            <img src="https://cdn.yemek.com/mncrop/600/315/uploads/2014/08/keskul-asama-1.jpg" alt="keşkül yapımı">
            <li> Sütü ekleyin ve bir çırpıcı yardımıyla karıştırıp tüm malzemelerin pürüzsüzce birleştiğine
                emin olun. </li>
            <img src="https://cdn.yemek.com/mncrop/600/315/uploads/2014/08/keskul-asama-1.jpg" alt="keşkül resmi">
            <li> Orta-kısık ateşte devamlı olarak karıştırarak kıvamı hafifçe koyulaşıncaya dek
                yaklaşık 15-20 dakika pişirin.Krema kıvamına geldiğinde ocaktan alın.
                Keşkülün kıvamı muhallebi kadar yoğun olmamasına özen gösterin. </li>
            <img src="https://cdn.yemek.com/mncrop/600/315/uploads/2014/08/keskul-asama-3.jpg" alt="keşkül resmi">
            <li> Pişen keşkülü servis kaselerine paylaştırın. Önce ilk sıcaklığının çıkmasını
                bekleyin. Ardından buzdolabına alarak dinlendirin. </li>
            <img src="https://cdn.yemek.com/mncrop/600/315/uploads/2014/08/keskul-asama-4.jpg" alt="keşkül resmi">
            <li> Servis etmeden önce üzerlerini  badem ve file Antep fıstığı ile süsledikten sonra
                soğuk olarak servis edin, işte bu kadar! </li>
            <img src="https://cdn.yemek.com/mncrop/600/315/uploads/2014/08/keskul-asama-5.jpg" alt="kekül resmi">
        </ol>  
    </section>
    <!-- SECTION END -->

    <!-- FOOTER START  -->
    <footer>
        <a href="https://yemek.com/editor/"><img src="https://cdn.yemek.com/uploads/2017/12/kisir-web.jpg"
        alt="Sen de tarif gönder"></a>
    </footer>
    <!-- FOOTER END -->
</body>
</html>


/******** CSS STYLESHEET ********/

/******************* CSS STYLESHEET ********************/
/*  BODY BG-COLOR */
body {
    background-color: slategray;
    font-family:Inter, sans-serif;
}
/* PLACE IMG ITEMS */
img {
    margin-left: 500px;
    margin-top: 50px;   
    width: 450px;
    height: 300px;
}
/* PLACE HEADER ITEMS */
h1, h4, h3, li, p {
    margin-left: 500px;
}
/* H1 COLOR */
h1 {
    color: white;
}
/* H3, H4 COLOR */
h3, h4 {
    color:pink;
}
/*  LIST ITEMS COLOR */
.list {
    color: white;
}
/*  PLACE LINK ITEMS */
a {
    margin-left: 50px;
}
