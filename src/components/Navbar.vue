<template>
    <div class="container">
        <nav class="navbar fixed-top">
            <div class="navbar-left">
                <a href="#" class="title">JinibbokShop</a><br>
                <a href="#" class="sub-title">Selling all your favorite Kpop Stuff with love!</a><br>
            </div>
            <div class="navbar-right">
                <ul>
                    <li class="nav-item active"><a href="#">Beranda</a></li>
                    <li><a href="#visimisi">Visi Misi</a></li>
                    <li><a href="#service">Service</a></li>
                    <li><a href="#ourwork">Our Produk</a></li>
                    <li><a href="#testimoni">Testimoni</a></li>
                    <li><a href="#joinus">Join Us</a></li>
                </ul>
            </div>
        </nav>
    </div>
</template>

<style scoped>
a.title{
	color:#444; 
	font-weight:bold; 
	text-decoration:none; 
	font-size:30px; 
	line-height:50px; 
	padding:10px;
    padding-left: 30px;
}

a.sub-title{
	color:#444;  
	text-decoration:none; 
	font-size:12px; 
	line-height:20px; 
	padding:10px;
    padding-left: 30px;
}

.navbar{
	width:auto;
    height:100px;
    background:#abc4ff;
	border-radius:2px;
    position: fixed;
    padding-bottom: 20px;
}

.navbar-left{
    float:left;
}
.navbar-right{
    float:right;
	line-height:50px; 
    /* width:260px; */
    padding-right:60px;
}
.navbar ul{
    float:left;
    margin:0;
    padding:0;
}
.navbar li{
    float:left;
    list-style:none;
    margin:0;
    padding:0;
}
.navbar li a, .navbar li a:link {
    float: left;
    padding: 17px 12px;
    color: #444;
    text-decoration: none;
    position: relative;
    font-family: sans-serif;
    font-size: 14px;
}
.navbar li a:hover{
    background: #ddd;
    color: #444;
}
.navbar li li a, .navbar li li a:link {
    text-decoration: none;
    font-size: 16px;
    background: #444;
    color: #fff;
    width: 108px;
    padding: 0px 0px 0 12px;
    font-size: 12px;
    line-height: 35px;
}
.navbar li li a:hover{
    background: #ddd;
    color: #444
}
.navbar li ul{
    z-index:9999;
    position:absolute;
    left:-999em;
    height:auto;
    width:120px;
    margin-top:50px;
    border:1px solid #666;
}
.navbar li:hover ul,
.navbar li li:hover ul,
.navbar li li li:hover ul{left:auto;}
.navbar li:hover{position:auto;}
li a#dropdown{
    width: 96%;
    height: 50%;
    background-color: #9BC7D3;
    padding-left :5px;
}

</style>