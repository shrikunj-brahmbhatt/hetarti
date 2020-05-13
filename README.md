
<!DOCTYPE html>
<html>
<head>
<title>hetarti.in site for GSSSB study Material</title>
<meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
 <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.4.1/jquery.min.js"></script>
 <script>
$(document).ready(function(){
  $("a:first").click(function(){
    $("iframe").removeClass("seen").addClass("gone");
	$("#intro").removeClass("rhom").addClass("hom");
	$("#myDiv").removeClass("resp-container");
  });
});
</script>
<script>
$(document).ready(function(){
  $("a:not(:first)").click(function(){
    $("#myDiv").addClass("resp-container");
	$("iframe").removeClass("gone").addClass("seen");
	$("#intro").removeClass("hom").addClass("rhom");
});
});
</script>
<script>
$(document).ready(function(){
  $('.active').trigger('click');
});
</script>
<script>
function myFunction() {
  var x = document.getElementById("myTopnav");
  if (x.className === "topnav") {
    x.className += " responsive";
  } else {
    x.className = "topnav";
  }
}
</script>
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<meta name="viewport" content="width=device-width, initial-scale=1" />
<style>
.sitename{
padding:0;
background-color:dodgerBlue;
color:white;
text-align:center;
overflow:hidden;
}

body {
  background-image: url("https://drive.google.com/uc?id=12kQjAM4Pa6ARzyWCKPW1wrlMr1x83Mwq");
  margin:0;font-family:Arial;	
}
.hom{
  margin-left:20px; 	
  margin-right:10px; 
  margin-top:2px; 
  margin-bottom:10px; 
  padding-top:10px;
  padding-right:100px;
  padding-bottom: 100px;
  padding-left:100px;
  top:0;
  float:left;
  overflow: hidden; 

}
.rhom{
    
   overflow: hidden;
   visibility: hidden;
  
}
.seen {
      visibility: visible;
      }
  .gone {
 visibility: hidden;
         }
.footer{
padding: 0;
border: 1px solid black;
color:white;
text-align:center;
background-color:dodgerBlue;
overflow:hidden;
}

.topnav {
  overflow: hidden;
  background-color: #333;
}
.topnav a {
  float: left;
  display: block;
  color: #f2f2f2;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
  font-size: 17px;
}

.active {
  background-color: #4CAF50;
  color: white;
}

.topnav .icon {
  display: none;
}

.dropdown {
  float: left;
  overflow: hidden;
}

.dropdown .dropbtn {
  font-size: 17px;    
  border: none;
  outline: none;
  color: white;
  padding: 14px 16px;
  background-color: inherit;
  font-family: inherit;
  margin: 0;
}

.dropdown-content {
  display: none;
  position: absolute;
  background-color: #f9f9f9;
  min-width: 160px;
  box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
  z-index: 1;
}

.dropdown-content a {
  float: none;
  color: black;
  padding: 12px 16px;
  text-decoration: none;
  display: block;
  text-align: left;
}

.topnav a:hover, .dropdown:hover .dropbtn {
  background-color: #555;
  color: white;
}

.dropdown-content a:hover {
  background-color: #ddd;
  color: black;
}

.dropdown:hover .dropdown-content {
  display: block;
}

.resp-container {
    position: relative;
    overflow: hidden;
    padding-top: 46.25%;
	height:500px;
}
.resp-iframe {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    border: 0;
}

#customers {
  font-family: "Trebuchet MS", Arial, Helvetica, sans-serif;
  border-collapse: collapse;
  width: 100%;
}

#customers td, #customers th {
  border: 1px solid #ddd;
  padding: 8px;
}

#customers tr:nth-child(even){background-color: #f2f2f2;}

#customers tr:hover {background-color: #ddd;}

#customers th {
  padding-top: 12px;
  padding-bottom: 12px;
  text-align: left;
  background-color: #4CAF50;
  color: white;
}

@media screen and (max-width: 600px) {
		resp-container {
		position: relative;
		overflow: hidden;
		padding-top: 46.25%;
		height:500px;
		}
		.resp-iframe {
		position: absolute;
		top: 0;
		left: 0;
		width: 100%;
		height:500px;
		border: 0;
		}
	}

@media screen and (max-width: 600px) {
  .topnav a:not(:first-child), .dropdown .dropbtn {
    display: none;
  } 
  .topnav a.icon {
    float: right;
    display: block; 
    background-color: red;
  }
  


@media screen and (max-width: 600px) {
  .topnav.responsive {position: relative;}
  .topnav.responsive .icon {
    position: absolute;
    right: 0;
    top: 0;
    background-color: black;
  }
  .topnav.responsive a {
    float: none;
    display: block;
    text-align: left;
  }
  .topnav.responsive .dropdown {float: none;}
  .topnav.responsive .dropdown-content {position: relative;}
  .topnav.responsive .dropdown .dropbtn {
    display: block;
    width: 100%;
    text-align: left;
  }
	
}
@media screen and (max-width: 600px){
       .col{ width: 100%; }
        h3{ font-size: 2vw; word-spacing: 2vw;}
}
@media screen and (max-width: 600px){
             .het{ width: 100%;}
	   .hom{
                         width:100%;
                         padding: 0;
                         margin: 0;
		         position: relative;
			overflow:hidden;
		} 
            .rhom{ width: 100%; padding:0; margin:0;
                           float:left;
                           overflow: hidden; }
	         .sub{  
                           padding: 2px;
                           margin: 2px;}
}

</style>
</head>
<body>
                  <div class="het">
		<div class="sitename" class="col"><h1>hetarti.in</h1>
		</div>
	<div class="topnav" id="myTopnav" class="col">
		   <a href="#" class="active">Home</a>
		        <div class="dropdown">
				    <button class="dropbtn">Science<i class="fa fa-caret-down"></i></button>
					    <div class="dropdown-content">
						    <a href="https://drive.google.com/file/d/1rrjvYilqXuG-CSosl4ylCazx5R-n6yog/preview" target="iframe_a">Invention</a>	
						    <a href="https://drive.google.com/file/d/1QkaH3RIILZ8zOKyCo5TucSFzCZ0MrKTe/preview" target="iframe_a">Human Related</a>
						    <a href="https://drive.google.com/file/d/1-OObV2mI1T9vS7O00lRhDzPWZar6FpUf/preview" target="iframe_a">Gen.Science</a>
						    <a href="https://drive.google.com/file/d/1RgwpuTKKfccX84JTLnMtaaALiTuA9ha8/preview" target="iframe_a">Chemistry</a>
						    <a href="https://drive.google.com/file/d/1n6RysRaiSlVZ_k1rhag84KUxGGnbnmTg/preview" target="iframe_a">Gen.Maths</a>
						</div>
                </div> 
		   
		  

				<div class="dropdown">
				    <button class="dropbtn">Guj.Litreture<i class="fa fa-caret-down"></i></button>
						<div class="dropdown-content">
							<a href="https://drive.google.com/file/d/197GomCMRVs35LKViwlbuLDrmn3Urxkhw/preview" target="iframe_a">Birthplace</a>	
							<a href="https://drive.google.com/file/d/1IiTEoH5qSqPWVYbIQ1vrh12drKdts3dC/preview" target="iframe_a">Nicknames</a>
							<a href="https://drive.google.com/file/d/12trAczHlLYYMawbPthlDj7HLs9ckvqkH/preview" target="iframe_a">Krutio-Books</a>
							<a href="https://drive.google.com/file/d/1IiTEoH5qSqPWVYbIQ1vrh12drKdts3dC/preview" target="iframe_a">Lines-Poems</a>
							<a href="https://drive.google.com/file/d/1BWSIBoxuVVCB-CEI4q6eIQ6D-9LOVBUC/preview" target="iframe_a">Gen.Literature</a>
						</div>
                </div> 

				<div class="dropdown">
				    <button class="dropbtn">English<i class="fa fa-caret-down"></i></button>
						<div class="dropdown-content">
							<a href="#" target="_self">Fill the Blanks</a>	
							<a href="https://www.dropbox.com/s/j258eqk48bjis72/active.htm?raw=1">Active-Passive</a>
							<a href="#" target="iframe_a">Direct-Indirect</a>
							<a href="/storage/emulated/0/download/antonyms.html">Antonyms</a>
							<a href="#" target="iframe_a">Synonyms</a>
						    <a href="#" target="iframe_a">Change Degree</a>
							<a href="#" target="iframe_a">General English</a>
							<a href="#" target="iframe_a">One Word Subsitution</a>
						</div>
				</div>	
   
	 <div class="dropdown">
	    <button class="dropbtn">G.K Part 1<i class="fa fa-caret-down"></i></button>
			<div class="dropdown-content">
			   <a href="#">Schemes</a>
			   <a href="#">Gandhiji</a>
			   <a href="#">Starting</a>
			   <a href="#">Gujarat</a>
			   <a href="#">India-World</a>
			   <a href="#">Act and Rules</a>
			   <a href="#">Person Related</a>
			   <a href="#">Airports In India</a>
			   <a href="#">Days-Week</a> 
			</div>
     </div>
  
	<div class="dropdown">
	    <button class="dropbtn">G.K Part 2<i class="fa fa-caret-down"></i></button>
		   <div class="dropdown-content">
			  <a href="#">Full Forms</a>
			  <a href="#">Computer</a>
			  <a href="#">General</a>
			  <a href="#">Agriculture</a>
 	          <a href="#">Plants</a>
			  <a href="#">Economics</a>
			  <a href="#">Act and Rules</a>
		   </div>
     </div>

     <div class="dropdown">
	    <button class="dropbtn">Constitution<i class="fa fa-caret-down"></i></button>
		<div class="dropdown-content">
        <a href="D:\JC-SRK\site\Constitution.PDF #toolbar=0" target="iframe_a">Constitution</a>
		<a href="D:\JC-SRK\site\Panchayati Raj.PDF #toolbar=0" target="iframe_a">Panchayati Raj</a>
     </div>
     </div>	    

     <div class="dropdown">
	    <button class="dropbtn">Guj.Grammar<i class="fa fa-caret-down"></i></button>
		<div class="dropdown-content">
          <a href="#">Antonyms</a>
		  <a href="#">Adjectives</a>
		  <a href="#">Sanyojako</a>
		  <a href="#">Samas</a>
		  <a href="#">Chhand</a>
		  <a href="#">Sandhi</a>
		  <a href="#">Alankar</a>
		  <a href="#" target="iframe_a">Shabd kram</a>
		  <a href="#">Idioms</a>
		  <a href="#">Shabd Samuh</a>
		  <a href="#">Kartari-Karmani</a>
		  <a href="#">Gen.Grammar</a>
		  <a href="#">Nipat</a>
		</div>
      </div>
          <a href="javascript:void(0);" style="font-size:15px;" class="icon" onclick="myFunction()">&#9776;</a>
</div>
	      
	     	
		 <div> <table id="customers">
								<tr><th colspan="2"> Antonyms</th></tr>
								<tr><td> Clergy</td>  <td> 	Laity </td></tr>
								<tr><td>Captive	 </td>  <td> Free </td></tr>
								<tr><td> Noble</td>  <td>  	Ignoble</td></tr>
								<tr><td> Famous	</td>  <td> Obscure </td></tr>
								<tr><td> Corrupt	</td>  <td> Non corrupt </td></tr>
								<tr><td> Better </td>  <td> 	Worse </td></tr>
								<tr><td> Innocent</td>  <td> 	Guilty </td></tr>
								<tr><td> Democracy </td>  <td> Autocracy </td></tr>
								<tr><td> Inadvertently</td>  <td> 	Knowingly </td></tr>
								<tr><td>Cautious </td>  <td> Rash </td></tr>
								<tr><td> Abundance</td>  <td> Scarcity </td></tr>
								<tr><td> Fertile</td>  <td>	Barren  </td></tr>
								<tr><td>Make </td>  <td> 	Mar </td></tr>
								<tr><td>Clergy </td>  <td> Laity </td></tr>
								<tr><td>Deficit</td>  <td>	Surplus</td></tr>
								<tr><td> Wizard</td>  <td>Witch  </td></tr>
								<tr><td> Same</td>  <td> 	Polar </td></tr>
								<tr><td> Stag</td>  <td> 	Hind </td></tr>
								<tr><td>Virtue </td>  <td> 	Vice </td></tr>
								<tr><td>Noble </td>  <td> 	Ignoble </td></tr>
								<tr><td>Make</td>  <td> Raze </td></tr>
								<tr><td>Hope </td>  <td> Despair </td></tr>
								<tr><td> Grief</td>  <td>	Happiness  </td></tr>
								<tr><td>Robust(મજબૂત)</td>  <td> Weak </td></tr>
								<tr><td> Gradual(ધીમે-ધીમે)</td>  <td>Abrupt(અચાનક)  </td></tr>
								<tr><td>Mourn(શોક)</td>  <td>Rejoice (આનંદ) </td></tr>
								<tr><td> Condense</td>  <td> expand </td></tr>
				</table> 		
		 </div> 
			
		  <div class="footer" class="col">
					<a href="https://drive.google.com/file/d/1LXDSzIn64FtNip-MIuogIfceOapGfFmQ/preview?uc=drivesdk"
style="color:black; text-decoration: none;">Privacy Policy</a>&nbsp;&nbsp;&nbsp; 
					<a href="#" style="color:black; text-decoration:none;">Disclaimer</a>
		  </div>
  
</div>	


	

</body>
</html>
