 <HTML>
  <HEAD>
<meta name="description" content="Homepage for personal website on hobbies,fun and travel.">
<meta name="keywords" content="hobbies,fun,travel,pranavbahl poems,poems view,page poems,pranavbahl poem, view poems,Top 10 poems">
<meta name="author" content="Pranav Bahl">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
 </HEAD>
 <body>
 <SCRIPT>
	function passWord() {
	var testV = 1;
	var pass1 = prompt('Please Enter Your Password',' ');
	while (testV < 3) {
	if (!pass1) 
	history.go(-1);
	if (pass1.toLowerCase() == "single") {
	alert('You Got it Right!');
	window.open('Poems.html');
	break;
	} 
	testV+=1;
	var pass1 = 
	prompt('Access Denied - Password Incorrect, Please Try Again.','Password');
	}
	if (pass1.toLowerCase()!="password" & testV ==3) 
	history.go(-1);
	return " ";
	} 
	</SCRIPT>
	<CENTER>
	<FORM>
	<input type="button" value="Enter Protected Area" onClick="passWord()">
	</FORM>
	</CENTER>

 <marquee behavior="scroll" direction="left" scrollamount="5">Content under construction, until then static poems only :/</marquee>

 <button onclick="window.location.href = 'https://pranavbahl.me/Poems.html';">Poems</button><br><br>
 </body>

