<!doctype html>

    <head>
        <meta charset="utf-8">
        <meta name="viewport" content="width=device-width",initial-scale='1.0'>

        <title>
            Bootstrap Grid system
        </title>
    
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">
    
    <link rel="stylesheet" type="text/css" href="style7.css">
    <style>
    body
{
font-size:25px;
}
header{
top:0px;
background-color:antiquewhite;
color:black;
position:fixed;
left:0px;
width:100%;
font-size:20px;
font-family:'Times New Roman', Times, serif;
}
footer
{
background-color:antiquewhite;
color:black;
position:fixed;
left:0px;
bottom:0px;
width:100%;
font-size:30px;
text-align:center;
font-size:25px;
    font-family:Impact, Haettenschweiler, 'Arial Narrow Bold', sans-serif;
    font-weight:bold;
}

.a1
{
display:flex;
flex-direction:row;
margin-top:20px;
font-family:bold;
text-decoration:none;
flex-wrap:wrap;
}
div{
padding:5px;
}
#a
{
    padding-left:300px;
}
#B
{ 

    padding-right:100px;
    font-size:25px;
    font-family:Impact, Haettenschweiler, 'Arial Narrow Bold', sans-serif;
    font-weight:bold;
    position:fixed;
}
a
{
    text-decoration:none;
}
.a:hover{color:blue;}
.a1:hover{color:blue;}

*
{
    font-family:'Lato',sans-serif;
}

html,body{
    width: 100%;
    height:100%;
    display:100%;
    justify-content:center;
    align-items:center;
    background-color:darkslategray;
    font-size: 10px;

}

.container
{
margin-top:100px;
margin-bottom:70px;
    display:flex;
    justify-content:center;
    flex-wrap:wrap;
}
.cards
{
    width:300px;
    margin:10px;
    background-color: white;
    border-radius:10px;
    transition:0.2s
}
.card-img img{
    width:100%;
    height:180px;
    border-radius:10px 10px 0px 0px;
}
.card-body h2{
    text-align:center;
}
.card-body p{
    text-align:justify;
    margin-bottom:10px;
    padding:5px;
    font-size:15px;
}
.card-footer
{
    display:flex;
    justify-content:center;
    align-items:center;

}
.card-footer button{
    width:150 px;
    margin-top:30px;
    background:blue;
    color:white;
    border-radius:15px;
    border:2px solid black;
    font-size:17px;
    padding:6px;
    cursor:pointer;
    margin-bottom:10px;
    transition:0.2s;

}
.card-footer button:hover{
    background-color:white;
    color:black;
    border:2px sloid black;
}
.cards:hover{
    box-shadow: 3.9px 7.8px 7.8px hs1(0deg 0% 0% /0.38);
        transform:translateY(20px);
        background-color:antiquewhite;
        
        
    
}


</style>
</head>
<body>

<header>
<div class='a1'>
<div ID="B">HISTORICAL PLACES IN INDIA</div>
&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;
&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;
&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;

<div id='a' ><a href='#'>HOME</a></div>
<div id='b'><a href='#'>ABOUT</a></div>
<div id='c'><a href='#'>SERVICES</a></div>
<div id='d'><a href='#'>PORTFOLIO</a></div>
<div id='e'><a href='#'>CONTACT </a></div>
</div></header>

<div class="container">
    <div class="cards">
        <div class="card-img">
            <img src="https://1.bp.blogspot.com/-nCb575DjTBw/XtlVjaAqjCI/AAAAAAAAebE/NtRHHn8nKnkHrm-p2QkQGDMtrvzkr383gCK4BGAsYHg/w1200-h630-p-k-no-nu/2880px-Golkonda_Fort_001.jpg">
        </div>
        <div class="card-body">
            <h1>Golconda</h1>
           <p>Golconda is a fortified citadel and ruined city located in the western outskirts of Hyderabad, Telangana, India. The fort was originally built by Kakatiya ruler Pratāparudra in the 11th century out of mud walls. It was ceded to the Bahmani Kings by Deo Rai, Rajah of Warangal during the reign of Sultan Muhammad Shah of the Bahmani Sultanate.</p>
        </div>
        <div class="card-footer">
       <button >
       READ MORE.......
       </button>
        </div>
    </div>

    <div class="cards">
        <div class="card-img">
        <img src="https://3.bp.blogspot.com/-ty6sAqo50b4/V0XIo8whMpI/AAAAAAAAEYI/Yb9nxhLzxS0RjqAOLCEDD11VSRQgD1JMwCLcB/s1600/CHARMINAR1.jpg" alt="">
        </div>
        <div class="card-body">
            <h1>Charminar</h1>
            <p>The Charminar is a monument located in Hyderabad, Telangana, India. Constructed in 1591, the landmark is a symbol of Hyderabad and officially incorporated in the emblem of Telangana. The Charminar's long history includes the existence of a mosque on its top floor for more than 425 years. While both historically and religiously significant, it is also known for its popular and busy local markets surrounding the structure, and has become one of the most frequented tourist attractions in Hyderabad. </p>

        </div>
        <div class="card-footer">
       <button >
       READ MORE.......
       </button>
        </div>
    </div> 

    <div class="cards">
        <div class="card-img">
           <img src="https://th.bing.com/th/id/OIP.nj64A_dSQJTjP3m0h4l8zgHaDn?pid=ImgDet&w=4407&h=2148&rs=1" alt="" class="img">

        </div>
        <div class="card-body">
            <h1>Mysore Palace</h1>

            <p>Mysore Palace, also known as Amba Vilas Palace, is a historical palace and a royal residence. It is located in Mysore, Karnataka, India. It used to be the official residence of the Wadiyar dynasty and the seat of the Kingdom of Mysore. The palace is in the centre of Mysore, and faces the Chamundi Hills eastward. Mysore is commonly described as the 'City of the Palaces', and there are seven palaces including this one.</p>

        </div>
        <div class="card-footer">
       <button >
       READ MORE.......
       </button>
        </div>
    </div>






</div>


<div class="container">
    <div class="cards">
        <div class="card-img">
            <img src="http://4.bp.blogspot.com/-MafjvvS0hrs/Vq4tG0pV7TI/AAAAAAAALUM/nnBmVfqkSl4/s1600/Belum%2BCaves%2B13.jpg" class="img">

        </div>
        <div class="card-body">
            <h1>Belum Caves</h1>
            <p>The Belum Caves, located in Nandyala district of Andhra Pradesh's Rayalaseema region, is the second largest cave system on the Indian subcontinent, known for its speleothems, such as stalactite and stalagmite formations. The Belum Caves have long passages, galleries, spacious caverns with fresh water and siphons. This cave system was formed over the course of tens of thousands of years by the constant flow of underground water from the now-disappeared river Chitravathi.</p>
        </div>
        <div class="card-footer">
       <button >
       READ MORE.......
       </button>
        </div>
    </div>

    <div class="cards">
        <div class="card-img">
            <img src="https://th.bing.com/th/id/OIP.7im17fy4bG5_lXHuRjvvwQHaDt?w=293&h=174&c=7&r=0&o=5&pid=1.7">

        </div>
        <div class="card-body">
            <h1>Lotus Temple</h1>
            <p>The Lotus Temple, located in New Delhi, India, is a Baháʼí House of Worship that was dedicated in December 1986. Notable for its lotus-like shape, it has become a prominent attraction in the city. Like all Bahá’í Houses of Worship, the Lotus Temple is open to all, regardless of religion or any other qualification. The building is composed of 27 free-standing marble-clad "petals" arranged in clusters of three to form nine sides, with nine doors opening onto a central hall with a height of slightly over 34 meters and a capacity of 1,300 people.</p>
        </div>
        <div class="card-footer">
       <button >
       READ MORE.......
       </button>
        </div>
    </div> 

    <div class="cards">
        <div class="card-img">
            <img src="https://th.bing.com/th?id=OLC.M2JE%2fcrczzy8BQ480x360&w=186&h=140&c=8&rs=1&qlt=90&o=6&pid=3.1&rm=2" class="img">
        </div>
        <div class="card-body">
            <h1> Elephanta Caves</h1>

           <p>The Elephanta Caves are a collection of cave temples predominantly dedicated to the Hindu god Shiva, which have been designated a UNESCO World Heritage Site. They are on Elephanta Island, or Gharapuri, in Mumbai Harbour, 10 kilometres east of Mumbai in the Indian state of Mahārāshtra. The island, about 2 kilometres west of the Jawaharlal Nehru Port, consists of five Hindu caves, a few Buddhist stupa mounds that date back to the 2nd century BCE, and two Buddhist caves with water tanks.</p>
        </div>
        <div class="card-footer">
       <button >
       READ MORE.......
       </button>
        </div>
    </div>
</div>

<div class="container">
    <div class="cards">
        <div class="card-img">
            <img src="https://th.bing.com/th/id/OIP.31U9ZvkNowjOBQmaBCp-6AHaEH?w=319&h=180&c=7&r=0&o=5&pid=1.7">

        </div>
        <div class="card-body">
            <h1>Veerabhadra temple</h1>

            <p>Veerabhadra temple is a Hindu temple located in the Lepakshi, in the state of Andhra Pradesh, India. The temple is dedicated to the Virabhadra, a fierce incarnation of Lord Shiva. Built in the 16th century, the architectural features of the temple are in the Vijayanagara style with profusion of carvings and paintings at almost every exposed surface of the temple. It is one of the centrally protected monuments of national importance and is considered one of the most spectacular Vijayanagara temples.</p>

        </div>
        <div class="card-footer">
       <button >
       READ MORE.......
       </button>
        </div>
    </div>

    <div class="cards">
        <div class="card-img">
            <img src="https://th.bing.com/th/id/OIP.BEYj1oZ62qBgR6yY94fi3gHaE7?w=237&h=180&c=7&r=0&o=5&pid=1.7">

        </div>
        <div class="card-body">
            <h1>Qutb Minar</h1>
            <p>The Qutb Minar, also spelled Qutub Minar and Qutab Minar, is a minaret and "victory tower" that forms part of the Qutb complex, which lies at the site of Delhi's oldest fortified city, Lal Kot, founded by the Tomar Rajputs. It is a UNESCO World Heritage Site in the Mehrauli area of South Delhi, India. It is one of the most visited tourist spots in the city, mostly built between 1199 and 1220.

                It can be compared to the 62-metre all-brick Minaret of Jam in Afghanistan, of c.1190, which was constructed a decade or so before the probable start of the Delhi tower.</p>
        </div>
        <div class="card-footer">
       <button >
       READ MORE.......
       </button>
        </div>
    </div> 

    <div class="cards">
        <div class="card-img">
            <img src="https://www.bing.com/th?id=OIP.jXqs1wdTJay1twMsYFbESQHaFj&w=176&h=185&c=8&rs=1&qlt=90&o=6&pid=3.1&rm=2">

        </div>
        <div class="card-body">
            <h1>Golden Temple</h1>
            <p>The Golden Temple also known as the Harimandir Sahib , or the Darbār Sahib, 'exalted court',or Suvaran Mandir is a gurdwara located in the city of Amritsar, Punjab, India. It is the preeminent spiritual site of Sikhism. It is one of the holiest sites in Sikhism, alongside the Gurdwara Darbar Sahib Kartarpur in Kartarpur, and Gurdwara Janam Asthan in Nankana Sahib.</p>
        </div>
        <div class="card-footer">
       <button >
       READ MORE.......
       </button>
        </div>
    </div>
</div>
</section>
<footer>DESIGNED BY Shaik.Arshiya</footer>    
</body>
           </html>
