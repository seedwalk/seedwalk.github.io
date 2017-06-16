<html>
<head>
	<title>TwoPage Scrolling</title>
	<script src="https://ajax.googleapis.com/ajax/libs/jquery/2.1.3/jquery.min.js"></script>
	<script src="http://ajax.googleapis.com/ajax/libs/jqueryui/1.11.2/jquery-ui.min.js"></script>
</head>
<style>
	body {
		background: #0F062C;
		color: white;
		margin: 0;
		overflow: hidden;
	}
	.container {
		position: relative;
		top:0;
		left:0;
		width: 100%
	}
	.halfscreen {
		position: relative;
		width: 50%;
		float:left;
		box-sizing: border-box;
		overflow: hidden;
	}

	section {
		position:relative;
		float: left;
		width: 100%;
		box-sizing: border-box;
	}

	.imgLeft {
		position: relative;
		top: 50%;
		margin-top: -200px;
		left: 100%;
		margin-left: -200px;
	}
	.imgRight {
		position: relative;
		top: 50%;
		margin-top: -200px;
		left: 0px;
		margin-left: -200px;
	}
</style>
<body>
	
	<div id="sideLeft"  class="halfscreen"></div>
	<div id="sideRight" class="halfscreen"></div>
	
</body>

<script>	var windowHeight = $(window).height();

	var sections = [];
	sections[0] = "#69C9BA";
	sections[1] = "#C4D600";
	sections[2] = "#F1B434";
	sections[3] = "#DFE3EB";
	sections[4] = "#AD1AAC";
	sections[5] = "#B587B8";
	sections[6] = "#00A9E0";

	var sectionsb = [];
	sectionsb[6] = "#69C9BA";
	sectionsb[5] = "#C4D600";
	sectionsb[4] = "#F1B434";
	sectionsb[3] = "#00A9E0";
	sectionsb[2] = "#AD1AAC";
	sectionsb[1] = "#B587B8";
	sectionsb[0] = "#DFE3EB";

	function SectionObj(backgroundColor, number, side) {
		this.section = document.createElement("section");
		$(this.section).addClass("elementSection");
		$(this.section).css('background-color', backgroundColor);
		$(this.section).css('height', windowHeight);

		var img = document.createElement('img');
		
		number = (side =="right") ? number : number +1;
		if (side=="right") {
			$(img).addClass('imgRight');
		}
		else {
			number +1;
			$(img).addClass('imgLeft');
		}
		img.src = number+".png"
		$(this.section).append(img);
	}

	for (i=0;i<sections.length; i++){
		var element = new SectionObj(sections[i], i, 'left');
		$('#sideLeft').append(element.section);
	}

	for (i=sections.length;i>0; i--){
		var newi = i-1;
		var element = new SectionObj(sectionsb[newi], i, 'right');
		$('#sideRight').append(element.section);
	}
	var SectionsToUseForRightTop = sections.length -1;
	var sectionRightTop= (windowHeight * SectionsToUseForRightTop) *-1;
	$("#sideRight").css('top', sectionRightTop + "px");
	console.log(windowHeight);
	

	var lastScrollTop = $(window).scrollTop();
	var actualScrollPos = 0;
	var actualScrollPosLeft = 0;
	var actualScrollPosRight = sectionRightTop;
	var animationSpeed = 1200;
	var easingType = 'easeOutBounce';

	function ScrollDown() {
		var SectionsToUseForScrollDown = sections.length -1;
		var totalScrollTop = windowHeight * SectionsToUseForScrollDown;
		if (actualScrollPos < totalScrollTop) {
			actualScrollPosLeft =  actualScrollPosLeft - windowHeight;
			actualScrollPosRight =  actualScrollPosRight + windowHeight;

			actualScrollPos = actualScrollPos + windowHeight;
			$('#sideLeft').animate({
				top: actualScrollPosLeft
			}, animationSpeed, easingType);
			$('#sideRight').animate({
				top: actualScrollPosRight
			}, animationSpeed, easingType);	
		}
		
	}

	function ScrollUp() {
		if (actualScrollPos > 0) {
			actualScrollPosLeft =  actualScrollPosLeft + windowHeight;
			actualScrollPosRight =  actualScrollPosRight - windowHeight;

			actualScrollPos = actualScrollPos - windowHeight;
			$('#sideLeft').animate({
				top: actualScrollPosLeft
			}, animationSpeed, easingType);
			$('#sideRight').animate({
				top: actualScrollPosRight
			}, animationSpeed, easingType);	
		}
		
	}


	$( window ).scroll(function(event) {
		timeNow = new Date().getTime(),
		quietPeriod = 500;

		var newTop = sectionRightTop + ( $( "body" ).scrollTop() * 2);
		$("#sideRight").css('top', newTop + "px");
	});



	var lastAnimation = new Date().getTime()  

	function init_scroll(event, delta) {
		var deltaOfInterest = delta,
		timeNow = new Date().getTime(),
		quietPeriod = 500;

   		// Cancel scroll if currently animating or within quiet period
   		if(timeNow - lastAnimation < quietPeriod + animationSpeed) {
   			event.preventDefault();
   			return;
   		}

   		if (deltaOfInterest < 0) {
   			ScrollDown();
   		} else {
   			ScrollUp();
   		}
   		lastAnimation = timeNow;
   	}

   	$(document).bind('mousewheel DOMMouseScroll', function(event) {
   		event.preventDefault();
   		var delta = event.originalEvent.wheelDelta || -event.originalEvent.detail;
   		init_scroll(event, delta);
   	});

	// if(timeNow - lastAnimation < quietPeriod + settings.animationTime) {
	// 	event.preventDefault();
	// 	return;
	// }
	// 	//if (scrolling) {

	// 		var st = $(this).scrollTop();
	// 		if (st > lastScrollTop){
	// 			ScrollDown();
	// 		} else {
 //      			// upscroll code
 //      		}
 //      		lastScrollTop = st;
 //      		scrolling =false;
 //      	// }
 //      	// else {
 //      	// 	event.preventDefault();
 //      	// 	return;
 //      	// }

 //      	lastAnimation = timeNow;







	//$(".sideLeft").onepage_scroll();



</script>

</html>