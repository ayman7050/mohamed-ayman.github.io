# mohamed-ayman.github.io
<!DOCTYPE html>
<html lang = "en">
	<head>
		<title>Module 2 Solution</title>
		<!--meta data for the browser-->
		<meta author = "mohamed ayman">
		<meta title = "Module-2-Solution">
		<meta charset = "UTF-8">
		<meta name = "viewport" content = "width=device-width, initial-scale = 1">
		<link rel = "stylesheet" href = "css-module2.css">
    <style>
    

h1{font-size: 40px;
text-align: center;

}

body{
    font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
}

section{
	
	margin-top: 25px;
}



p{
	
	background-color: #bbbbbb;
	
	
	padding: 45px 10px 10px 10px;
	border: 1px solid black;
    font-size: 18px;
}

#title1{
	background-color: rgb(206, 110, 126);
	
	float: right;
	position: relative;
	top: 0px;
	
	padding: 7px 45px 7px 45px;
	border: solid black 1px;
    
}

#title2{
	background-color: #fc5757;
	float: right;
	position: relative;
	top: 0px;
	
	padding: 2px 45px 7px 45px;
	border: solid black 1px;

}

#title3{
	background-color: #dddb46;
	float: right;
	position: relative;
	top: 0px;
	
	padding: 2px 45px 7px 45px;
	border: solid black 1px;

}


@media (min-width: 992px){

	.large-1, .large-2, .large-3{
		float: left;
	}

	

	.large-1{
		width: 30%;
		margin-left: 30px;
		margin-right: 30px;
	}

	.large-2{
		width: 30%;
		margin-right: 15px;
	}

	.large-3{
		width: 30%;
	}

}


@media (min-width: 768px) and (max-width: 991px)
{
	.med-1, .med-2, .med-3{
		float: left;
	}

	
	.med-1{
		width: 45%;
		margin-left: 30px;
	}

	.med-2{
		width: 45%;
		margin-left: 20px;
		margin-right: 5px;
	}

	.med-3{
		width: 92.25%;
		margin-left: 30px;
	}

}



@media (max-width: 767px)
{
	.small-1, .small-2, .small-3{
		float: left;
	}

	
	.small-1{
		width: 100%;
	}

	.small-3{
		width: 100%;
	}

	.small-3{
		width: 100%;
	}

}
    </style>
	</head>
	<body>
		<h1>Our Menu</h1>
		
		<section class = "large-1 med-1 small-1">
			
			<p id = "title1">Chicken</p>
				
				<p>ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore mogna aliqua.Ut enim ad minim veniam,quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
		</section>
		<section class = "large-2 med-2 small-2">
			<p id = "title2">Beef</p>
				<p>ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore mogna aliqua.Ut enim ad minim veniam,quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
		</section>
		<section class = "large-3 med-3 small-3">
			<p id = "title3">Sushi</p>
				<p>ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore mogna aliqua.Ut enim ad minim veniam,quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
		</section>
	</body>
</html>
