<script>
    function expandIt(id) {
      var linkObj = document.getElementById(id+"_link");
      var textObj = document.getElementById(id);
      if (textObj.style.display == "block") {
        textObj.style.display   = "none";
        linkObj.innerHTML       = "Show Abstract";
        linkObj.style.color = "#48AE00";   
      } else {
        textObj.style.display   = "block";
        linkObj.innerHTML       = "Hide Abstract";
	   linkObj.style.color = "#48AE00";  
      }
    }
</script>

 <!--
<p style="margin-bottom: 10"> &nbsp; &nbsp; 1. &nbsp; <a href="https://hhsandoval.github.io/E7427S2022.pdf"> <strong> ECO 7427 </a> </strong> <br> 
&nbsp; &nbsp; &nbsp;  &nbsp; &nbsp; <a href="https://hhsandoval.github.io/"> Syllabus </a> <br> &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; <br> &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; <font color=FF4F00> <i> University of Florida </i></font>. &nbsp; &nbsp; &nbsp; &nbsp; <font size="2">[<a id="hhsg_link" href="javascript:expandIt('hhsg');" font size="2"; style="color: #48AE00"> Show Abstract/a>]<br /> <div id="hhsg" style="display: none" class="abstract">
<p style="margin-left:4em; margin-right: 45%; text-align:justify" > <b> Abstract: </b> 
Hola, me llamo Hector. </div> </p> </font size="3">

<li><p>   
<a href="javascript:showHide('mno_crystalballs');">Show/Hide Abstract</a>
<div id="mno_crystalballs" class="abstract" style="display:none;"> We truthfully.
</div>
</p></li>   
 
--> 
   
