# Exp-2-Create-a-commercial-website-using-HTML-CSS

## AIM:
To create a commercial website using html and css.

## SOFTWARE:
Visual Studio Code.

## ALGORITHM:
1.Create a new HTML file and save it with a .html extension.Begin with the basic structure by adding the declaration at the top.

2.Set up the Head:

  Inside the <head> element, add the <title> element and give it a meaningful title for your website.
  Link your CSS file by adding the <link> element with the rel attribute set to "stylesheet" and 
  the href attribute pointing to your CSS file.
3.Develop the Content:

 Divide the main content area into sections using appropriate HTML elements like <section>, <div>, or <article>.
 Use headings <h1> to <h6> to structure your content hierarchically.
 Incorporate text, images, videos, and other media within the content sectionS
4.Style with CSS:

  Create a new CSS file and save it with a .css extension. Select the elements you want to style using CSS selectors. Apply styles using properties and     values. For example, you can change colors, fonts, sizes, margins, and padding.

5.Find a web hosting provider to host your website online. Upload your HTML, CSS, and any other necessary files to the hosting server.

6.Test your website again after deployment to ensure it works as intended.

## PROGRAM:
### HTML CODE:
```
<!DOCTYPE html>
<html lang='en'>

<head>
	<link rel="stylesheet" href="webpage.css">
</head>
	<body class="bg" ></body>
		<div class="topcontainer">
			<div class="toppage">Offerings Whywealthy  Stories Help</div>
			<div class="top-right"><a href="login.html"><button class="button1"> Login</button></a></div>
			<div class="words">Explore the life you want to live.</br>Put your money to work</br>
			<button class="button2">Get in touch</button></div>
		  </div>
		  <div class="middlecontain">
		<table>
		<th style="color: rgba(114, 51, 195, 0.912);font-size: 38px;">Black Advantange</th>
		<tr style="color: aliceblue;font-size: 28px;">
			
			<td ><img src="fe.png" width="90px;"></br>&nbsp;Financial Expertise</td>
			<td ><img src="at.png" width="90px;"></br>&nbsp;Advanced Technology</td>
				<td><img src="ra.png" width="110px;" style="padding-bottom: 6%;"></br>&nbsp;Right Advice</td>
				</tr>
				<tr style="color: aliceblue;font-size: 20px; ">
			<td>Comprehensive guidance from skilled financial analysts on investment 
				strategies, risk assessment, and portfolio management.</td>
			
				<td>Specialized insights and recommendations from experienced technology consultants to optimize 
				business processes and leverage advanced technologies.</td>
			
				<td>Trusted advice from qualified advisors to make informed decisions and achieve desired outcomes 
				in various domains, such as finance, technology, and beyond.</td>
			</tr>
	</table>
	</div>
    <div class="endcontain">
	<p class="h">ANALYSIS OF YOUR WEALTH</br></p>
		
		<p class="h1">Helping you connent the dots.</br>So you can see what life could</br> look like into the future</p>
		<p class="h2">The Personal Wealth Analysis represents</br> a comprehensive picture of your current wealth planning circumstances and suggestions for improvement.</p >
	 </p>
	</div>
	<center>	  <footer  style="color: aliceblue;">
	<p>&copy; 2023 Student Website. All rights reserved.</p>
</footer></center>
	
	</html>
		
```  
### CSS code:
```
.toppage{
    color:white;
    font-family:Arial, Helvetica, sans-serif;
    position: absolute;
    top: 18px;
    left: 16px;
    cursor: pointer;
    padding-left:10%;
    word-spacing: 35px;
}
.top-right {
    position: absolute;
    top: 8px;
    right: 16px;
    color:white;
  }
.topcontainer {
    position: relative;
    text-align: center;
    color: white;
  }
.words{
    position: absolute;
    top:155px;
    bottom: 18px;
    left: 10%;
    font-size: 300%;
}
.button1{
    border-radius: 20px;
    padding: 14px 40px;
    background-color: transparent;
    cursor: pointer;
    color:white;
    
}
.button2{
    border-radius: 20px;
    padding: 11px 40px;
    background-color: black;
    cursor: pointer;
    color:white;
}
.bg{
    background-repeat: no-repeat;
    background-image: url("top.png");
    image-rendering: pixelated; 
    background-color:black; 
    background-position: center top;
     background-size: 100% 500px ;
} 
 .middlecontain{
    padding-top: 37%;
    padding-left:10px;
} 
th,td{
   padding: 25px 50px 25px 100px;
}
.endcontain{
    padding-top:50%; 
    background-image: url("bottom.png");
    background-repeat: no-repeat;
    image-rendering: pixelated; 
    background-color:black; 
    background-size: 100% 100%;
    position: relative;
    white-space: nowrap;
}
.h{
    position: absolute;
    bottom: 85%;
    left: 7%;
    color:rgb(0, 255, 251);
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
}
.h1{
    position: absolute;
    bottom: 64%;
    left: 7%;
    color: aliceblue;
    font-size: 210%;
}
.h2{
    position: absolute;
    bottom: 58%;
    left: 7%;
    color: aliceblue;
    font-size: 100%;
}

```
## OUTPUT:
![image](https://github.com/sangeethak15-AI/Exp-2-Create-a-commercial-website-using-HTML-CSS/assets/93992063/0c14e999-03c6-4f9a-9ea5-52d8acef3e0a)
![image](https://github.com/sangeethak15-AI/Exp-2-Create-a-commercial-website-using-HTML-CSS/assets/93992063/89411008-8d78-427a-b5fd-385f06b8357b)
![image](https://github.com/sangeethak15-AI/Exp-2-Create-a-commercial-website-using-HTML-CSS/assets/93992063/21e066c4-3535-4d8e-b967-f2a3b0c7edd5)
### Additional login page:
![image](https://github.com/sangeethak15-AI/Exp-2-Create-a-commercial-website-using-HTML-CSS/assets/93992063/fe094cfe-d833-437e-a29d-aae2890d7cdc)

## RESULT:
Thus the website is created.  
  
