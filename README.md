# dezembro-index.html
body{background-color:#CBDEF3}

<style>
     img{width:500px;height:300px;border: 20px solid 
     	#000000;
     }
     img:hover{ zoom:100%;

     }


     .parallax {
  /* The image used */
  background-image: url("C:/meu primeiro site/fotos/chakras.jpg");

  /* Set a specific height */
  min-height: 500px; 

  /* Create the parallax scrolling effect */
  background-attachment: fixed;
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
}
<style>
        *{ margin: 0;padding: 0; }
        body{ font-family: "Verdana"; }
        a{ text-decoration: none; color: #000; }
        a:hover{ }
 
        #all{
            width: 580px;
            height: 80px;
            line-height: 80px; /* centraliza na horizontal */
            background-color: #f1f1f1;
            border: 1px dashed #ccc;
            margin: 0 auto;
        }
        ul.menu{
            text-align: center; /* centraliza na horizontal */
        }
        ul.menu li{
            display: inline-block; /* centraliza na horizontal */
            margin-left: 200px
              
        }
        ul.menu li a{
            background-color: #008000;
            border-radius: 6px;
            padding: 6px 10px;
            color: #fff;
        }
        ul.menu li a:hover{
            background-color: #8BBADC;
        }

    
    </style>





@media screen and(max-width: 400px){

}

@media screen and(min-width: 1200px){
	.container{
		display: grid;
		grid-template-columns: 100% 30%;
		justify-content: space-between;
		padding: 10px 5%;
		grid-template-areas: 
			"header  header"
			"main aside"
		;
	}


	header{grid-area:header; height: 100px; background: red;}

	main{grid-area:main ; height: 1000px; background:white; }


	body, html {
  height: 100%;

}


</style>
