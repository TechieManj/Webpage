# Webpage
Creating Webpage by using HTML and CSS
@@ -0,0 +1,82 @@

* {

    margin: 0;
    padding: 0;
    box-sizing: border-box;
}


.container{
    background-color: #e5e5fd;
    min-height: 100vh;
    border: 10px solid #1d1e4c;
}
.content {
    max-width: 900px;
    margin: 0 auto;
}
.top_section {
    margin-top: 100px;
    display: flex;
    justify-content: space-between;
    align-items: flex-end;
}
.top_section h1{
    font-size: 50px;
    font-weight: bold;
    font-family: 'Times New Roman', Times, serif;
    color: brown;
    text-transform: uppercase;

}
.top_section h4{
    text-align: end;
    font-size: 30px;
}
.image_container{
    border-radius: 50%;
    overflow: hidden;
}
.image_container, 
img{
    width: 300px;
    height: 320px;


}
.about_section {
    margin-top: 50px;
}
.about_section h2{
    font-size: 70px;
    font-weight: bold;
    font-family: 'Times New Roman', Times, serif;
    margin-bottom: 20px;
}
.about_section p{
    font-size: 25px;
    font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
    line-height: 30px;
    letter-spacing: 1.5px;

}
.Books_section{
    margin-top: 50px;

}
.Books_section h3{
    margin-bottom: 35px;
    font-size: 40px;
    font-family: 'Times New Roman', Times, serif;
    font-weight: bold;

}

.Books_section {
    font-size: 25px;
    font-weight: bold;
    font-family: 'Times New Roman', Times, serif;
    line-height: 30px;
    letter-spacing: 1.5px;
}
 59  
index.html
@@ -0,0 +1,59 @@
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>The Tribute Website | A. P. J. Abdul Kalam</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <div class="container">
        <div class="content">
<section class="top_section">
    <div class="image_container">
        <img src="./images/Apj Abdul Kalam.jpg" alt="tribute" />
    </div>
    <div>
        <h1>A. P. J. Abdul Kalam</h1>
        <h4>1931 - 2015</h4>
    </div>
</section>
<section class="about_section">
    <h2>Missile Man Of India</h2>
    <p>
        <b>Avul Pakir Jainulabdeen Abdul Kalam </b> BR (/ˈɑːbdəl kəˈlɑːm/ (listen); 
        15 October 1931 – 27 July 2015) was an Indian aerospace scientist and statesman who served as the 11th president of India from 2002 to 2007.
         He was born and raised in Rameswaram, Tamil Nadu and studied physics and aerospace engineering. 
         He spent the next four decades as a scientist and science administrator, mainly at the Defence Research and Development Organisation (DRDO) and Indian Space Research Organisation (ISRO) and was intimately involved in India's civilian space programme and military missile development efforts.[1] He thus came to be known as the Missile Man of India for his work on the development of ballistic missile and launch vehicle technology.
          He also played a pivotal organisational, technical, and political role in India's Pokhran-II nuclear tests in 1998, the first since the original nuclear test by India in 1974.[5]

    </p>

</section>
<section class="Books_section">
    <h3>Books</h3>
    <ul>
        <li>
            Developments in Fluid Mechanics and Space Technology by A P J Abdul Kalam and Roddam Narasimha;
             Indian Academy of Sciences, 1988.[196]
        </li>
        <li>India 2020: A Vision for the New Millennium by A P J Abdul Kalam, Y. S. Rajan; New York, 1998.</li>
<li>Wings of Fire: An Autobiography by A P J Abdul Kalam, Arun Tiwari; Universities Press, 1999.</li>
<li>The Luminous Sparks by A P J Abdul Kalam, by; Punya Publishing Pvt Ltd., 2004.</li>
<li>Mission India by A P J Abdul Kalam, Paintings by Manav Gupta; Penguin Books, 2005</li>
<li>Inspiring Thoughts by A P J Abdul Kalam; Rajpal & Sons, 2007</li>
<li>Envisioning an Empowered Nation by A P J Abdul Kalam with A Sivathanu Pillai; Tata McGraw-Hill, New Delhi</li>
    </ul>
</section>
<footer>Read more about A. P. J. Abdul Kalam</footer>
        </div>




    </div>

</body>
</html>
