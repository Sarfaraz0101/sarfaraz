


<!DOCTYPE html>
<html class="">
<head>
    <!-- title START -->
    <meta charset="UTF-8">
<title>University of Kashmir</title>
<meta name="description" content="Offical Web site of University of Kashmir">
<meta name="keywords" content="University of Kashmir,Kashmir University,University kashmir">
<meta name="author" content="Asim Banday">
<link rel="SHORTCUT ICON" href="favicon.ico">
<meta name="dcterms.rightsHolder" content="">
<meta name="dcterms.dateCopyrighted" content="2014">
<meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
<META HTTP-EQUIV="Pragma" CONTENT="no-cache">
<META HTTP-EQUIV="Expires" CONTENT="-1">


<!--<link class="theme_link" href="layout/styles/colours/red.css" rel="stylesheet" type="text/css" />
-->
<script>
    var layoutColorName = "Red";
    var layoutColor = "#B9282C";
</script>


<link class="theme_link" href="layout/styles/colours/Green.css" rel="stylesheet" type="text/css" />
<script>
    //layoutColor = "#B9282C";
    // layoutColorName = "red";
    layoutColor = "#84B533";
    layoutColorName = "Green";
</script>

<link href="layout/styles/main.css" rel="stylesheet" type="text/css" media="all">
<link href="layout/styles/mediaqueries.css" rel="stylesheet" type="text/css" media="all">


    <!-- title END -->
    <script language="javascript">
     var xmlHttp1;
        function GetXmlHttpObject() {
            var xmlHttp = null;
            try {
                // Firefox, Opera 8.0+, Safari
                xmlHttp = new XMLHttpRequest();
            }
            catch (e) {
                // Internet Explorer
                try {
                    xmlHttp = new ActiveXObject("Msxml2.XMLHTTP");
                }
                catch (e) {
                    xmlHttp = new ActiveXObject("Microsoft.XMLHTTP");
                }
            }
            return xmlHttp;
        }

        function GetNotificationList() {
            document.getElementById('lstDepartmentalNotifications').innerHTML = "loading...";
            document.getElementById('lnkDN').style.display = "none";
            xmlHttp1 = GetXmlHttpObject();
            if (xmlHttp1 == null) {
                alert("Your browser does not support AJAX!");
                return;
            }
            var url = "_Include/MultiPurposeAJAXFunctions.ashx?operation=GetNotificationList";
            xmlHttp1.onreadystatechange = updateNotificationList;
            xmlHttp1.open("POST", url, true);
            xmlHttp1.setRequestHeader("Content-type", "application/x-www-form-urlencoded");
            xmlHttp1.send("DepartmentID=" + document.getElementById('ddDepartment').value);
        }

        function updateNotificationList() {
            if (xmlHttp1.readyState == 4) {
                var responseString = xmlHttp1.responseText;
                if (responseString != "") {
                    document.getElementById('lstDepartmentalNotifications').innerHTML = responseString;
                    document.getElementById('lnkDN').style.display = "block";
                }
                else {
                    document.getElementById('lstDepartmentalNotifications').innerHTML = "";
                    document.getElementById('lnkDN').style.display = "none";
                }
                if (responseString == 'No record found') document.getElementById('lnkDN').style.display = "none";

            }
        }
    </script>
</head>
<body id="top">
    <!-- ################################################################################################ -->
    <!-- ################################################################################################ -->
    <!-- TOPBAR -->
    <!-- TOPBAR START -->
    <div class="wrapper row0">
  <div id="topbar">
    <div id="slidepanel" class="clear">
      <div class="fl_left">
        <form name="formSear" action="search.aspx" method="GET" onSubmit="return qs();" class="block clear">
          <input name="searWords" type="text" value="" size="35">
          <button class="button" name="Send" type="submit"><span class="icon-search"></span></button>
        </form>
      </div>
      <div class="fl_right">
        <ul class="social">
        <li><a class="button small green themeButton" title="Green" href="#"><span class="icon-tumblr green"><em>Green</em></span></a></li>
        <li><a class="button small red themeButton" title="Red" href="#"><span class="icon-tumblr red"><em>Green</em></span></a></li>
        <li><a class="button small blue themeButton" title="Blue" href="#"><span class="icon-tumblr blue"><em>Green</em></span></a></li>
        <li><a class="button small orange themeButton" title="Orange" href="#"><span class="icon-tumblr orange"><em>Green</em></span></a></li>
        <li><a class="button small purple themeButton" title="Purple" href="#"><span class="icon-tumblr purple"><em>Green</em></span></a></li>
         <!-- <li><a class="button small green" title="Facebook" href="#"><span class="icon-facebook green"><em>Facebook</em></span></a></li>
          <li><a class="socico-pinterest" title="Pinterest" href="#"><span class="icon-pinterest"><em>Pinterest</em></span></a></li>
          <li><a class="socico-twitter" title="Twitter" href="#"><span class="icon-twitter"><em>Twitter</em></span></a></li>
          <li><a class="socico-dribble" title="Dribble" href="#"><span class="icon-dribbble"><em>Dribble</em></span></a></li>
          <li><a class="socico-linkedin" title="LinkedIn" href="#"><span class="icon-linkedin"><em>LinkedIn</em></span></a></li>
          <li><a class="socico-google-plus" title="Google+" href="#"><span class="icon-google-plus"><em>Google+</em></span></a></li>
          <li><a class="socico-skype" title="Skype" href="#"><span class="icon-skype"><em>Skype</em></span></a></li>-->
        </ul>
      </div>
    </div>
    <!-- TOP BAR SLIDER BUTTON -->
    <div id="openpanel"><a id="slideit" class="icon-chevron-down" href="#slidepanel"></a><a id="closeit" class="icon-chevron-up" style="display:none;" href="#slidepanel"></a></div>
  </div>
</div>
    <!-- TOPBAR END -->
    <!-- ################################################################################################ -->
    <!-- ################################################################################################ -->
    <!-- HEADER -->
    <!-- HEADER START -->
    
<div class="wrapper row1">
  <header role="banner" id="header" class="clear">
    <div class="fl_left">
        <h1><a href="Default.aspx"><img class="logo" src="images/KUGreen.png" / alt="UNIVERSITY OF KASHMIR"></a><img src="images/logo-black.png" style="height:60px" alt="Har Ghar Tiranga"/><img src="images/naac.png" style="height:50px"/><a href="https://www.nirfindia.org/2022/UniversityRanking.html" target="_blank"><img src="images/rank2-new1.png"  style="height:50px" /></a>|<a href="https://www.topuniversities.com/universities/university-kashmir-srinagar" target="_blank"><img src="images/BRICS.png"  style="height:50px" /></a></h1>
     <!-- University of Kashmir
      <p class="times">From Darkness to Light</p>-->
    </div>
    <div class="fl_right right">
      <ul class="meta nospace inline">
        <li><span class="icon-phone"></span> +91 (194) 227 2096</li>
        <li><span class="icon-envelope-alt"></span> <a href="#">info@uok.edu.in</a></li>
      </ul>
      <nav>
        <ul class="nospace inline">
      <!-- <li><a href="NAACmessage.aspx">Vice Chancellor's Message on NAAC Accreditation</a></li>-->
          <!--<li><a href="Policies.aspx">University Policies</a></li>-->
          <li><a href="http://kuaa.uok.edu.in/" target="_blank">Alumni</a></li>
          
          <li><a href="Donations.aspx">Donations</a></li>
          <li><a href="Contact.aspx">Contact Us</a></li>
        </ul>
      </nav>
    </div>
  </header>
</div>
<!-- ################################################################################################ --> 
<!-- ################################################################################################ --> 
<!-- MAIN NAVIGATION -->
<div class="wrapper row2">
    <nav role="navigation" id="topnav" class="clear">
    <ul class="clear">
      <li id="lnkHome"><a href="default.aspx" title="Home">Home</a></li>
      <li id="lnkAbout"><a class="drop" href="#" title="Pages">About</a>
        <ul class="sub-menu">
          <li id="subLnkAboutUok"><a href="AboutUoK.aspx" style="text-transform:none;" title="About Us">University of Kashmir</a></li>
              <li id="Li1"><a href="VisionNMission.aspx" style="text-transform:none;" title="About Us">Vision and Mission</a></li>
           <li id="Li2"><a href="CoreValues.aspx" style="text-transform:none;" title="About Us">Our Core Values</a></li>
          <li id="subLnkAdministrator"><a href="administrator.aspx" title="Contact">Administration</a></li>
         <!-- <li id="subLnkPGC" class="last-child"><a href="formerVCs.aspx" title="Former Vice Chancellors">Former Vice Chancellors</a></li>-->
          <!--<li id="subLnkCampuses"><a href="Campuses.aspx" title="Campus">Campuses</a></li>
          <li id="subLnkColleges" class="last-child"><a href="Colleges.aspx" title="Affiliated Colleges">Affiliated Colleges</a></li>
          <li id="Li1" class="last-child"><a href="Colleges.aspx" title="Affiliated Colleges">Academic Calender</a></li>-->
        </ul>
      </li>
      <li id="lnkAcademics"><a class="drop"  href="#" title="Academics">Academics</a>
        <ul class="sub-menu">
        
		<li><a href="Colleges.aspx" title="Affiliated Colleges">Affiliated Colleges</a></li>
        
		<li><a href="degreeprograms.aspx" title="Coureses Offered">Courses Offered</a></li>
        <!--<li><a href="../download/Admission policy-2017.pdf" title="Admission Policy">Admission Policy</a></li>
		<li class="last-child"><a href="academiccalander.aspx" title="Acadenmic Calender">Academic Calender</a></li>-->
		        
        
        </ul>
      </li>
      <li id="lnkFaculty"><a href="faculty.aspx" title="Faculties">Schools</a></li>
       <li id="lnkCampus"><a href="Campuses.aspx" title="Campuses">Campuses</a></li>
      <li id="lnkResearch"><a href="research.aspx" title="Research Centres">Research Centres</a></li>
       <li id="lnkDirectorates" class="last-child"><a href="directorates.aspx" title="Directorates">Directorates</a></li>
     
    </ul>
  </nav>
</div>

    <!-- HEADER END -->
    <!-- ################################################################################################ -->
    <!-- ################################################################################################ -->
    <!-- FULL WIDTH SLIDER -->
       
 <marquee scrolldelay="100" style="color:#FDF33F;font-weight:bold;" onmouseover="stop();" onmouseout="start();"  >
 
 KU among top 100 universities in NIRF ranking, maintains top slot among J&K varsities....<a href="VCMsgNRIF.aspx" > read more</a>
 </marquee>
   <div class="wrapper full_width">
        <div class="flex-container flex-rtl">
            <div class="flexslider flex-homepage">
      
                    <div id="divList"><ul class='flex-slides'><li><a  href='' title='Digital Week' target=_blank> <img src='images/BannerImage/10231111.jpg'></a></li><li><a  href='https://uok.edu.in/admission.aspx' title='Admissions 2022' target=_blank> <img src='images/BannerImage/1017banner2022.jpg'></a></li><li><a  href='https://www.kashmiruniversity.net/imagegallery.aspx?gallery=1155' title='19th Annual Convocation' target=_blank> <img src='images/BannerImage/1019.jpg'></a></li><li><a  href='https://play.google.com/store/apps/details?id=net.kashmiruniversity&hl=en' title='Android App' target=_blank> <img src='images/BannerImage/1013.jpg'></a></li></ul></div>

            </div>

        </div>
    </div>
    <!-- ################################################################################################ -->
    <!-- ################################################################################################ -->
    <!-- INTRO -->
 
    <div class="wrapper row0">
        <div id="intro" class="clear">
            <ul class="nospace">
                <li><a class="block" href="admission.aspx">
                    <div class="block push30">
                        <span class="cc circle icon-bullhorn"></span>
                    </div>
                    <h6 class="nospace">
                        Admissions</h6>
                   
                </a></li>
               
                <li><a class="block" href="Examination.aspx">
                    <div class="block push30">
                        <span class="cc circle icon-pencil"></span>
                    </div>
                    <h6 class="nospace">
                        Examinations</h6>
                    
                </a></li> 
                <li><a class="block" href="http://deanres.uok.edu.in/">
                    <div class="block push30">
                        <span class="cc circle icon-bar-chart"></span>
                    </div>
                    <h6 class="nospace">
                        Research</h6>
                    <p class="nospace">
                    </p>
                </a></li>
                 <li><a class="block" href="https://egov.uok.edu.in/elearning/">
                    <div class="block push30">
                        <span class="cc circle icon-book"></span>
                    </div>
                    <h6 class="nospace">
                        E-Tutorials</h6>
                    
                </a></li>
               
                <li><a class="block" href="http://ddeku.edu.in" target="_blank">
                    <div class="block push30">
                        <span class="cc circle icon-group"></span>
                    </div>
                   
                    <h6 class="nospace">
                        Distance Education</h6>
                   
                </a></li>
                <li><a class="block" href="http://ail.uok.edu.in" target="_blank">
                    <div class="block push30">
                        <span class="cc circle icon-book"></span>
                    </div>
                    <h6 class="nospace">
                        Library</h6>
                    
                </a></li>
            </ul>
        </div>
    </div>
    <!-- ################################################################################################ -->
    <!-- ################################################################################################ -->
    <!-- CONTENT -->
    <form method="post" action="./" id="form1">
<div class="aspNetHidden">
<input type="hidden" name="__VIEWSTATE" id="__VIEWSTATE" value="/wEPDwULLTE1MDE2NDE2OTgPZBYEZg8WAh4JaW5uZXJodG1sBfIEPHVsIGNsYXNzPSdmbGV4LXNsaWRlcyc+PGxpPjxhICBocmVmPScnIHRpdGxlPSdEaWdpdGFsIFdlZWsnIHRhcmdldD1fYmxhbms+IDxpbWcgc3JjPSdpbWFnZXMvQmFubmVySW1hZ2UvMTAyMzExMTEuanBnJz48L2E+PC9saT48bGk+PGEgIGhyZWY9J2h0dHBzOi8vdW9rLmVkdS5pbi9hZG1pc3Npb24uYXNweCcgdGl0bGU9J0FkbWlzc2lvbnMgMjAyMicgdGFyZ2V0PV9ibGFuaz4gPGltZyBzcmM9J2ltYWdlcy9CYW5uZXJJbWFnZS8xMDE3YmFubmVyMjAyMi5qcGcnPjwvYT48L2xpPjxsaT48YSAgaHJlZj0naHR0cHM6Ly93d3cua2FzaG1pcnVuaXZlcnNpdHkubmV0L2ltYWdlZ2FsbGVyeS5hc3B4P2dhbGxlcnk9MTE1NScgdGl0bGU9JzE5dGggQW5udWFsIENvbnZvY2F0aW9uJyB0YXJnZXQ9X2JsYW5rPiA8aW1nIHNyYz0naW1hZ2VzL0Jhbm5lckltYWdlLzEwMTkuanBnJz48L2E+PC9saT48bGk+PGEgIGhyZWY9J2h0dHBzOi8vcGxheS5nb29nbGUuY29tL3N0b3JlL2FwcHMvZGV0YWlscz9pZD1uZXQua2FzaG1pcnVuaXZlcnNpdHkmaGw9ZW4nIHRpdGxlPSdBbmRyb2lkIEFwcCcgdGFyZ2V0PV9ibGFuaz4gPGltZyBzcmM9J2ltYWdlcy9CYW5uZXJJbWFnZS8xMDEzLmpwZyc+PC9hPjwvbGk+PC91bD5kAgEPZBYMAgEPFgIfAAWmKw0KICAgICAgICAgICAgIA0KICAgICAgICAgICAgPGxpPjxhIGhyZWY9J2h0dHBzOmV2ZW50cy83ODY4LnBkZicgdGFyZ2V0PSdfbmV3J3N0eWxlPSdmb250LXdlaWdodDpib2xkOyAgICBjb2xvcjojNGI0YzRhOyc+VXBkYXRlZCBTZWxlY3Rpb24gTm90aWZpY2F0aW9uIE5vLjogNiBvZg0KUEcsIDMtWWVhciBMTC5CIFByb2dyYW1tZXMgKFNlbGYgRmluYW5jZSBTZWF0IFF1b3RhKSBTZXNzaW9uLTIwMjI7IERhdGVkOiA8Yj4xNy04LTIwMjI8L2I+PC9hPjxsaT48YSBocmVmPSdodHRwczpldmVudHMvNzg3My5wZGYnIHRhcmdldD0nX25ldydzdHlsZT0nZm9udC13ZWlnaHQ6Ym9sZDsgICAgY29sb3I6IzRiNGM0YTsnPlNlbGVjdGlvbiBOb3RpZmljYXRpb24gTm8uNCBvZiANCk0gU2MgQmlvLVRlY2hub2xvZ3kgUHJvZ3JhbW1lDQpTZXNzaW9uLTIwMjI7IERhdGVkOiA8Yj4xNy04LTIwMjI8L2I+PC9hPjxsaT48YSBocmVmPSdodHRwczpldmVudHMvNzg3Mi5wZGYnIHRhcmdldD0nX25ldydzdHlsZT0nZm9udC13ZWlnaHQ6Ym9sZDsgICAgY29sb3I6IzRiNGM0YTsnPlNlbGVjdGlvbiBOb3RpZmljYXRpb24gTm8uOjENCjUtWWVhciBCQS1MTC5CLiBQcm9ncmFtbWUgKE1haW4gQ2FtcHVzKSBTZXNzaW9uLTIwMjI7IERhdGVkOiA8Yj4xNy04LTIwMjI8L2I+PC9hPjxsaT48YSBocmVmPSdodHRwczpldmVudHMvNzg3MS5wZGYnIHRhcmdldD0nX25ldydzdHlsZT0nZm9udC13ZWlnaHQ6Ym9sZDsgICAgY29sb3I6IzRiNGM0YTsnPlNlbGVjdGlvbiBMaXN0IG9mIEJBTExCIFNlc3Npb24gMjAyMjsgRGF0ZWQ6IDxiPjE3LTgtMjAyMjwvYj48L2E+PGxpPjxhIGhyZWY9J2h0dHBzOmV2ZW50cy83ODcwLnBkZicgdGFyZ2V0PSdfbmV3Jz5HZW5lcmFsIE1lcml0IExpc3Qgb2YgY2FuZGlkYXRlcyB3aG8gaGF2ZSBhcHBsaWVkIGZvciBhZG1pc3Npb24gdG8gQi5FZC4gUHJvZ3JhbW1lIHRocm91Z2ggRGlzdGFuY2UgTW9kZSBzZXNzaW9uLTIwMjIuOyBEYXRlZDogPGI+MTYtOC0yMDIyPC9iPjwvYT48bGk+PGEgaHJlZj0naHR0cHM6ZXZlbnRzLzc4NjkucGRmJyB0YXJnZXQ9J19uZXcnPkxpc3Qgb2YgY2FuZGlkYXRlcyB3aG8gaGF2ZSBhcHBsaWVkIGZvciBhZG1pc3Npb24gdG8gQi5FZC4gUHJvZ3JhbW1lIHRocm91Z2ggRGlzdGFuY2UgTW9kZSBTZXNzaW9uLTIwMjIgaGF2aW5nIG1lbnRpb25lZCBvbmx5IGRldGFpbHMgb2YgdGhlaXIgTWFzdGVycyBQcm9ncmFtbWUgb25seSBub3QgQkEvQlNDL0JDT00gb3Igb3RoZXINCnJlbGF0ZWQgUHJvZ3JhbW1lL0NvdXJzZSBEZXRhaWxzOyBEYXRlZDogPGI+MTYtOC0yMDIyPC9iPjwvYT48bGk+PGEgaHJlZj0naHR0cHM6ZXZlbnRzLzc4NjcucGRmJyB0YXJnZXQ9J19uZXcnPlNlbGVjdGlvbiBOb3RpZmljYXRpb24gTm8uIDEgRm9yIE11c2ljICYgRmluZSBBcnRzIFByb2dyYW1tZSBTZXNzaW9uLTIwMjI7IERhdGVkOiA8Yj4xNi04LTIwMjI8L2I+PC9hPjxsaT48YSBocmVmPSdodHRwczpldmVudHMvNzg2Ni5wZGYnIHRhcmdldD0nX25ldyc+VXBkYXRlZCBSb2xsIE9yZGVyIExpc3Qgb2YgdGhlIENhbmRpZGF0ZXMgd2hvIGhhdmUgYXBwZWFyIGluIHRoZSBFbnRyYW5jZSBUZXN0IGFuZCBhcHBsaWVkIGZvciBBZG1pc3Npb24gdG8gDQpQRyBQcm9mZXNzaW9uYWwgL05vbi1Qcm9mZXNzaW9uYWwgQ291cnNlcy9Qcm9ncmFtbWVzIHVuZGVyIFNlbGYtRmluYW5jZSBTZWF0IFF1b3RhIFNlc3Npb24tMjAyMjsgRGF0ZWQ6IDxiPjE2LTgtMjAyMjwvYj48L2E+PGxpPjxhIGhyZWY9J2h0dHBzOmV2ZW50cy83ODY1LnBkZicgdGFyZ2V0PSdfbmV3Jz5EYXRlIEV4dGVuZGVkIE5vdGljZSBmb3IgSW52aXRhdGlvbiBvZiBFbnRyaWVzIGZvciBTdWNjZXNzIFN0b3J5IG9uIFdhdGVyIFJlc291cmNlczogQ3VycmVudCBzdGF0dXMgYW5kIHN1c3RhaW5hYmxlIG1hbmFnZW1lbnQgYW5kIEJpb2RpdmVyc2l0eTogQ3VycmVudCBzdGF0dXMsIGNvbnNlcnZhdGlvbiBhbmQgc3VzdGFpbmFibGUgdXRpbGl6YXRpb247IERhdGVkOiA8Yj4xNi04LTIwMjI8L2I+PC9hPjxsaT48YSBocmVmPSdodHRwczpldmVudHMvNzg2Mi5wZGYnIHRhcmdldD0nX25ldyc+VXBkYXRlZCBDb3Vuc2VsaW5nIE5vdGljZS0yIGZvciBQRywgTExCLE1CQSwgTUJBLUZNIGFuZCBNQkEtQ01FIFByb2dyYW1tZXMgU2Vzc2lvbi0yMDIyOyBEYXRlZDogPGI+MTYtOC0yMDIyPC9iPjwvYT48bGk+PGEgaHJlZj0naHR0cHM6ZXZlbnRzLzc4NjQucGRmJyB0YXJnZXQ9J19uZXcnPkdlbmVyYWwgTWVyaXQgTGlzdCAgb2YgdGhlIENhbmRpZGF0ZXMgd2hvIGhhdmUgYXBwZWFyIGluIHRoZSBFbnRyYW5jZSBUZXN0IG9mIEJBLkxMQiBTZXNzaW9uLTIwMjI7IERhdGVkOiA8Yj4xMi04LTIwMjI8L2I+PC9hPjxsaT48YSBocmVmPSdodHRwczpldmVudHMvNzg2My5wZGYnIHRhcmdldD0nX25ldyc+Um9sbCBPcmRlciBMaXN0IG9mIHRoZSBDYW5kaWRhdGVzIHdobyBoYXZlIGFwcGVhciBpbiB0aGUgRW50cmFuY2UgVGVzdCBhbmQgYXBwbGllZCBmb3IgQWRtaXNzaW9uIHRvIFBHIFByb2Zlc3Npb25hbCAvTm9uLVByb2Zlc3Npb25hbCBDb3Vyc2VzL1Byb2dyYW1tZXMgdW5kZXIgU2VsZi1GaW5hbmNlIFNlYXQgUXVvdGEgU2Vzc2lvbi0yMDIyLjsgRGF0ZWQ6IDxiPjEyLTgtMjAyMjwvYj48L2E+PGxpPjxhIGhyZWY9J2h0dHBzOmV2ZW50cy83ODYxLnBkZicgdGFyZ2V0PSdfbmV3Jz44OHRoIEd1cnUgRGFrc2h0YSBGYWN1bHR5IEluZHVjdGlvbiBQcm9ncmFtbWUgKEhSREMpOyBEYXRlZDogPGI+MTItOC0yMDIyPC9iPjwvYT48bGk+PGEgaHJlZj0naHR0cHM6ZXZlbnRzLzc4NjAucGRmJyB0YXJnZXQ9J19uZXcnPkRhdGUgU2hlZXQgZm9yIEdFL09FIENvdXJzZXMgb2YgMm5kIFNlbWVzdGVyIChCYXRjaCAyMDIxKS47IERhdGVkOiA8Yj4xMS04LTIwMjI8L2I+PC9hPjxsaT48YSBocmVmPSdodHRwczpldmVudHMvNzg1OS5wZGYnIHRhcmdldD0nX25ldyc+QWRtaXNzaW9uIE5vdGlmaWNhdGlvbiBOby4xNSBvZiAyMDIyIEZvciA1LVllYXIgSU1CQSBQcm9ncmFtbWUgKFNlbGYtRmluYW5jZWQgU2VhdCBRdW90YSk7IERhdGVkOiA8Yj4xMC04LTIwMjI8L2I+PC9hPjxsaT48YSBocmVmPSdodHRwczpldmVudHMvNzg1OC5wZGYnIHRhcmdldD0nX25ldyc+QWRtaXNzaW9uIE5vdGlmaWNhdGlvbiBOby4xNCBvZiAyMDIyIEZvciBNQkEgJiBNQkEtRk0gUHJvZ3JhbW1lcyAoU2VsZi1GaW5hbmNlZCBTZWF0IFF1b3RhKTsgRGF0ZWQ6IDxiPjEwLTgtMjAyMjwvYj48L2E+PGxpPjxhIGhyZWY9J2h0dHBzOmV2ZW50cy83ODU3LnBkZicgdGFyZ2V0PSdfbmV3Jz5TZWxlY3Rpb24gTm90aWZpY2F0aW9uIE5vLjogMiANCkZvciA1LVllYXIgSW50ZWdyYXRlZCBNQkEgUHJvZ3JhbW1lIFNlc3Npb24tMjAyMjsgRGF0ZWQ6IDxiPjEwLTgtMjAyMjwvYj48L2E+PGxpPjxhIGhyZWY9J2h0dHBzOmV2ZW50cy83ODU2LnBkZicgdGFyZ2V0PSdfbmV3Jz5Ob3RpZmljYXRpb24gcmVnYXJkaW5nIFJldmlldyBvZiBDb3Vyc2UtQmFza2V0IG9mIENvcmUvRENFL09FL0dFIGNvdXJzZXMgZm9yIFBHICFzdCBTZW1lc3RlciBCYXRjaC0yMDIyOyBEYXRlZDogPGI+OC04LTIwMjI8L2I+PC9hPjxsaT48YSBocmVmPSdodHRwczpldmVudHMvNzg1NS5wZGYnIHRhcmdldD0nX25ldyc+U2VsZWN0aW9uIE5vdGlmaWNhdGlvbiBOby46IDUgb2YgDQozLVllYXIgTEwuQiBQcm9ncmFtbWUgKEthc2htaXIgTGF3IENvbGxlZ2UsIE5vd3NoZWhyYSkoUHJvZmVzc2lvbmFsKSBTZXNzaW9uLTIwMjI7IERhdGVkOiA8Yj44LTgtMjAyMjwvYj48L2E+PGxpPjxhIGhyZWY9J2h0dHBzOmV2ZW50cy83ODU0LnBkZicgdGFyZ2V0PSdfbmV3Jz5TZWxlY3Rpb24gTm90aWZpY2F0aW9uIE5vLjogMyBmb3IgUEcgRGlwbG9tYSBDb3Vyc2UgaW4gKEZyZW5jaCwgUnVzc2lhbiBhbmQgR2VybWFuKQ0KU2Vzc2lvbi0yMDIyOyBEYXRlZDogPGI+OC04LTIwMjI8L2I+PC9hPjxsaT48YSBocmVmPSdodHRwczpldmVudHMvNzg1My5wZGYnIHRhcmdldD0nX25ldyc+RGF0ZSBFeHRlbmRpbmcgTm90aWNlIGZvciBDb21wbGV0aW9uIG9mIEFkbWlzc2lvbiByZWxhdGVkIGZvcm1hbGl0aWVzIGZvciBTZXNzaW9uLTIwMjI7IERhdGVkOiA8Yj44LTgtMjAyMjwvYj48L2E+PGxpPjxhIGhyZWY9J2h0dHBzOmV2ZW50cy83ODUyLnBkZicgdGFyZ2V0PSdfbmV3Jz5GaW5hbCBBbnN3ZXIgS2V5cyBvZiBCQS5MTEIgRW50cmFuY2UgVGVzdCAyMDIyOyBEYXRlZDogPGI+OC04LTIwMjI8L2I+PC9hPjxsaT48YSBocmVmPSdodHRwczpldmVudHMvNzg1MS5wZGYnIHRhcmdldD0nX25ldyc+Tm90aWZpY2F0aW9uIHJlZ2FyZGluZyBSZS1vcGVuaW5nIG9mIGxpbmsgZm9yIHN1Ym1pc3Npb24gb2Ygb25saW5lIEFwcGxpY2F0aW9uIEZvcm0gIDQtWWVhciBCLlRlY2ggUHJvZ3JhbW1lcyBTZXNzaW9uLTIwMjI7IERhdGVkOiA8Yj44LTgtMjAyMjwvYj48L2E+PGxpPjxhIGhyZWY9J2h0dHBzOi8vdW9rLmVkdS5pbi9zZWxlY3Rpb25saXN0cy5hc3B4JyB0YXJnZXQ9J19uZXcnID5TZWxlY3Rpb24gTGlzdCBJSUkgb2YgUEcgRW50cmFuY2UgVGVzdCBTZXNzaW9uLTIwMjI7IERhdGVkOiA8Yj41LTgtMjAyMjwvYj48L2E+PGxpPjxhIGhyZWY9J2h0dHBzOmV2ZW50cy83ODUwLnBkZicgdGFyZ2V0PSdfbmV3Jz5TZWxlY3Rpb24gTm90aWZpY2F0aW9uIE5vLjogOCBvZiAyMDIyDQpNQkEgUHJvZ3JhbW1lIFNlc3Npb24tMjAyMg0KKElJVE0gQ29sbGVnZSwgSHlkZXJwb3JhOyBEYXRlZDogPGI+NS04LTIwMjI8L2I+PC9hPjxsaT48YSBocmVmPSdodHRwczpldmVudHMvNzg0OS5wZGYnIHRhcmdldD0nX25ldyc+U2VsZWN0aW9uIE5vdGlmaWNhdGlvbiBOby46IDQgb2YgMjAyMg0KUEcgYW5kIG90aGVyIFByb2dyYW1tZXMvQ291cnNlcyAoTWFpbiBDYW1wdXMpDQooTm9uLVByb2Zlc3Npb25hbCBhbmQgUHJvZmVzc2lvbmFsKTsgRGF0ZWQ6IDxiPjUtOC0yMDIyPC9iPjwvYT48bGk+PGEgaHJlZj0naHR0cHM6ZXZlbnRzLzc4NDgucGRmJyB0YXJnZXQ9J19uZXcnPlNlbGVjdGlvbiBOb3RpZmljYXRpb24gTm8uOiAzIG9mIDIwMjINCk1DQSwgTVNDSVQgUHJvZ3JhbW1lcyAoUHJvZmVzc2lvbmFsKQ0KKE5JRUxJVCwgUmFuZ3JldGggYW5kIElJVE0gSHlkZXJwb3JhKTsgRGF0ZWQ6IDxiPjUtOC0yMDIyPC9iPjwvYT48bGk+PGEgaHJlZj0naHR0cHM6ZXZlbnRzLzc4NDcucGRmJyB0YXJnZXQ9J19uZXcnPjg4dGggR3VydSBEYWtzaHRhIEZhY3VsdHkgSW5kdWN0aW9uIFByb2dyYW1tZShIUkRDKTsgRGF0ZWQ6IDxiPjUtOC0yMDIyPC9iPjwvYT48bGk+PGEgaHJlZj0naHR0cHM6ZXZlbnRzLzc4NDYucGRmJyB0YXJnZXQ9J19uZXcnPjUtWWVhciBCQS1MTEIgQW5zd2VyIEtleXMtMjAyMjsgRGF0ZWQ6IDxiPjQtOC0yMDIyPC9iPjwvYT48bGk+PGEgaHJlZj0naHR0cHM6ZXZlbnRzLzc4NDUucGRmJyB0YXJnZXQ9J19uZXcnPlNlbGVjdGlvbiBOb3RpZmljYXRpb24gTm8uIDcgDQpGb3INCk1CQS1DTUUgUHJvZ3JhbW1lIFNlc3Npb24tMjAyMjsgRGF0ZWQ6IDxiPjItOC0yMDIyPC9iPjwvYT5kAgMPEA8WBh4NRGF0YVRleHRGaWVsZAUETmFtZR4ORGF0YVZhbHVlRmllbGQFAklEHgtfIURhdGFCb3VuZGdkEBVjEzAtU2VsZWN0IERlcGFydG1lbnQUQWxsYW1hIElxYmFsIExpYnJhcnkGQXJhYmljDEJpb2NoZW1pc3RyeRVCaW9pbmZvcm1hdGljcyBDZW50cmUMQmlvcmVzb3VyY2VzBkJvdGFueSJDZW50ZXIgb2YgUmVzZWFyY2ggZm9yIERldmVsb3BtZW50JENlbnRyZSBmb3IgQmlvZGl2ZXJzaXR5IGFuZCBUYXhvbm9teSpDZW50cmUgZm9yIENhcmVlciBQbGFubmluZyBhbmQgQ291bnNlbGxpbmc2Q2VudHJlIEZvciBJbm5vdmF0aW9uLCBJbmN1YmF0aW9uIEFuZCBFbnRyZXByZW5ldXJzaGlwM0NlbnRyZSBmb3IgSW50ZXJkaXNjaXBsaW5hcnkgUmVzZWFyY2ggJiBJbm5vdmF0aW9ucydDZW50cmUgZm9yIFVuaXZlcnNpdHkgU29jaWV0eSBJbnRlcmZhY2UkQ2VudHJlIGZvciBXb21lbnMgU3R1ZGllcyAmIFJlc2VhcmNoH0NlbnRyZSBvZiBDZW50cmFsIEFzaWFuIFN0dWRpZXMJQ2hlbWlzdHJ5FENoaWVmIFByb2N0b3IgT2ZmaWNlFUNsaW5pY2FsIEJpb2NoZW1pc3RyeQhDb21tZXJjZRFDb21wdXRlciBTY2llbmNlcx9Db3JvbmEtMTkgVW5pdmVyc2l0eSBPZiBLYXNobWlyEkREVSBLYXVzaGFsIEtlbmRyYRVEZWFuIEFjYWRlbWljIEFmZmFpcnMgRGVhbiBDb2xsZWdlIERldmVsb3BtZW50IENvdW5jaWwuRGVhbiBTY2hvb2wgb2YgRWFydGggYW5kIEVudmlyb25tZW50YWwgU2NpZW5jZR5EZXBhcnRtZW50IG9mIEFwcGxpZWQgU2NpZW5jZXMbRGVwYXJ0bWVudCBvZiBCaW90ZWNobm9sb2d5HkRlcGFydG1lbnQgb2YgU3R1ZGVudHMgV2VsZmFyZRJEZXBhcnRtZW50IG9mIFVyZHUiRGlyZWN0b3JhdGUgb2YgQ29udm9jYXRpb24gQ29tcGxleCFEaXJlY3RvcmF0ZSBvZiBEaXN0YW5jZSBFZHVjYXRpb24pRGlyZWN0b3JhdGUgb2YgSW50ZXJuYWwgUXVhbGl0eSBBc3N1cmFuY2UWRGlyZWN0b3JhdGUgb2YgSVQgJiBTUyBEaXJlY3RvcmF0ZSBvZiBMaWZlbG9uZyBMZWFybmluZypEaXJlY3RvcmF0ZSBvZiBQaHlzaWNhbCBFZHVjYXRpb24gJiBTcG9ydHMORWFydGggU2NpZW5jZXMJRWNvbm9taWNzCUVkdWNhdGlvbihFbGVjdHJvbmljcyAmIEluc3RydW1lbnRhdGlvbiBUZWNobm9sb2d5BUVNTVJDB0VuZ2xpc2gnRW50cmVwcmVuZXVyc2hpcCBEZXZlbG9wbWVudCBDZWxsIChFREMpFUVudmlyb25tZW50YWwgU2NpZW5jZRlGb29kIFNjaWVuY2UgJiBUZWNobm9sb2d5H0dlb2dyYXBoeSAmIERpc2FzdGVyIE1hbmFnZW1lbnQOR2VvaW5mb3JtYXRpY3MNSGVhbHRoIENlbnRyZQVIaW5kaQdIaXN0b3J5DEhvbWUgU2NpZW5jZSdJbnN0aXR1dGUgb2YgZW5naW5lZXJpbmcgYW5kIHRlY2hub2xvZ3keSW5zdGl0dXRlIG9mIEZvcmVpZ24gTGFuZ3VhZ2VzHEluc3RpdHV0ZSBvZiBLYXNobWlyIFN0dWRpZXMgSW5zdGl0dXRlIG9mIE11c2ljIGFuZCBGaW5lIEFydHMXSW5zdGl0dXRlIG9mIFRlY2hub2xvZ3kdSW50ZXJuYWwgQ29tcGxhaW50cyBDb21taXR0ZWUnSXFiYWwgSW5zdGl0dXRlIG9mIEN1bHR1cmUgJiBQaGlsb3NvcGh5EEogJiBLIFNFVCBBZ2VuY3kNS2FyZ2lsIENhbXB1cyVLYXNobWlyIFVuaXZlcnNpdHkgQWx1bW5pIEFzc29jaWF0aW9uCEthc2htaXJpDkt1cHdhcmEgQ2FtcHVzA0xhdwpMZWggQ2FtcHVzH0xpYnJhcnkgYW5kIEluZm9ybWF0aW9uIFNjaWVuY2ULTGluZ3Vpc3RpY3MSTWFuYWdlbWVudCBTdHVkaWVzC01hdGhlbWF0aWNzH01lZGlhIEVkdWNhdGlvbiBSZXNlYXJjaCBDZW50cmUOTmFub3RlY2hub2xvZ3krTmF0aW9uYWwgSGltYWxheWFuIENyeW9zcGhlcmljIFJlc2VhcmNoIExhYhdOYXRpb25hbCBTZXJ2aWNlIFNjaGVtZQtOZXdHZW4gSUVEQwxOb3J0aCBDYW1wdXMbT2ZmaWNlIG9mIHRoZSBEZWFuIFJlc2VhcmNoHE9mZmljZSBvZiB0aGUgUHJvdm9zdCAoQm95cykHUGVyc2lhbhdQaGFybWFjZXV0aWNhbCBTY2llbmNlcwdQaHlzaWNzEVBvbGl0aWNhbCBTY2llbmNlGlBvcHVsYXRpb24gUmVzZWFyY2ggQ2VudHJlFVByb3Zvc3QgR2lybHMgSG9zdGVscwpQc3ljaG9sb2d5F1B1YmxpYyBSZWxhdGlvbnMgQ2VudHJlCFNhbnNrcml0GlNjaG9vbCBvZiBCdXNpbmVzcyBTdHVkaWVzJFNjaG9vbCBvZiBVbmFuaSAmIEF5dXJ2ZWRpYyBNZWRpY2luZStTaGFoLWktSGFtYWRhbiBJbnN0aXR1dGUgb2YgSXNsYW1pYyBTdHVkaWVzNFNoYWlraC1VbC1BYWxhbSBDZW50cmUgZm9yIE11bHRpZGlzY2lwbGluYXJ5IFN0dWRpZXMLU29jaWFsIFdvcmsJU29jaW9sb2d5DFNvdXRoIENhbXB1cxVTdGF0ZSBSZXNvdXJjZSBDZW50cmUKU3RhdGlzdGljcyZUb3VyaXNtLCBIb3NwaXRhbGl0eSAmIExlaXN1cmUgU3R1ZGllcyVVR0MtSHVtYW4gUmVzb3VyY2UgRGV2ZWxvcG1lbnQgQ2VudHJlKVVuaXZlcnNpdHkgTGFuZHNjYXBlIERldmVsb3BtZW50IERpdmlzaW9uKVVuaXZlcnNpdHkgU2NpZW5jZSBJbnN0cnVtZW50YXRpb24gQ2VudHJlB1pvb2xvZ3kVYyQwMDAwMDAwMC0wMDAwLTAwMDAtMDAwMC0wMDAwMDAwMDAwMDAkYzVlMzBjN2EtYzhmMS00YjkyLTg2YzYtNmY1YjE5MWQ2ZmQxJGJjNjIzN2M3LWYxNTAtNGUyNi05Y2E4LTE0MjZiZDg2OTVjNiQ2YmIwYTVmMy1iN2M0LTRjMjYtYmUxOS0wOWE2MDg0NWE2NmQkNDVlZjNiMmItMWFhNS00MGIyLTliMGUtNzYwYjRiMDUzYWY4JDRlOTJlZjNhLTBlMTItNDRkYS1iOGZiLWRmZDA1ZTMzMTg4NiRiZGNmY2Y3MC0yOTRhLTRjNDMtOTVlZC03MGNhZjY4NWYzYjIkNDcwMWI4NTMtYTMzMC00Zjk0LWEwMGUtMDE1NTVhMzJhMGZmJGViOWNjZDI5LTJhMTItNGFkZC1iNjViLWE3MjgyMTUzM2M0NyRiZGVkNGYxZi1hODM5LTQwNTktOWMxNC1mYjc3MGZkMWU2NzgkN2NjZjJiM2YtOWMxMC00NmY4LTkzNGYtZGM1ZDMwN2U0MTJjJDAwZDAzZmZiLWY3NmQtNGI4Zi04YWFlLWU4NDliYzQxOWY3NiQ0YzA4YjZjNS02MTRlLTRhNDUtYjhhYi1jYzY5OGYwNDA2MjckZTk0ZDM1YTMtMmRjYi00YjA4LTg1NzUtMDI1MDljZDY2YzU4JDkzMjY5YjZjLTdmNTMtNDQzOS1hZTlhLTNiZGY1NWE0YzY0OSQ1YWY0YzEyMC01MDBmLTQ4ZDQtOTJjMi05ZTAxNDRlMWNkM2MkZjNlMjkwOTItZWY5Mi00OWZkLTg2OGItYTY3NzljMDk0ZTUzJDZiZDU5MDhhLWE0N2YtNDUxNi1hNTIyLTU2ZTMwN2U0MjY4NSQ4MGI1ZjlmMy1lYmIxLTQ4YjEtODhkYi1hZDllOTlhNjliYWEkNzk3NTVmMDctOTU1MC00YWViLWJkNmYtNWQ4MDJkNTZiNDZkJGFiOTZiNzcwLTBhNmUtNDI2NS1iODIwLTFiOGU2ZThkNGE2MSQ1YjNlMmMzZC1jNGU1LTRlMTYtYjk1Mi1iNGRjNDljODUyODkkMzU4ZDJmNDMtOWQyYi00ZDQ1LWFhMDMtNjE4YjdkNThmOGU3JDYxZWE3NjQ1LTU1MmItNGZhNi04NTJiLTc3ZWQ1ODU0Mzg3NCQ0ZjFjYmRhYi1jNDI5LTRiOTctODY4ZS1jNmU1YjI1YzFmNDMkYTQ1MWY5MzgtZjY2Ny00Zjk2LTg4YmUtNTI1Y2Y1ZDczY2U1JDQ1Mzk0ZGJjLTgwYzctNGFlNC1iOTk5LTljZWQ4MzUwZjJmOCQzM2NlOTU1NC03MGM4LTRkZjQtYTc0Yi1lY2ZkYTg1YWQyZGIkMTcyMzM4YzMtNjdmMy00MDI2LThjYTAtNjc1ZWE1YjMzMmQwJDNhMmZlYTlmLTNiOWItNDFlOS04MjIyLTM3ZDdmZjUyODdjNSQyY2ZhNDU4NC01YWZlLTQzY2UtYWE0Yi1hZDkzNmNjOWQzYmUkYmQ2NGU4ZWYtYzlhMC00M2U0LTk3Y2MtNzQ0NGI1ZWU4OTdhJDdhMzEwM2U1LWI1ZmMtNGEyNi1hYWUzLWYwYjUwNDllN2ZhYSQyMGFlNDU0Yy0wY2I0LTRlMDQtOGFmZS05OGIxOTIxY2M4ZWYkZTllZmIxMzEtZmU4ZS00M2FiLTg2Y2YtNThlZTg0OTQxOGY3JDc1MjZmNTg5LThiYjItNDcxYS1hMzc5LTM2MzY2MTJhMDgyMSRhNTg4M2MyOC1kYTkyLTRkNTgtYjk2Yy05ZDE0N2U2NDg1YzUkNGY5NmRkZTktOWEzNS00NmM3LTliM2UtYzgwMjkxZWQ1Njg5JDlkZDNiNWZmLTUyOGQtNDhkNC04ZjUyLTk3NDRjYWFlN2I2NSQ2ZjExM2M1OC00ZjlhLTQ5YWQtODUzMS1lNWY1M2MxZGQ5Y2IkOWIzYmQzZTMtZTVmYi00MTc0LTk5MDMtMjk4Y2U2MjJlNGNlJDlmN2Y0MTk5LTEyYjUtNDlkMS04ZTQxLTI2MGIzNWQ5NjUwYyRhYjFhYzFmMS0wN2UzLTQyYTItODViYy04MzcxN2VmMzkxNTUkYTgzZDg3MWUtYzY3Ni00MjQ2LWFlNzItZWZiNzk4ZmQ3Y2Q1JDA4MGRiZjhhLTA2ZjAtNDc0Ny05YTc0LWQwOGNhNzY5ZWU5NyRjZTQ0NGNkYi02MWU3LTRiMzktOTIwMC1jM2I5MmM4M2JiMDckYzdlMjk5OTctNzE4Zi00ODA5LWI2ZTgtYTgxZmZmMzJkNTg4JDg4NzYyNTgwLWYxMDYtNGNlMS05OTUzLWNmNWRiNGZjMThmMCQ2NTY3ZGJmNS03OWZlLTRkZmMtOTFmNy1kN2FmYmU1MDY0NDYkYmFkNzAxODktNzIyNi00MDdlLTkwYmYtMWFlMTE3OGVkYTc2JGJhOWQzYWM4LThhMDgtNDkwZS1iYWVhLThjZTQwYmJlY2NmZCQ2NjQ4ZWJjNy00OWVlLTQyNTUtODVkMS0wYTlmZmEzM2QyYTMkM2E5NjM3MzgtNWQ2Ny00NDQ0LWFlYmEtZWRkYTc3MjgzYzE1JDExNTk4MGU5LTliYWItNGM2YS04MzRjLWRlOWM1Y2MxNzNmOCQ1ZjczMDA2NC0yMGU0LTRhNWEtYjYxNC01N2Q3OGE4ZWRmZDgkMzNhNWUyNmYtN2QwOS00ZmNhLTk4YmMtNTZjNWM5NGQ1ZTZjJGZjNmQ5MWZkLTk5MjctNDAyMi05ZjBkLTFkMzgyNjk2NDUwNSRkZjQzNzgzZS01NDAyLTQ1MjQtOTIwMS1jNWRmMDU0MWQxZjEkMTNjM2UwOWItMzI1ZC00YzJmLTk0OGMtNmZkMjY5NjMwMjc2JDM3Y2Q4ZDczLTE3NTUtNDFmYS04YWFkLTgzZmE5YWMxODAzZCRlZTczNTRiOC01NzIxLTQ3MjktYWRiZS0yYjM5MmUwMWI1NWUkYmNhY2IzZGQtZGFiYy00NGZhLWIzNjctMGI2YjVmNTBmYTUzJDVjZTZjNzY1LWMwMTMtNDQ2Yy1iNmFjLWI5ZGU0OTZmODc1MSQ1ZjhmNjYzNC0wZDgzLTRlYzctOGQxNi1hNTEzYTk4MmMyOGYkOWViZmIyZjItNTAwMy00N2E0LTlkZmUtZDNjZGNjNmEyMDIwJGY2ZWMzNzQwLTQyMmQtNGFjMS05ZjUyLWRkZmUyY2ZmY2IyOCQ5MTQyMjFlYy1jNTRhLTRhNDAtYTA1Mi1iMTJkMjU0YWY2MGIkNWNiNzliNGUtZWU0NC00NDQ4LTlkZmUtY2E4NzZjMzFhMjRlJDcxYmNlYzc2LTU1ZDAtNGRkNy04YWE0LWRmYWI2ZjFiZDRjZSQyYjg2NDAwNS0yMDRmLTQxNjctOTBkOC00MDhlYjhkZGFjOWIkMTc2MmE3MjgtM2YxMi00NjBhLWIwMGMtMTQ3NmZjYWRkNmM4JDZlZmI1YzI3LWE0MjctNDUwZC1hZjkzLWFmMjQwZDQ2OTdkNSRhMjViM2RlYy04ZGI0LTRjNDQtODMwYS1jNTRlNmEzOGRkNzMkYTg1Yjk3ZjgtNzRmMS00MWYwLWE3NDYtMTEwNmU0MzdmNDY2JDgwYzNiNDg3LTU5YWYtNDc0NS1iYmNmLTFjMTUyODFkNzRlMyRlYWUzZDRjOS1kNTQxLTRiODQtOTNkZS1mNzY4MWQ4YzIzNTMkYjU0YzMxZDEtYjQyMy00ODFlLTg0ODAtYjE2YTY0NjY1Mjk2JDRmZDY4NDdlLTVmMWUtNGE1Ni1iNjNmLTZkMGVkYjBmMzI2YyQxODAyZjEyYy1lZjZkLTRkNTAtODkwZS1iYjlmN2Y2NzhhMjMkNjMyOTNjM2ItZjRmZi00YzM1LWEzODctNzIzNmM0NmVjMGZhJGZiN2Q3OTU4LTcwMTUtNDU0ZS04ZTgxLTBkNTM2YWI0NGJhZCQ1YzhiMmI2Ny0wYjg2LTRmNGEtYjg2Ny1lMTM5ZjIzZTIzMzkkYzJkZDc0NmItYmUyYy00MjEyLWIwM2UtMjA0MDQ3MWJhMWU2JDNjZWU2NDRmLTk2M2QtNDAzZS1hZmI0LTA0YmYyZjBhNDMwNSRkNGE1N2I5NC0xYTI4LTQ3YTItOTVjZC01NDE1ZTVlNDE1MWQkNmQ4YmUwNTUtZmMwNy00MTEwLThiOGEtNDg0NzdlOWI5NjBhJGQyYWNiNDg5LWJkNzktNDY0MC1hMGIzLWVmMDYxZDlkODQ4YSQzNjg5MjQwOC0xZmVkLTQ0MzEtOTg0OC0wNzYxYjllMDI1ODckNDNmN2Q5ODEtOTYyNi00ZjI5LTllYWYtMWNjN2E0NjNhOWMxJGY0NWJjZGFiLTVhNDEtNGI5Yi04YzE4LTlkZjFmMTYzZjQ4MCRjMmQzYjI3OC00Y2Y3LTQ5YTUtOTUyNS1hZjVlMzUyZjI5MDAkOTdmMDRkZTUtZWUxZi00N2Q2LThjMmUtN2VlMzY5MDlmNTRmJDdmOWFhMDhjLWMzZDktNDc0Yy04MDY3LWUwZWU5Yzk1YTgzNCQzZGY2ZGU0Ni1lMDE1LTQ5ZWYtOGNlNS1iNTVkNjI0MDU0NDYkOWMwY2NiNWMtZjg0Yi00ZjAwLTk0MTAtMDQ2NDgxMDAzYThlJGMyY2UyNTY0LTY5MWUtNGM5YS1hZThhLTQ0ZjhlMzI0NGM2MCRhYjlhNmFlNS0yNDg3LTQ2MGQtYTIzOC0yMjc3MmVhOGZmY2MkNjZlYzE5MDgtNWZlMC00Y2JlLTg2Y2YtY2Q3Y2ZjZWQwNTM0JGNhZTJkMDhmLTRmNjItNDI4ZS1iNmVhLWNmNDZjZGNjYmY0MhQrA2NnZ2dnZ2dnZ2dnZ2dnZ2dnZ2dnZ2dnZ2dnZ2dnZ2dnZ2dnZ2dnZ2dnZ2dnZ2dnZ2dnZ2dnZ2dnZ2dnZ2dnZ2dnZ2dnZ2dnZ2dnZ2dnZ2dnZ2dnZ2dnZ2dnZ2dnZ2dnZ2dnZ2dkZAIHDxYCHwAFsA0NCiAgICAgICAgICAgICANCiAgICAgICAgICAgIDxsaSA+PGEgaHJlZj0naHR0cHM6Ly9lZ292LnVvay5lZHUuaW4vY291cnNlaW5mbyN1Z2Zvcm1zL3ByZWxvZ2luL2RlZmF1bHRfbmV3LmFzcHg/aWQ9NicgdGFyZ2V0PSdfbmV3JyA+IFVHLUJhY2tsb2cgRXhhbWluYXRpb24gRm9ybXMgZm9yIDR0aCBzZW1lc3RlciBiYXRjaGVzICgyMDE2LTIwMTkpPC9hPjxsaSA+PGEgaHJlZj0naHR0cHM6Ly9lZ292LnVvay5lZHUuaW4vY291cnNlaW5mbyN1Z2Zvcm1zL1BheW1lbnRJc3N1ZXMuYXNweCcgdGFyZ2V0PSdfbmV3JyA+IENoZWNrIEZlZSBTdGF0dXMtVUcgKEJhY2tsb2cpICYgQi5FZCAoUmVndWxhci9CYWNrbG9nKSBFeGFtIEZvcm1zPC9hPjxsaSA+PGEgaHJlZj0naHR0cHM6Ly9lZ292LnVvay5lZHUuaW4vZXhhbXMvdWdmb3Jtcy9wcmVsb2dpbi9kZWZhdWx0LmFzcHg/aWQ9MjAnIHRhcmdldD0nX25ldycgPiBBZG1pdCBDYXJkcyBmb3IgIEIuRWQgMXN0ICYgMm5kIFNlbWVzdGVyL3MgRERFKERpc3RhbmNlKSAmIERlcHQuIG9mIEVkdS4oUmVndWxhcikgQmF0Y2ggKDIwMjAtMjIpPC9hPjxsaSA+PGEgaHJlZj0naHR0cHM6Ly9lZ292LnVvay5lZHUuaW4vY291cnNlaW5mbyN1Z2Zvcm1zL3ByZWxvZ2luL2RlZmF1bHRfbmV3LmFzcHg/aWQ9MScgdGFyZ2V0PSdfbmV3JyA+IEFkbWl0IGNhcmRzIGZvciBVZy01dGggU0VNIFJlZy9QdnQgKDIwMTkpIEFuZCBCYWNrbG9nICgyMDE2LTIwMTgpPC9hPjxsaSA+PGEgaHJlZj0naHR0cHM6Ly9lZ292LnVvay5lZHUuaW4vY291cnNlaW5mbyN1Z2Zvcm1zL3ByZWxvZ2luL2RlZmF1bHRfbmV3LmFzcHg/aWQ9NCcgdGFyZ2V0PSdfbmV3JyA+IEFkbWl0IGNhcmRzIGZvciAgMm5kIFNlbWVzdGVyIFJlZy4mIFB2dCgyMDIxKSBBbmQgQmFja2xvZyAoMjAxNi0yMCk8L2E+PGxpID48YSBocmVmPSdodHRwczovL2Vnb3YudW9rLmVkdS5pbi9jb3Vyc2VpbmZvI3VnZm9ybXMvcHJlbG9naW4vZGVmYXVsdF9uZXcuYXNweD9pZD0xMDInIHRhcmdldD0nX25ldycgPiBBZG1pdCBDYXJkcyBGb3IgSU1USCA1VEggKDIwMTkpLzNyZCgyMDIwKSYybmQoMjAyMSkgJiBCQUNLTE9HICgyMDE3LTIwMjApIFNFTUVTVEVSPC9hPjxsaSA+PGEgaHJlZj0naHR0cHM6Ly9lZ292LnVvay5lZHUuaW4vY291cnNlaW5mbyN1Z2Zvcm1zL3ByZWxvZ2luL2RlZmF1bHQuYXNweD9pZD00JyB0YXJnZXQ9J19uZXcnID4gQWRtaXQgY2FyZHMgZm9yIDFzdCAmIDJuZCBTZW1lc3RlciBNb2x2aSBSZWcuKDIwMjEpLUJhdGNoPC9hPjxsaSA+PGEgaHJlZj0naHR0cHM6Ly9lZ292LnVvay5lZHUuaW4vY291cnNlaW5mbyN1Z2Zvcm1zL3ByZWxvZ2luL2RlZmF1bHQuYXNweD9pZD0xMScgdGFyZ2V0PSdfbmV3JyA+IEJhY2tsb2cgMXN0IEFuZCAybmQgWWVhciBCc2MgTUxUICgyMDE2LTIwMTkpPC9hPjxsaSA+PGEgaHJlZj0naHR0cHM6Ly9lZ292LnVvay5lZHUuaW4vY291cnNlaW5mbyN1Z2Zvcm1zL3ByZWxvZ2luL2RlZmF1bHRfbmV3LmFzcHg/aWQ9MzEnIHRhcmdldD0nX25ldycgPiBFeGFtIEZvcm1zIGZvciBCLkVkIDFzdCBTZW1lc3RlciBDUkMgQmF0Y2ggKDIwMjEpPC9hPjxsaSA+PGEgaHJlZj0naHR0cHM6Ly9lZ292LnVvay5lZHUuaW4vZUNvbmR1Y3QvJyB0YXJnZXQ9J19uZXcnID4gRXhhbWluYXRpb24gZm9ybXMgJiBBZG1pdCBDYXJkcyBmb3IgUEcsIEJUZWNoLEJFICYgRGlwbG9tYSBDb3Vyc2VzPC9hPmQCCQ8WAh8ABZgWDQogICAgICAgICAgICAgIA0KICAgICAgICAgICAgPGxpID48YSBocmVmPSdodHRwczovL2Vnb3YudW9rLmVkdS5pbi9pbWJhL1ByZWxvZ2luL1BheW1lbnRBcHBsaWNhdGlvbkZvcm0uYXNweCcgdGFyZ2V0PSdfbmV3JyA+IEFwcGxpY2F0aW9uIEZvcm0gZm9yIDUtWWVhciBJTUJBIFByb2dyYW1tZXMgKFVuZGVyIFNlbGYgRmluYW5jZSkgU2Vzc2lvbi0yMDIyPC9hPjxsaSA+PGEgaHJlZj0naHR0cHM6Ly9lZ292LnVvay5lZHUuaW4vQnRlY2gvUG9zdExvZ2luL0RlZmF1bHQuYXNweCcgdGFyZ2V0PSdfbmV3JyA+IEFwcGxpY2F0aW9uIEZvcm0gZm9yIEIuVGVjaCBQcm9ncmFtbWVzIFNlc3Npb24gMjAyMjwvYT48bGkgPjxhIGhyZWY9J2h0dHBzOi8vZWdvdi51b2suZWR1LmluL21iYS9QcmVsb2dpbi9QYXltZW50QXBwbGljYXRpb25Gb3JtLmFzcHgnIHRhcmdldD0nX25ldycgPiBBcHBsaWNhdGlvbiBGb3JtIGZvciBNQkEgUHJvZ3JhbW1lIChVbmRlciBTZWxmIEZpbmFuY2UpIFNlc3Npb24tMjAyMjwvYT48bGkgPjxhIGhyZWY9J2h0dHBzOi8vZWdvdi51b2suZWR1LmluL21iYS9QcmVsb2dpbi9QYXltZW50QXBwbGljYXRpb25Gb3JtbWJhZm0uYXNweCcgdGFyZ2V0PSdfbmV3JyA+IEFwcGxpY2F0aW9uIEZvcm0gZm9yIE1CQS1GTSBQcm9ncmFtbWUgKFVuZGVyIFNlbGYgRmluYW5jZSkgU2Vzc2lvbi0yMDIyPC9hPjxsaSA+PGEgaHJlZj0naHR0cHM6Ly9lZ292LnVvay5lZHUuaW4vZXNlcnZpY2VzL3BnYWRtaXNzaW9uL3ByZWxvZ2luL0FkbWlzc2lvbmZvcm0uYXNweCcgdGFyZ2V0PSdfbmV3JyA+IEFkbWlzc2lvbiBGb3JtIEZvciBQRyBQcm9ncmFtbWVzICwgTExNLCBNLlBoYXJtYSwgTS5UZWNoLCBCLlRlY2ggTGF0ZXJhbCBFbnRyeSxNLkVkLEIuRWQgLE1CQS9NQkFGTS9NQkFDTUUsIEJBTExCL0xMQiwgQi5UZWNoLCBCLlZvYywgSU1CQSwgTXVzaWMgRmluZSBBcnQsIFBHIERpcGxvbWEsRGlwbG9tYSwgQ2VydGlmaWNhdGUgQ291cnNlcyAxc3QgU2VtZXN0ZXIgKFNlc3Npb24gMjAyMik8L2E+PGxpID48YSBocmVmPSdodHRwczovL2Vnb3YudW9rLmVkdS5pbi9lQWRtaXNzaW9uc1Byb2YvUHJlbG9naW4vTXlLVUFkbWl0Q2FyZC5hc3B4JyB0YXJnZXQ9J19uZXcnID4gQWRtaXQgQ2FyZHMgZm9yIEJBLkxMQiBFbnRyYW5jZSBUZXN0IFNlc3Npb24tMjAyMjwvYT48bGkgPjxhIGhyZWY9J2h0dHBzOi8vZWdvdi51b2suZWR1LmluL2VBZG1pc3Npb25zRERFL1ByZWxvZ2luL0VudHJhbmNlSG9tZS5hc3B4JyB0YXJnZXQ9J19uZXcnID4gQXBwbGljYXRpb24gRm9ybSBmb3IgQi5FZCBQcm9ncmFtbWUgKERpc3RhbmNlIEVkdWNhdGlvbilTZXNzaW9uIDIwMjI8L2E+PGxpID48YSBocmVmPSdodHRwczovL2Vnb3YudW9rLmVkdS5pbi9lQWRtaXNzaW9ucy9QcmVsb2dpbi9yZXN1bHRzdGF0dXMuYXNweCcgdGFyZ2V0PSdfbmV3JyA+IEVudHJhbmNlIFRlc3QgU2NvcmUgLSBTZXNzaW9uIDIwMjI8L2E+PGxpID48YSBocmVmPSdodHRwczovL2Vnb3YudW9rLmVkdS5pbi9lYWRtaXNzaW9ucy9QcmVsb2dpbi9lbnRyYW5jZWhvbWUuYXNweCcgdGFyZ2V0PSdfbmV3JyA+IEFwcGxpY2F0aW9uIGZvcm0gZm9yIE1BIEhpbmRpIFNlc3Npb24gMjAyMjwvYT48bGkgPjxhIGhyZWY9J2h0dHA6Ly9lZ292LnVvay5lZHUuaW4vZXNlcnZpY2VzL3BoZGFkbWlzc2lvbi9wcmVsb2dpbi9hZG1pc3Npb25mb3JtLmFzcHgnIHRhcmdldD0nX25ldycgPiBSZWdpc3RyYXRpb24gRm9ybSBmb3IgSW50ZWdyYXRlZCBNLlBoaWwvUGguRCAtU2Vzc2lvbiAyMDIyPC9hPjxsaSA+PGEgIGhyZWY9J0FkbWlzc2lvbnMvNDc0LnBkZicgdGFyZ2V0PSdfbmV3Jz5BcHBsaWNhdGlvbiBGb3JtIGZvciBBZG1pc3Npb24gdG8gUmVndWxhciBGdWxsLXRpbWUNClByb2dyYW1tZXMgb2YgU3R1ZHkgZm9yIEZvcmVpZ24gTmF0aW9uYWxzPC9hID4gPGxpID48YSBocmVmPSdodHRwczovL2Vnb3YudW9rLmVkdS5pbi9lYWRtaXNzaW9ucy9QcmVsb2dpbi9QYXltZW50QXBwbGljYXRpb25Gb3JtLmFzcHgnIHRhcmdldD0nX25ldycgPiBBcHBsaWNhdGlvbiBGb3JtIGZvciBQRyBQcm9ncmFtbWVzIChVbmRlciBTZWxmIEZpbmFuY2UpIFNlc3Npb24tMjAyMjwvYT48bGkgPjxhIGhyZWY9J2h0dHBzOi8vZWdvdi51b2suZWR1LmluL2VzZXJ2aWNlcy9wZ2FkbWlzc2lvbi9wcmVsb2dpbi8zUkRTZW12aWV3YmF0Y2hzMjAxNy5hc3B4JyB0YXJnZXQ9J19uZXcnID4gQWRtaXNzaW9uIEZvcm0gZm9yIFBHIENvdXJzZXMsIE0uVGVjaChDUyk0dGgsM3JkICYgMm5kIFNlbSAoQmF0Y2ggMjAxOC8yMDE5LzIwMjEsIEIuRWQsIEludGVncmF0ZWQgQ291cnNlcyAzcmQgU2VtZXN0ZXIsIE1DQSAzcmQsNXRoIFNlbSAoQmF0Y2ggMjAxNy8xOC8xOSkgMm5kIFllYXIgQi5TYyAgTnVyc2luZyAvTS5QaGFybS8gQi5QaGFybWEgMm5kIFllYXIgJiAzdGggWWVhcixMTE0sIE1DQSwgSG9tZSBTY2llbmNlIDNyZCBTZW0gKEJhdGNoIDIwMTgpLCBJTUJBIDNyZCBTZW1lc3RlciwgNXRoIFNlbWVzdGVyLCA3dGggU2VtZXN0ZXIsIDl0aCBTZW1lc3RlciwgTXVzaWMgRmluZSBBcnRzIEJhdGNoICgyMDE4LzIwMTkvMjAyMCk8L2E+PGxpID48YSBocmVmPSdyZXNlYXJjaHN5bGxhYmkuYXNweCcgdGFyZ2V0PSdfbmV3JyA+IFBoRC9NcGhpbCBFbnRyYW5jZSBUZXN0IFN5bGxhYnVzPC9hPjxsaSA+PGEgaHJlZj0naHR0cDovL2Vnb3YudW9rLmVkdS5pbi9lc2VydmljZXMvcGdhZG1pc3Npb24vcHJlbG9naW4vM1JEU2Vtdmlld2JhdGNoczIwMTguYXNweCcgdGFyZ2V0PSdfbmV3JyA+IEZlZSBzbGlwIG9mIDNyZCBTZW0gQmF0Y2ggMjAxOCAoU2Vjb25kIEluc3RhbGxtZW50KTwvYT5kAgsPFgIfAAWWHg0KICAgICAgICAgICAgICANCiAgICAgICAgICAgIDxsaSA+PGEgaHJlZj0naHR0cHM6Ly9lZ292LnVvay5lZHUuaW4vY29sbGVnZWFkbS9BZG1EZXRhaWxzL2luc3RydWN0aW9uU1BBR0UuQVNQWCcgdGFyZ2V0PSdfbmV3JyA+IFJlZ2lzdHJhdGlvbiBGb3JtIGZvciBDb2xsZWdlIFVHIEFkbWlzc2lvbnMtMjAyMiAoUmVndWxhciBNb2RlKSAgKHVuZGVyIE5hdGlvbmFsIEVkdWNhdGlvbiBQb2xpY3ktTkVQPC9hPjxsaSA+PGEgaHJlZj0naHR0cHM6Ly9lZ292LnVvay5lZHUuaW4vY29sbGVnZWFkbS9BZG1EZXRhaWxzL1N0dWRlbnRTdGF0dXMuYXNweD91aW8xbz0xMTk5ODgnIHRhcmdldD0nX25ldycgPiBNeSBGb3JtIFN0YXR1cyxTdWJqZWN0IENvbmZpcm1hdGlvbiBhbmQgRkVFIFBheW1lbnQgZm9yIFVHIDFzdC8ybmQgU2VtLiBiYXRjaCAyMDIyICAoVW5kZXIgTmF0aW9uYWwgRWR1Y2F0aW9uIFBvbGljeS1ORVApPC9hPjxsaSA+PGEgaHJlZj0naHR0cHM6Ly9lZ292LnVvay5lZHUuaW4vQ29sbGVnZUFkbS9BZG1EZXRhaWxzL1N0dWRlbnRTdGF0dXNfUHJvbW90aW9uYWwuYXNweD9yY29kZXJ0PTIwMjExNCZyc2VtaWQ9MyZhcHBpZD05MDhpaW91MTIzNG1uJnNlcnZpY2VpZD0xeHgyMzRAQEAnIHRhcmdldD0nX25ldycgPiBGRUUgUGF5bWVudCBmb3IgQi5FRCAzcmQgJiA0dGggKFByaXZhdGUgQ29sbGVnZXMpLCBCYXRjaCAyMDE5LTIxPC9hPjxsaSA+PGEgaHJlZj0naHR0cHM6Ly9lZ292LnVvay5lZHUuaW4vQ29sbGVnZUFkbS9BZG1EZXRhaWxzL1N0dWRlbnRTdGF0dXNfUHJvbW90aW9uYWwuYXNweD9yY29kZXJ0PTIwMjExJnJzZW1pZD0zJmFwcGlkPTkwOGlpb3UxMjM0bW4mc2VydmljZWlkPTF4eDIzNDQwNDA0MCcgdGFyZ2V0PSdfbmV3JyA+IE15IEZvcm0gU3RhdHVzLFN1YmplY3QgQ29uZmlybWF0aW9uIGFuZCBGRUUgUGF5bWVudCBmb3IgVUcgM3JkLzR0aCBTZW0uIGJhdGNoIDIwMjE8L2E+PGxpID48YSBocmVmPSdodHRwczovL2Vnb3YudW9rLmVkdS5pbi9Db2xsZWdlQWRtL2FkbWRldGFpbHMvSG9tZUJhc2ljUmVnRm9ybVByb21vdGlvbmFsX1JSSURfQkVELmFzcHgnIHRhcmdldD0nX25ldycgPiBBZG1pc3Npb24gQ3VtIEV4YW1pbmF0aW9uIEZvcm1zIEZvciAzcmQgJiA0dGggU2VtZXN0ZXIgQi5FRCAoUHJpdmF0ZSBDb2xsZWdlcyksIEJhdGNoIDIwMTktMjE8L2E+PGxpID48YSBocmVmPSdodHRwczovL2Vnb3YudW9rLmVkdS5pbi9Db2xsZWdlQWRtL0FkbURldGFpbHMvU3R1ZGVudFN0YXR1c19Qcm9tb3Rpb25hbC5hc3B4P3Jjb2RlcnQ9MjAxOTEmcnNlbWlkPTUmYXBwaWQ9OTA4aWlvdTEyMzRtbiZzZXJ2aWNlaWQ9MXh4MjM0NDA0MDQwJyB0YXJnZXQ9J19uZXcnID4gTXkgRm9ybSBTdGF0dXMgYW5kIEZFRSBQYXltZW50IGZvciBVRyA1dGgvNnRoU2VtLiAgYmF0Y2ggMjAxOTwvYT48bGkgPjxhIGhyZWY9J2h0dHBzOi8vZWdvdi51b2suZWR1LmluL0NvbGxlZ2VBZG0vQWRtRGV0YWlscy9Ib21lQmFzaWNSZWdGb3JtUHJvbW90aW9uYWxfcnJpZC5hc3B4JyB0YXJnZXQ9J19uZXcnID4gQWRtaXNzaW9uIEZvcm1zIGZvciBVRyAzcmQvNHRoICBzZW0gQmF0Y2ggMjAyMSAtUmVndWxhciAoTm90IEVucm9sbGVkIGluIENvbGxlZ2VzKTwvYT48bGkgPjxhIGhyZWY9J2h0dHBzOi8vZWdvdi51b2suZWR1LmluL0NvbGxlZ2VBZG0vQWRtRGV0YWlscy9TdHVkZW50U3RhdHVzX1Byb21vdGlvbmFsLmFzcHg/cmNvZGVydD0yMDIwMTImcnNlbWlkPTMmYXBwaWQ9OTA4aWlvdTEyMzRtbiZzZXJ2aWNlaWQ9MXh4MjM0NDA0MDQwJyB0YXJnZXQ9J19uZXcnID4gTXkgRm9ybSBTdGF0dXMgYW5kIEZFRSBQYXltZW50IGZvciBCQVJDSCAzcmQvNHRoIFNlbS4gYmF0Y2ggMjAyMDwvYT48bGkgPjxhICBocmVmPSdSZWdpc3RyYXRpb24vNjEucGRmJyB0YXJnZXQ9J19uZXcnPuKAnEludGVyIENvbGxlZ2UgTWlncmF0aW9uIER1cmluZyB0aGUgQ291cnNlIE9yZGVyIE5vLjEgb2YgMjAxODwvYSA+IDxsaSA+PGEgIGhyZWY9J1JlZ2lzdHJhdGlvbi81MC5wZGYnIHRhcmdldD0nX25ldyc+SW50ZXIgQ29sbGVnZSBNaWdyYXRpb24gT3JkZXIgTm8uMSAoMjAxOCk8L2EgPiA8bGkgPjxhICBocmVmPSdSZWdpc3RyYXRpb24vNDIucGRmJyB0YXJnZXQ9J19uZXcnPkxpc3Qgb2YgUmVnaXN0cmF0aW9uIE5vLiBhbGxvdHRlZCB0byAgUHJpdmF0ZSBDYW5kaWRhdGVzIG9mIGJhdGNoIDIwMjEgKENCQ1MgU2NoZW1lKTwvYSA+IDxsaSA+PGEgaHJlZj0naHR0cHM6Ly9lZ292LnVvay5lZHUuaW4vY291cnNlaW5mby9taWdyYXRpb24vcHJlbG9naW4vaW5zdHJ1Y3Rpb25zLmFzcHgnIHRhcmdldD0nX25ldycgPiBBcHBsaWNhdGlvbiBmb3JtIGZvciBJbnRlci1Vbml2ZXJzaXR5IE1pZ3JhdGlvbjwvYT48bGkgPjxhIGhyZWY9J2h0dHBzOi8vZWdvdi51b2suZWR1LmluL2NvdXJzZWluZm8vbWlncmF0aW9uL3ByZWxvZ2luL1ByaW50Rm9ybS5hc3B4JyB0YXJnZXQ9J19uZXcnID4gU3RhdHVzIG9mIEludGVyLVVuaXZlcnNpdHkgTWlncmF0aW9uIENlcnRpZmljYXRlPC9hPjxsaSA+PGEgaHJlZj0naHR0cHM6Ly9lZ292LnVvay5lZHUuaW4vY291cnNlaW5mby9wZ3N0YXR1cy9kZWZhdWx0LmFzcHgnIHRhcmdldD0nX25ldycgPiBSZWdpc3RyYXRpb24gU3RhdHVzIEZvciBQRyBTdHVkZW50czwvYT48bGkgPjxhICBocmVmPSdSZWdpc3RyYXRpb24vNzAucGRmJyB0YXJnZXQ9J19uZXcnPkludGVyIENvbGxlZ2UgTWlncmF0aW9uICBPcmRlciBOby4wMSBvZiAyMDIwPC9hID4gPGxpID48YSAgaHJlZj0nUmVnaXN0cmF0aW9uLzMxLnBkZicgdGFyZ2V0PSdfbmV3Jz5PbmUgc3ViamVjdCBjaGFuZ2Ugb3JkZXIgTm8uIDI8L2EgPiA8bGkgPjxhICBocmVmPSdSZWdpc3RyYXRpb24vMzIucGRmJyB0YXJnZXQ9J19uZXcnPk9uZSBzdWJqZWN0IGNoYW5nZSBPcmRlciBOby4zPC9hID4gPGxpID48YSAgaHJlZj0nUmVnaXN0cmF0aW9uLzI2LnBkZicgdGFyZ2V0PSdfbmV3Jz5PbmUgc3ViamVjdCBjaGFuZ2UgT3JkZXIgTm8uMTwvYSA+IDxsaSA+PGEgaHJlZj0naHR0cHM6Ly9lZ292LnVvay5lZHUuaW4vY291cnNlaW5mby9zdHJlYW1jaGFuZ2UvcHJlbG9naW4vc3RyZWFtY2hhbmdlc3RhdHVzLmFzcHgnIHRhcmdldD0nX25ldycgPiBTdHJlYW0gQ2hhbmdlIFN0YXR1czwvYT48bGkgPjxhICBocmVmPSdSZWdpc3RyYXRpb24vNDAucGRmJyB0YXJnZXQ9J19uZXcnPk9uZSBzdWJqZWN0IGNoYW5nZSBvcmRlciBuby4gMzwvYSA+IDxsaSA+PGEgIGhyZWY9J1JlZ2lzdHJhdGlvbi81OC5wZGYnIHRhcmdldD0nX25ldyc+T25lIFN1YmplY3QgQ2hhbmdlIGZvciBCYXRjaCAyMDE3PC9hID4gPGxpID48YSAgaHJlZj0nUmVnaXN0cmF0aW9uLzY2LnBkZicgdGFyZ2V0PSdfbmV3Jz5PbmUgU3ViamVjdCBDaGFuZ2UgT3JkZXIgKDI0LTAxLTIwMTkpPC9hID4gPGxpID48YSAgaHJlZj0nUmVnaXN0cmF0aW9uLzU0LnBkZicgdGFyZ2V0PSdfbmV3Jz5PbmUgU3ViamVjdCBPcmRlciBOby4wMSBvZiAyMDE4PC9hID4gPGxpID48YSAgaHJlZj0nUmVnaXN0cmF0aW9uLzYzLnBkZicgdGFyZ2V0PSdfbmV3Jz5PbmUgU3ViamVjdCBPcmRlciAoMjAxOCBOb3YpPC9hID4gPGxpID48YSAgaHJlZj0nUmVnaXN0cmF0aW9uLzYyLnBkZicgdGFyZ2V0PSdfbmV3Jz5PbmUgU3ViamVjdCBPcmRlciAoMjAxOCBOZXcpPC9hID4gPGxpID48YSAgaHJlZj0nUmVnaXN0cmF0aW9uLzUzLnBkZicgdGFyZ2V0PSdfbmV3Jz5JbnRlciBDb2xsZWdlIE1pZ3JhdGlvbiBPcmRlciBOby4yICgyMDE4KTwvYSA+IDxsaSA+PGEgaHJlZj0naHR0cHM6Ly9lZ292LnVvay5lZHUuaW4vY291cnNlaW5mbycgdGFyZ2V0PSdfbmV3JyA+IFN0dWRlbnQgQWNhZGVtaWMgRGV0YWlsczwvYT5kAg8PFgIfAAWeDQ0KICAgICAgICAgIA0KICAgICAgICAgIA0KICAgICAgICAgDQogICAgICAgICAgPGxpIGNsYXNzPSdjbGVhcicgdGl0bGU9J05hdGlvbmFsIENvbmZlcmVuY2Ugb24NClJlcHJvZHVjdGl2ZSBIZWFsdGggYW5kIERpc2Vhc2UgJiBDYXBhY2l0eSBCdWlsZGluZyBQcm9ncmFtJz48dGltZSBkYXRldGltZT0nMjAyMi0wOC0xN1QxMiswMDowMCcgY2xhc3M9J2RhdGUtaWNvbic+PHN0cm9uZz5BdWc8L3N0cm9uZz4gPGVtPjE3PC9lbT48L3RpbWU+IDxkaXY+IDxwIGNsYXNzPSdub3NwYWNlIHRpbWVzIGZvbnQtbWVkaXVtJz48YSBocmVmPSdodHRwczovL3d3dy5uY3JoZDIwMjIuY29tLycgIHRhcmdldD0nX25ldycgPiBOYXRpb25hbCBDb25mZXJlbmMuLi48L2E+PC9wPiA8cCBjbGFzcz0nbm9zcGFjZSc+TmF0aW9uYWwgQ29uZmVyZW5jZSBvbg0KUmVwcm9kdWN0aXZlIEhlYWx0aCBhLi4uPC9wPjwvZGl2PjwvbGk+PGxpIGNsYXNzPSdjbGVhcicgdGl0bGU9JzNyZCBJbnRlcm5hdGlvbmFsIENvbmZlcmVuY2UgT24NCkNyeXN0YWwgRW5naW5lZXJpbmcnPjx0aW1lIGRhdGV0aW1lPScyMDIyLTA4LTMxVDEyKzAwOjAwJyBjbGFzcz0nZGF0ZS1pY29uJz48c3Ryb25nPkF1Zzwvc3Ryb25nPiA8ZW0+MzE8L2VtPjwvdGltZT4gPGRpdj4gPHAgY2xhc3M9J25vc3BhY2UgdGltZXMgZm9udC1tZWRpdW0nPjxhIGhyZWY9J2h0dHBzOi8vY2VmbWMudW9rLmVkdS5pbi8nICB0YXJnZXQ9J19uZXcnID4gM3JkIEludGVybmF0aW9uYWwgLi4uPC9hPjwvcD4gPHAgY2xhc3M9J25vc3BhY2UnPjNyZCBJbnRlcm5hdGlvbmFsIENvbmZlcmVuY2UgT24NCkNyeXN0YWwgRW5naS4uLjwvcD48L2Rpdj48L2xpPjxsaSBjbGFzcz0nY2xlYXInIHRpdGxlPSc0NFRIIEFMTCBJTkRJQSBDRUxMIEJJT0xPR1kgQ09ORkVSRU5DRSAmIElOVEVSTkFUSU9OQUwgU1lNUE9TSVVNJz48dGltZSBkYXRldGltZT0nMjAyMi0wOS0wMlQxMiswMDowMCcgY2xhc3M9J2RhdGUtaWNvbic+PHN0cm9uZz5TZXA8L3N0cm9uZz4gPGVtPjAyPC9lbT48L3RpbWU+IDxkaXY+IDxwIGNsYXNzPSdub3NwYWNlIHRpbWVzIGZvbnQtbWVkaXVtJz48YSBocmVmPSdodHRwOi8vbWNpb2hkLnVvay5lZHUuaW4vJyAgdGFyZ2V0PSdfbmV3JyA+IDQ0VEggQUxMIElORElBIENFTC4uLjwvYT48L3A+IDxwIGNsYXNzPSdub3NwYWNlJz40NFRIIEFMTCBJTkRJQSBDRUxMIEJJT0xPR1kgQ09ORkVSRU5DRSAmIElOVEUuLi48L3A+PC9kaXY+PC9saT48bGkgY2xhc3M9J2NsZWFyJyB0aXRsZT0nTmF0aW9uYWwgQ29uZmVyZW5jZSBvbkNoYW5naW5nIERpbWVuc2lvbnMgb2YgU2Nob2xhcmx5IENvbW11bmljYXRpb24gYW5kIFJvbGUgb2YgTGlicmFyaWVzIHRvQXR0YWluIEluY2x1c2l2ZSBLbm93bGVkZ2UgU29jaWV0eSc+PHRpbWUgZGF0ZXRpbWU9JzIwMjItMDktMDZUMTIrMDA6MDAnIGNsYXNzPSdkYXRlLWljb24nPjxzdHJvbmc+U2VwPC9zdHJvbmc+IDxlbT4wNjwvZW0+PC90aW1lPiA8ZGl2PiA8cCBjbGFzcz0nbm9zcGFjZSB0aW1lcyBmb250LW1lZGl1bSc+PGEgICBocmVmPSdGb3J0aENvbWluZ0V2ZW50cy8yNTEucGRmJyB0YXJnZXQ9J19uZXcnPk5hdGlvbmFsIENvbmZlcmVuYy4uLjwvYT48L3A+IDxwIGNsYXNzPSdub3NwYWNlJz5OYXRpb25hbCBDb25mZXJlbmNlIG9uQ2hhbmdpbmcgRGltZW5zaW9ucyBvZiAuLi48L3A+PC9kaXY+PC9saT4gZGSBV5R3jtG1KB7MDpZhjJVQUaNX1ZWVTMdHT5u63aC2iw==" />
</div>

<div class="aspNetHidden">

	<input type="hidden" name="__VIEWSTATEGENERATOR" id="__VIEWSTATEGENERATOR" value="CA0B0334" />
	<input type="hidden" name="__EVENTVALIDATION" id="__EVENTVALIDATION" value="/wEdAGQ3OeyTfHYp4wO5cg3LTGD3jcDk+kb+dbResxpET+nkRNhDNE3FJmzGX2v8tncztwDyFtwOR1SIdHz7pgFa+6OS2+QxrKhVw6Np9I4OEKVIa6bai8J/5z2RZlk/2FyW24a8+9Huz5PL0daKW5+Cmwyh7gLKZHL0j5K65ss6v8yUP44YaNWn5IbjTY7l9bgBrNzqWi+/l/DhM2F5QMFyhur13qB7Bkx5WhV7DRkFrwe7mycylLeSqHOp4Zq4yPVkzDAuzmh27susOdHChDLQkxwbgH0yVkwGOYy1jNBBryP+IjmvSa4Ara8LFFY5o8Zkp+iUfGocjyPwgpqbiW9bgNv1bhSqO53qpLEp1oLqt1LUDjNqiqyhQDJt/LHEPdEkKOd0bYU3yrgREZKZ/glDd65NNmNI4hj0g9BMSrO3nzbdXuOcowpa3fUMOEMlEqzcOcNH9Gxo89LV3lRS0Z3w+keQF6dyxYLY25LM/+cq7Ypybi5I/1OxwUzZ7+cQhcIfl2L0g9YE+ni7ywbwa2FPN6LYbfSJUS82fkgZJH6PwRJcdgLhQ3JR9xnR+7teV9pH3xrw/o1vTSG97V2bUBPTXTNrvM+CLFUGsSBCKeiFFqWgub9790qHmt+GkrFrBgVbo9pRS3jIyfswEsYb6qTTsnJn4xLxvvzTUTqpF7md/1p7FfnBDjH5YL0SPhaw8h0TV3FfAUaTMMQ5Lg92xVFF0z5XL5Mxk9ddso7ivqzagn9yoCfGevC3Scet29tPEk/9Fs9VT8GMBKmoNgqmcBH3t7IKhA8PbIS5J5nIyjXx01sVv+4EDPN76bx7lFJtA3Gv4mAM21D6XsDF0kbyEiumVUs2LpFqjqw5haiwXw6ufZTTBkcV2TmKfRoSv9n8VyZ/y11ToFqlmq9y9CQe7ElO375z/ZGt2AqIq6ebbdU5kEgaT2DvSsF4D8se0lmTwfFKfuhfhEIbVndZUX4Tp0S8Q/ns8dhaQdWKMSYrViVkZdbFCWgKC6i54zoqj84IwHKJg0Fzgjhbs6mUKqIyY5+Al/28F8GLKj09OUAkN4sK0/lnhAHy5eDC3wwqMnDckKH6gWKCinhgnz4JGiI2Rt6c2oJ9r8BgwahjfcyVMTSPQOlumYD+yFlr1Nq9GPpZL/qSWiirWiHDkXnCzAegLNxg7QBE5PSQ11JU+LYRmTWzyWZf0RBFCVUERU6qltBR71OVZDoqMVl8O80ICjxJ5yGDCXoFs7UT9C3bIULn/285DJ2LabvwlDBIuFVEtleLEUTi2t4SnFeU6pLbX01b5KJXNw8SaJ0CE1nnKEAz+LKk7272B4OSi0r5DiaALxrNwYVVx5nRrtUDvpbgBCIFAOuUa6kELCcmPHBHlS2mhEQnXHEh8vEDeGknPCXbJCCtpktlQUJu5OYV03hkX2vg9TRPVPIyG7sUzf26IDXs4XI+3pjjKb6tdOScx0Ub8zvvpNH6F86SOKGmzAeFmEq45XOPyh2ps7Eq8I9DqSU62RmFo7nr5tcuKCvmwUB+O8AvbOsDHpa0YDyG4RtM/3ILUJDZiLEzu8fISYaX3rljnlQGyNvDAkIYQsompPktSbUyiRStvViZETOsmR+qBSfrQpwu9H3ERuYXDtZM+OTmul2hrp5FT8mWuA1Rr+/eWP13i470L7l77HHSSPqX765jwfYoWFF26L/ozG6uONXxW9LRTBWAl7WxXxerDOOak5sXzqsih+0ywtUM+U9NRwXj9P32f/XRCVuyiSw3htCFWGQnZEZFwJaFdXORu2mhnipGHr3nZCbedTMTaUv/y3jY8cO8a70lEn6TUnzGLlJFCKxyOlo6o33tWPypzamTHkiabXKh8IpK0i4EKD792wktoHAD8eNJaglb+UemiQToGTonWLSqDy1nYigODdJtaVntia6k5J9VFGBw4GK3NOXOA7QHkrwE4OdYYVwyWBsr9/Y7ZkVvJkPd1kfF0f+ekGD7lMyP3KWCApuskWlQUGyeZhXYhLNEcNWUe6n7mMCUVEINBNtVF95aIeZbjANY2krqEObsbJMLE9R8DpYU5zLc4H/D5YsMZ5xQgT332lSPuPGSxfv7QYnoDEeQwLN0/yMs+ECG+y43HoJNFQ1zAP3iZFXM6pyU5QYI4xSOXDqzw+zTtLmkaHvyMhbiyPxFz8UtyX5nCio=" />
</div>
    <div class="wrapper row4">
        <div role="main" class="container">
            <!-- ################################################################################################ -->
            <div id="homepage">
                <!-- ########################################################################################## -->
                <!-- ########################################################################################## -->
                <!-- ########################################################################################## -->
                <div class="col-3-4 first">
                    <!-- ################################################################################################ -->
                    <section class="clear">
                    
                    
          <h2><span>University of Kashmir</span></h2>
          <div class="col-1-2 first"><img class="boxholder" src="images/demo/vice-chancellor2.jpg" alt=""></div>
          <div class="col-1-2">
            <h3>About Us</h3>
            <p style="text-align:justify">The University of Jammu and Kashmir was founded in the year 1948. 
            In the year 1969 it was bifurcated into two full-fledged Universities: University of Kashmir at
             Srinagar and University of Jammu at Jammu. The University of Kashmir is situated at Hazratbal 
             in Srinagar. It is flanked by the world famous Dal Lake on its eastern side and Nigeen Lake on 
             the western side. The Main Campus of the University spread over 247 acres of   </p>
            <br />
            <p><a href="AboutUok.aspx" >Read More &raquo;</a></p>
          </div>
        </section>
                    <!-- ################################################################################################ -->
                    <div class="clear">
                    </div>
                    <!-- ################################################################################################ -->
                    <section class="clear">
          <div class="col-1-3 first">
            <h2><span>Services</span></h2>
            <ul class="nospace spacing">
            <li><a class="button block pad20 purple clear" href="uokmail.aspx"><span class="icon-envelope-alt icon-2x imgl"></span>
                <p class="nospace times font-medium">KU Mail</p>
                <p class="nospace">Official e-Mail Service</p>
                </a></li>
              <li><a class="button block pad20 green clear" href="jobs.aspx"><span class="icon-briefcase icon-2x imgl"></span>
                <p class="nospace times font-medium">Jobs/Recruitment</p>
                <p class="nospace">Advertisements,Call Letters</p>
                </a></li>
              <li><a class="button block pad20 orange clear" href="tenders.aspx"><span class="icon-file-text-alt icon-2x imgl"></span>
                <p class="nospace times font-medium">Tenders</p>
                <p class="nospace">Notices,eTenders...</p>
                </a></li>
              <li><a class="button block pad20 yellow clear" href="EmployeeDownloads.aspx"><span class="icon-calendar-empty icon-2x imgl"></span>
                <p class="nospace times font-medium">Employee</p>
                <p class="nospace">Online Services</p>
                </a></li>
              <li><a class="button block pad20 red clear" href="download.aspx"><span class="icon-download-alt icon-2x imgl"></span>
                <p class="nospace times font-medium">Downloads</p>
                <p class="nospace">Forms,Applications...</p>
                </a></li>

                <li><a class="button block pad20 blue clear" href="photogallery.aspx"><span class=" icon-camera icon-2x imgl"></span>
                <p class="nospace times font-medium">Photogallery</p>
                <p class="nospace">Conferences,Workshops...</p>
                </a></li>
                
            </ul>
          </div>

          <div class="col-2-3">
          <h2><span>Notifications and Announcements</span></h2>
              
        

        <div class="accordion-wrapper"><a href="javascript:void(0)" class="accordion-title active"><span>Notifications</span></a>
          <div class="accordion-content default" style="height:245px; overflow:auto">
          
           <p>
            <ul id="lstNewsAndAnnouncements" class="list doughnut">
             
            <li><a href='https:events/7868.pdf' target='_new'style='font-weight:bold;    color:#4b4c4a;'>Updated Selection Notification No.: 6 of
PG, 3-Year LL.B Programmes (Self Finance Seat Quota) Session-2022; Dated: <b>17-8-2022</b></a><li><a href='https:events/7873.pdf' target='_new'style='font-weight:bold;    color:#4b4c4a;'>Selection Notification No.4 of 
M Sc Bio-Technology Programme
Session-2022; Dated: <b>17-8-2022</b></a><li><a href='https:events/7872.pdf' target='_new'style='font-weight:bold;    color:#4b4c4a;'>Selection Notification No.:1
5-Year BA-LL.B. Programme (Main Campus) Session-2022; Dated: <b>17-8-2022</b></a><li><a href='https:events/7871.pdf' target='_new'style='font-weight:bold;    color:#4b4c4a;'>Selection List of BALLB Session 2022; Dated: <b>17-8-2022</b></a><li><a href='https:events/7870.pdf' target='_new'>General Merit List of candidates who have applied for admission to B.Ed. Programme through Distance Mode session-2022.; Dated: <b>16-8-2022</b></a><li><a href='https:events/7869.pdf' target='_new'>List of candidates who have applied for admission to B.Ed. Programme through Distance Mode Session-2022 having mentioned only details of their Masters Programme only not BA/BSC/BCOM or other
related Programme/Course Details; Dated: <b>16-8-2022</b></a><li><a href='https:events/7867.pdf' target='_new'>Selection Notification No. 1 For Music & Fine Arts Programme Session-2022; Dated: <b>16-8-2022</b></a><li><a href='https:events/7866.pdf' target='_new'>Updated Roll Order List of the Candidates who have appear in the Entrance Test and applied for Admission to 
PG Professional /Non-Professional Courses/Programmes under Self-Finance Seat Quota Session-2022; Dated: <b>16-8-2022</b></a><li><a href='https:events/7865.pdf' target='_new'>Date Extended Notice for Invitation of Entries for Success Story on Water Resources: Current status and sustainable management and Biodiversity: Current status, conservation and sustainable utilization; Dated: <b>16-8-2022</b></a><li><a href='https:events/7862.pdf' target='_new'>Updated Counseling Notice-2 for PG, LLB,MBA, MBA-FM and MBA-CME Programmes Session-2022; Dated: <b>16-8-2022</b></a><li><a href='https:events/7864.pdf' target='_new'>General Merit List  of the Candidates who have appear in the Entrance Test of BA.LLB Session-2022; Dated: <b>12-8-2022</b></a><li><a href='https:events/7863.pdf' target='_new'>Roll Order List of the Candidates who have appear in the Entrance Test and applied for Admission to PG Professional /Non-Professional Courses/Programmes under Self-Finance Seat Quota Session-2022.; Dated: <b>12-8-2022</b></a><li><a href='https:events/7861.pdf' target='_new'>88th Guru Dakshta Faculty Induction Programme (HRDC); Dated: <b>12-8-2022</b></a><li><a href='https:events/7860.pdf' target='_new'>Date Sheet for GE/OE Courses of 2nd Semester (Batch 2021).; Dated: <b>11-8-2022</b></a><li><a href='https:events/7859.pdf' target='_new'>Admission Notification No.15 of 2022 For 5-Year IMBA Programme (Self-Financed Seat Quota); Dated: <b>10-8-2022</b></a><li><a href='https:events/7858.pdf' target='_new'>Admission Notification No.14 of 2022 For MBA & MBA-FM Programmes (Self-Financed Seat Quota); Dated: <b>10-8-2022</b></a><li><a href='https:events/7857.pdf' target='_new'>Selection Notification No.: 2 
For 5-Year Integrated MBA Programme Session-2022; Dated: <b>10-8-2022</b></a><li><a href='https:events/7856.pdf' target='_new'>Notification regarding Review of Course-Basket of Core/DCE/OE/GE courses for PG !st Semester Batch-2022; Dated: <b>8-8-2022</b></a><li><a href='https:events/7855.pdf' target='_new'>Selection Notification No.: 5 of 
3-Year LL.B Programme (Kashmir Law College, Nowshehra)(Professional) Session-2022; Dated: <b>8-8-2022</b></a><li><a href='https:events/7854.pdf' target='_new'>Selection Notification No.: 3 for PG Diploma Course in (French, Russian and German)
Session-2022; Dated: <b>8-8-2022</b></a><li><a href='https:events/7853.pdf' target='_new'>Date Extending Notice for Completion of Admission related formalities for Session-2022; Dated: <b>8-8-2022</b></a><li><a href='https:events/7852.pdf' target='_new'>Final Answer Keys of BA.LLB Entrance Test 2022; Dated: <b>8-8-2022</b></a><li><a href='https:events/7851.pdf' target='_new'>Notification regarding Re-opening of link for submission of online Application Form  4-Year B.Tech Programmes Session-2022; Dated: <b>8-8-2022</b></a><li><a href='https://uok.edu.in/selectionlists.aspx' target='_new' >Selection List III of PG Entrance Test Session-2022; Dated: <b>5-8-2022</b></a><li><a href='https:events/7850.pdf' target='_new'>Selection Notification No.: 8 of 2022
MBA Programme Session-2022
(IITM College, Hyderpora; Dated: <b>5-8-2022</b></a><li><a href='https:events/7849.pdf' target='_new'>Selection Notification No.: 4 of 2022
PG and other Programmes/Courses (Main Campus)
(Non-Professional and Professional); Dated: <b>5-8-2022</b></a><li><a href='https:events/7848.pdf' target='_new'>Selection Notification No.: 3 of 2022
MCA, MSCIT Programmes (Professional)
(NIELIT, Rangreth and IITM Hyderpora); Dated: <b>5-8-2022</b></a><li><a href='https:events/7847.pdf' target='_new'>88th Guru Dakshta Faculty Induction Programme(HRDC); Dated: <b>5-8-2022</b></a><li><a href='https:events/7846.pdf' target='_new'>5-Year BA-LLB Answer Keys-2022; Dated: <b>4-8-2022</b></a><li><a href='https:events/7845.pdf' target='_new'>Selection Notification No. 7 
For
MBA-CME Programme Session-2022; Dated: <b>2-8-2022</b></a></ul><a href="notifications.aspx" style="color:Black; text-align:center; font-weight:bold">View All Notifications</a>
          </p>
          </div>
        </div>
        <div class="accordion-wrapper"><a href="javascript:void(0)" class="accordion-title" onclick="javascript:GetNotificationList();"><span>Departmental Notifications</span></a>
          <div class="accordion-content" style="height:245px; overflow:auto">
           <p><select name="ddDepartment" id="ddDepartment" onchange="javascript:GetNotificationList();">
	<option value="00000000-0000-0000-0000-000000000000">0-Select Department</option>
	<option value="c5e30c7a-c8f1-4b92-86c6-6f5b191d6fd1">Allama Iqbal Library</option>
	<option value="bc6237c7-f150-4e26-9ca8-1426bd8695c6">Arabic</option>
	<option value="6bb0a5f3-b7c4-4c26-be19-09a60845a66d">Biochemistry</option>
	<option value="45ef3b2b-1aa5-40b2-9b0e-760b4b053af8">Bioinformatics Centre</option>
	<option value="4e92ef3a-0e12-44da-b8fb-dfd05e331886">Bioresources</option>
	<option value="bdcfcf70-294a-4c43-95ed-70caf685f3b2">Botany</option>
	<option value="4701b853-a330-4f94-a00e-01555a32a0ff">Center of Research for Development</option>
	<option value="eb9ccd29-2a12-4add-b65b-a72821533c47">Centre for Biodiversity and Taxonomy</option>
	<option value="bded4f1f-a839-4059-9c14-fb770fd1e678">Centre for Career Planning and Counselling</option>
	<option value="7ccf2b3f-9c10-46f8-934f-dc5d307e412c">Centre For Innovation, Incubation And Entrepreneurship</option>
	<option value="00d03ffb-f76d-4b8f-8aae-e849bc419f76">Centre for Interdisciplinary Research &amp; Innovations</option>
	<option value="4c08b6c5-614e-4a45-b8ab-cc698f040627">Centre for University Society Interface</option>
	<option value="e94d35a3-2dcb-4b08-8575-02509cd66c58">Centre for Womens Studies &amp; Research</option>
	<option value="93269b6c-7f53-4439-ae9a-3bdf55a4c649">Centre of Central Asian Studies</option>
	<option value="5af4c120-500f-48d4-92c2-9e0144e1cd3c">Chemistry</option>
	<option value="f3e29092-ef92-49fd-868b-a6779c094e53">Chief Proctor Office</option>
	<option value="6bd5908a-a47f-4516-a522-56e307e42685">Clinical Biochemistry</option>
	<option value="80b5f9f3-ebb1-48b1-88db-ad9e99a69baa">Commerce</option>
	<option value="79755f07-9550-4aeb-bd6f-5d802d56b46d">Computer Sciences</option>
	<option value="ab96b770-0a6e-4265-b820-1b8e6e8d4a61">Corona-19 University Of Kashmir</option>
	<option value="5b3e2c3d-c4e5-4e16-b952-b4dc49c85289">DDU Kaushal Kendra</option>
	<option value="358d2f43-9d2b-4d45-aa03-618b7d58f8e7">Dean Academic Affairs</option>
	<option value="61ea7645-552b-4fa6-852b-77ed58543874">Dean College Development Council</option>
	<option value="4f1cbdab-c429-4b97-868e-c6e5b25c1f43">Dean School of Earth and Environmental Science</option>
	<option value="a451f938-f667-4f96-88be-525cf5d73ce5">Department of Applied Sciences</option>
	<option value="45394dbc-80c7-4ae4-b999-9ced8350f2f8">Department of Biotechnology</option>
	<option value="33ce9554-70c8-4df4-a74b-ecfda85ad2db">Department of Students Welfare</option>
	<option value="172338c3-67f3-4026-8ca0-675ea5b332d0">Department of Urdu</option>
	<option value="3a2fea9f-3b9b-41e9-8222-37d7ff5287c5">Directorate of Convocation Complex</option>
	<option value="2cfa4584-5afe-43ce-aa4b-ad936cc9d3be">Directorate of Distance Education</option>
	<option value="bd64e8ef-c9a0-43e4-97cc-7444b5ee897a">Directorate of Internal Quality Assurance</option>
	<option value="7a3103e5-b5fc-4a26-aae3-f0b5049e7faa">Directorate of IT &amp; SS</option>
	<option value="20ae454c-0cb4-4e04-8afe-98b1921cc8ef">Directorate of Lifelong Learning</option>
	<option value="e9efb131-fe8e-43ab-86cf-58ee849418f7">Directorate of Physical Education &amp; Sports</option>
	<option value="7526f589-8bb2-471a-a379-3636612a0821">Earth Sciences</option>
	<option value="a5883c28-da92-4d58-b96c-9d147e6485c5">Economics</option>
	<option value="4f96dde9-9a35-46c7-9b3e-c80291ed5689">Education</option>
	<option value="9dd3b5ff-528d-48d4-8f52-9744caae7b65">Electronics &amp; Instrumentation Technology</option>
	<option value="6f113c58-4f9a-49ad-8531-e5f53c1dd9cb">EMMRC</option>
	<option value="9b3bd3e3-e5fb-4174-9903-298ce622e4ce">English</option>
	<option value="9f7f4199-12b5-49d1-8e41-260b35d9650c">Entrepreneurship Development Cell (EDC)</option>
	<option value="ab1ac1f1-07e3-42a2-85bc-83717ef39155">Environmental Science</option>
	<option value="a83d871e-c676-4246-ae72-efb798fd7cd5">Food Science &amp; Technology</option>
	<option value="080dbf8a-06f0-4747-9a74-d08ca769ee97">Geography &amp; Disaster Management</option>
	<option value="ce444cdb-61e7-4b39-9200-c3b92c83bb07">Geoinformatics</option>
	<option value="c7e29997-718f-4809-b6e8-a81fff32d588">Health Centre</option>
	<option value="88762580-f106-4ce1-9953-cf5db4fc18f0">Hindi</option>
	<option value="6567dbf5-79fe-4dfc-91f7-d7afbe506446">History</option>
	<option value="bad70189-7226-407e-90bf-1ae1178eda76">Home Science</option>
	<option value="ba9d3ac8-8a08-490e-baea-8ce40bbeccfd">Institute of engineering and technology</option>
	<option value="6648ebc7-49ee-4255-85d1-0a9ffa33d2a3">Institute of Foreign Languages</option>
	<option value="3a963738-5d67-4444-aeba-edda77283c15">Institute of Kashmir Studies</option>
	<option value="115980e9-9bab-4c6a-834c-de9c5cc173f8">Institute of Music and Fine Arts</option>
	<option value="5f730064-20e4-4a5a-b614-57d78a8edfd8">Institute of Technology</option>
	<option value="33a5e26f-7d09-4fca-98bc-56c5c94d5e6c">Internal Complaints Committee</option>
	<option value="fc6d91fd-9927-4022-9f0d-1d3826964505">Iqbal Institute of Culture &amp; Philosophy</option>
	<option value="df43783e-5402-4524-9201-c5df0541d1f1">J &amp; K SET Agency</option>
	<option value="13c3e09b-325d-4c2f-948c-6fd269630276">Kargil Campus</option>
	<option value="37cd8d73-1755-41fa-8aad-83fa9ac1803d">Kashmir University Alumni Association</option>
	<option value="ee7354b8-5721-4729-adbe-2b392e01b55e">Kashmiri</option>
	<option value="bcacb3dd-dabc-44fa-b367-0b6b5f50fa53">Kupwara Campus</option>
	<option value="5ce6c765-c013-446c-b6ac-b9de496f8751">Law</option>
	<option value="5f8f6634-0d83-4ec7-8d16-a513a982c28f">Leh Campus</option>
	<option value="9ebfb2f2-5003-47a4-9dfe-d3cdcc6a2020">Library and Information Science</option>
	<option value="f6ec3740-422d-4ac1-9f52-ddfe2cffcb28">Linguistics</option>
	<option value="914221ec-c54a-4a40-a052-b12d254af60b">Management Studies</option>
	<option value="5cb79b4e-ee44-4448-9dfe-ca876c31a24e">Mathematics</option>
	<option value="71bcec76-55d0-4dd7-8aa4-dfab6f1bd4ce">Media Education Research Centre</option>
	<option value="2b864005-204f-4167-90d8-408eb8ddac9b">Nanotechnology</option>
	<option value="1762a728-3f12-460a-b00c-1476fcadd6c8">National Himalayan Cryospheric Research Lab</option>
	<option value="6efb5c27-a427-450d-af93-af240d4697d5">National Service Scheme</option>
	<option value="a25b3dec-8db4-4c44-830a-c54e6a38dd73">NewGen IEDC</option>
	<option value="a85b97f8-74f1-41f0-a746-1106e437f466">North Campus</option>
	<option value="80c3b487-59af-4745-bbcf-1c15281d74e3">Office of the Dean Research</option>
	<option value="eae3d4c9-d541-4b84-93de-f7681d8c2353">Office of the Provost (Boys)</option>
	<option value="b54c31d1-b423-481e-8480-b16a64665296">Persian</option>
	<option value="4fd6847e-5f1e-4a56-b63f-6d0edb0f326c">Pharmaceutical Sciences</option>
	<option value="1802f12c-ef6d-4d50-890e-bb9f7f678a23">Physics</option>
	<option value="63293c3b-f4ff-4c35-a387-7236c46ec0fa">Political Science</option>
	<option value="fb7d7958-7015-454e-8e81-0d536ab44bad">Population Research Centre</option>
	<option value="5c8b2b67-0b86-4f4a-b867-e139f23e2339">Provost Girls Hostels</option>
	<option value="c2dd746b-be2c-4212-b03e-2040471ba1e6">Psychology</option>
	<option value="3cee644f-963d-403e-afb4-04bf2f0a4305">Public Relations Centre</option>
	<option value="d4a57b94-1a28-47a2-95cd-5415e5e4151d">Sanskrit</option>
	<option value="6d8be055-fc07-4110-8b8a-48477e9b960a">School of Business Studies</option>
	<option value="d2acb489-bd79-4640-a0b3-ef061d9d848a">School of Unani &amp; Ayurvedic Medicine</option>
	<option value="36892408-1fed-4431-9848-0761b9e02587">Shah-i-Hamadan Institute of Islamic Studies</option>
	<option value="43f7d981-9626-4f29-9eaf-1cc7a463a9c1">Shaikh-Ul-Aalam Centre for Multidisciplinary Studies</option>
	<option value="f45bcdab-5a41-4b9b-8c18-9df1f163f480">Social Work</option>
	<option value="c2d3b278-4cf7-49a5-9525-af5e352f2900">Sociology</option>
	<option value="97f04de5-ee1f-47d6-8c2e-7ee36909f54f">South Campus</option>
	<option value="7f9aa08c-c3d9-474c-8067-e0ee9c95a834">State Resource Centre</option>
	<option value="3df6de46-e015-49ef-8ce5-b55d62405446">Statistics</option>
	<option value="9c0ccb5c-f84b-4f00-9410-046481003a8e">Tourism, Hospitality &amp; Leisure Studies</option>
	<option value="c2ce2564-691e-4c9a-ae8a-44f8e3244c60">UGC-Human Resource Development Centre</option>
	<option value="ab9a6ae5-2487-460d-a238-22772ea8ffcc">University Landscape Development Division</option>
	<option value="66ec1908-5fe0-4cbe-86cf-cd7cfced0534">University Science Instrumentation Centre</option>
	<option value="cae2d08f-4f62-428e-b6ea-cf46cdccbf42">Zoology</option>

</select>
            <ul id="lstDepartmentalNotifications" class="list doughnut">
             
            </ul><a id="lnkDN" href="DepartmentNotification.aspx" style="color:Black; text-align:center; display:none; font-weight:bold">View All Notifications</a>
          </p>
          </div> 
        </div>
        <div class="accordion-wrapper"><a href="javascript:void(0)" class="accordion-title"><span>General Notices</span></a>
          <div class="accordion-content" style="height:245px; overflow:auto">
           <p>
            <ul id="lstGeneralNotifications" class="list doughnut">
             
            <li ><a href='https://egov.uok.edu.in/courseinfo#ugforms/prelogin/default_new.aspx?id=6' target='_new' > UG-Backlog Examination Forms for 4th semester batches (2016-2019)</a><li ><a href='https://egov.uok.edu.in/courseinfo#ugforms/PaymentIssues.aspx' target='_new' > Check Fee Status-UG (Backlog) & B.Ed (Regular/Backlog) Exam Forms</a><li ><a href='https://egov.uok.edu.in/exams/ugforms/prelogin/default.aspx?id=20' target='_new' > Admit Cards for  B.Ed 1st & 2nd Semester/s DDE(Distance) & Dept. of Edu.(Regular) Batch (2020-22)</a><li ><a href='https://egov.uok.edu.in/courseinfo#ugforms/prelogin/default_new.aspx?id=1' target='_new' > Admit cards for Ug-5th SEM Reg/Pvt (2019) And Backlog (2016-2018)</a><li ><a href='https://egov.uok.edu.in/courseinfo#ugforms/prelogin/default_new.aspx?id=4' target='_new' > Admit cards for  2nd Semester Reg.& Pvt(2021) And Backlog (2016-20)</a><li ><a href='https://egov.uok.edu.in/courseinfo#ugforms/prelogin/default_new.aspx?id=102' target='_new' > Admit Cards For IMTH 5TH (2019)/3rd(2020)&2nd(2021) & BACKLOG (2017-2020) SEMESTER</a><li ><a href='https://egov.uok.edu.in/courseinfo#ugforms/prelogin/default.aspx?id=4' target='_new' > Admit cards for 1st & 2nd Semester Molvi Reg.(2021)-Batch</a><li ><a href='https://egov.uok.edu.in/courseinfo#ugforms/prelogin/default.aspx?id=11' target='_new' > Backlog 1st And 2nd Year Bsc MLT (2016-2019)</a><li ><a href='https://egov.uok.edu.in/courseinfo#ugforms/prelogin/default_new.aspx?id=31' target='_new' > Exam Forms for B.Ed 1st Semester CRC Batch (2021)</a><li ><a href='https://egov.uok.edu.in/eConduct/' target='_new' > Examination forms & Admit Cards for PG, BTech,BE & Diploma Courses</a></ul>
          </p>
          </div>
        </div>   
      <div class="accordion-wrapper"><a href="javascript:void(0)" class="accordion-title"><span>Admissions</span></a>
          <div class="accordion-content" style="height:245px; overflow:auto">
            <p>
            <ul id="lstAdmissions" class="list doughnut">
              
            <li ><a href='https://egov.uok.edu.in/imba/Prelogin/PaymentApplicationForm.aspx' target='_new' > Application Form for 5-Year IMBA Programmes (Under Self Finance) Session-2022</a><li ><a href='https://egov.uok.edu.in/Btech/PostLogin/Default.aspx' target='_new' > Application Form for B.Tech Programmes Session 2022</a><li ><a href='https://egov.uok.edu.in/mba/Prelogin/PaymentApplicationForm.aspx' target='_new' > Application Form for MBA Programme (Under Self Finance) Session-2022</a><li ><a href='https://egov.uok.edu.in/mba/Prelogin/PaymentApplicationFormmbafm.aspx' target='_new' > Application Form for MBA-FM Programme (Under Self Finance) Session-2022</a><li ><a href='https://egov.uok.edu.in/eservices/pgadmission/prelogin/Admissionform.aspx' target='_new' > Admission Form For PG Programmes , LLM, M.Pharma, M.Tech, B.Tech Lateral Entry,M.Ed,B.Ed ,MBA/MBAFM/MBACME, BALLB/LLB, B.Tech, B.Voc, IMBA, Music Fine Art, PG Diploma,Diploma, Certificate Courses 1st Semester (Session 2022)</a><li ><a href='https://egov.uok.edu.in/eAdmissionsProf/Prelogin/MyKUAdmitCard.aspx' target='_new' > Admit Cards for BA.LLB Entrance Test Session-2022</a><li ><a href='https://egov.uok.edu.in/eAdmissionsDDE/Prelogin/EntranceHome.aspx' target='_new' > Application Form for B.Ed Programme (Distance Education)Session 2022</a><li ><a href='https://egov.uok.edu.in/eAdmissions/Prelogin/resultstatus.aspx' target='_new' > Entrance Test Score - Session 2022</a><li ><a href='https://egov.uok.edu.in/eadmissions/Prelogin/entrancehome.aspx' target='_new' > Application form for MA Hindi Session 2022</a><li ><a href='http://egov.uok.edu.in/eservices/phdadmission/prelogin/admissionform.aspx' target='_new' > Registration Form for Integrated M.Phil/Ph.D -Session 2022</a><li ><a  href='Admissions/474.pdf' target='_new'>Application Form for Admission to Regular Full-time
Programmes of Study for Foreign Nationals</a > <li ><a href='https://egov.uok.edu.in/eadmissions/Prelogin/PaymentApplicationForm.aspx' target='_new' > Application Form for PG Programmes (Under Self Finance) Session-2022</a><li ><a href='https://egov.uok.edu.in/eservices/pgadmission/prelogin/3RDSemviewbatchs2017.aspx' target='_new' > Admission Form for PG Courses, M.Tech(CS)4th,3rd & 2nd Sem (Batch 2018/2019/2021, B.Ed, Integrated Courses 3rd Semester, MCA 3rd,5th Sem (Batch 2017/18/19) 2nd Year B.Sc  Nursing /M.Pharm/ B.Pharma 2nd Year & 3th Year,LLM, MCA, Home Science 3rd Sem (Batch 2018), IMBA 3rd Semester, 5th Semester, 7th Semester, 9th Semester, Music Fine Arts Batch (2018/2019/2020)</a><li ><a href='researchsyllabi.aspx' target='_new' > PhD/Mphil Entrance Test Syllabus</a><li ><a href='http://egov.uok.edu.in/eservices/pgadmission/prelogin/3RDSemviewbatchs2018.aspx' target='_new' > Fee slip of 3rd Sem Batch 2018 (Second Installment)</a></ul>
          </p>
         </div>
        </div>
        <div class="accordion-wrapper"><a href="javascript:void(0)" class="accordion-title"><span>Student Registration</span></a>
          <div class="accordion-content" style="height:245px; overflow:auto">
           <p>
            <ul id="lstRegistration" class="list doughnut">
              
            <li ><a href='https://egov.uok.edu.in/collegeadm/AdmDetails/instructionSPAGE.ASPX' target='_new' > Registration Form for College UG Admissions-2022 (Regular Mode)  (under National Education Policy-NEP</a><li ><a href='https://egov.uok.edu.in/collegeadm/AdmDetails/StudentStatus.aspx?uio1o=119988' target='_new' > My Form Status,Subject Confirmation and FEE Payment for UG 1st/2nd Sem. batch 2022  (Under National Education Policy-NEP)</a><li ><a href='https://egov.uok.edu.in/CollegeAdm/AdmDetails/StudentStatus_Promotional.aspx?rcodert=202114&rsemid=3&appid=908iiou1234mn&serviceid=1xx234@@@' target='_new' > FEE Payment for B.ED 3rd & 4th (Private Colleges), Batch 2019-21</a><li ><a href='https://egov.uok.edu.in/CollegeAdm/AdmDetails/StudentStatus_Promotional.aspx?rcodert=20211&rsemid=3&appid=908iiou1234mn&serviceid=1xx234404040' target='_new' > My Form Status,Subject Confirmation and FEE Payment for UG 3rd/4th Sem. batch 2021</a><li ><a href='https://egov.uok.edu.in/CollegeAdm/admdetails/HomeBasicRegFormPromotional_RRID_BED.aspx' target='_new' > Admission Cum Examination Forms For 3rd & 4th Semester B.ED (Private Colleges), Batch 2019-21</a><li ><a href='https://egov.uok.edu.in/CollegeAdm/AdmDetails/StudentStatus_Promotional.aspx?rcodert=20191&rsemid=5&appid=908iiou1234mn&serviceid=1xx234404040' target='_new' > My Form Status and FEE Payment for UG 5th/6thSem.  batch 2019</a><li ><a href='https://egov.uok.edu.in/CollegeAdm/AdmDetails/HomeBasicRegFormPromotional_rrid.aspx' target='_new' > Admission Forms for UG 3rd/4th  sem Batch 2021 -Regular (Not Enrolled in Colleges)</a><li ><a href='https://egov.uok.edu.in/CollegeAdm/AdmDetails/StudentStatus_Promotional.aspx?rcodert=202012&rsemid=3&appid=908iiou1234mn&serviceid=1xx234404040' target='_new' > My Form Status and FEE Payment for BARCH 3rd/4th Sem. batch 2020</a><li ><a  href='Registration/61.pdf' target='_new'>“Inter College Migration During the Course Order No.1 of 2018</a > <li ><a  href='Registration/50.pdf' target='_new'>Inter College Migration Order No.1 (2018)</a > <li ><a  href='Registration/42.pdf' target='_new'>List of Registration No. allotted to  Private Candidates of batch 2021 (CBCS Scheme)</a > <li ><a href='https://egov.uok.edu.in/courseinfo/migration/prelogin/instructions.aspx' target='_new' > Application form for Inter-University Migration</a><li ><a href='https://egov.uok.edu.in/courseinfo/migration/prelogin/PrintForm.aspx' target='_new' > Status of Inter-University Migration Certificate</a><li ><a href='https://egov.uok.edu.in/courseinfo/pgstatus/default.aspx' target='_new' > Registration Status For PG Students</a><li ><a  href='Registration/70.pdf' target='_new'>Inter College Migration  Order No.01 of 2020</a > <li ><a  href='Registration/31.pdf' target='_new'>One subject change order No. 2</a > <li ><a  href='Registration/32.pdf' target='_new'>One subject change Order No.3</a > <li ><a  href='Registration/26.pdf' target='_new'>One subject change Order No.1</a > <li ><a href='https://egov.uok.edu.in/courseinfo/streamchange/prelogin/streamchangestatus.aspx' target='_new' > Stream Change Status</a><li ><a  href='Registration/40.pdf' target='_new'>One subject change order no. 3</a > <li ><a  href='Registration/58.pdf' target='_new'>One Subject Change for Batch 2017</a > <li ><a  href='Registration/66.pdf' target='_new'>One Subject Change Order (24-01-2019)</a > <li ><a  href='Registration/54.pdf' target='_new'>One Subject Order No.01 of 2018</a > <li ><a  href='Registration/63.pdf' target='_new'>One Subject Order (2018 Nov)</a > <li ><a  href='Registration/62.pdf' target='_new'>One Subject Order (2018 New)</a > <li ><a  href='Registration/53.pdf' target='_new'>Inter College Migration Order No.2 (2018)</a > <li ><a href='https://egov.uok.edu.in/courseinfo' target='_new' > Student Academic Details</a></ul>
          </p>
          </div>
        </div>
        <div class="accordion-wrapper"><a href="javascript:void(0)" class="accordion-title prc"><span>Public Relations Centre</span></a>
          <div class="accordion-content prcD" style="height:245px; overflow:auto">
           <p>
            <ul id="lstAlerts" class="list doughnut">
             
            </ul>
          </p>
          </div>
        </div>
            
            <div class="clear"></div>
          </div>


        </section>
                    <!-- ################################################################################################ -->
                </div>
                <!-- ################################################################################################ -->
                <!-- ################################################################################################ -->
                <div id="sidebar_1" class="sidebar col-1-4">
                    <aside> 
          <!-- ########################################################################################## -->
          <h2><span>Upcoming Events</span></h2>
          <ul id="lstEvents" class="nospace spacing push50" style="height:245px;overflow:auto;">
          
          
         
          <li class='clear' title='National Conference on
Reproductive Health and Disease & Capacity Building Program'><time datetime='2022-08-17T12+00:00' class='date-icon'><strong>Aug</strong> <em>17</em></time> <div> <p class='nospace times font-medium'><a href='https://www.ncrhd2022.com/'  target='_new' > National Conferenc...</a></p> <p class='nospace'>National Conference on
Reproductive Health a...</p></div></li><li class='clear' title='3rd International Conference On
Crystal Engineering'><time datetime='2022-08-31T12+00:00' class='date-icon'><strong>Aug</strong> <em>31</em></time> <div> <p class='nospace times font-medium'><a href='https://cefmc.uok.edu.in/'  target='_new' > 3rd International ...</a></p> <p class='nospace'>3rd International Conference On
Crystal Engi...</p></div></li><li class='clear' title='44TH ALL INDIA CELL BIOLOGY CONFERENCE & INTERNATIONAL SYMPOSIUM'><time datetime='2022-09-02T12+00:00' class='date-icon'><strong>Sep</strong> <em>02</em></time> <div> <p class='nospace times font-medium'><a href='http://mciohd.uok.edu.in/'  target='_new' > 44TH ALL INDIA CEL...</a></p> <p class='nospace'>44TH ALL INDIA CELL BIOLOGY CONFERENCE & INTE...</p></div></li><li class='clear' title='National Conference onChanging Dimensions of Scholarly Communication and Role of Libraries toAttain Inclusive Knowledge Society'><time datetime='2022-09-06T12+00:00' class='date-icon'><strong>Sep</strong> <em>06</em></time> <div> <p class='nospace times font-medium'><a   href='ForthComingEvents/251.pdf' target='_new'>National Conferenc...</a></p> <p class='nospace'>National Conference onChanging Dimensions of ...</p></div></li> </ul>
          <!-- /Upcoming Events -->
          <h2><span>KU Tarana</span></h2>
         
       <iframe width="250" height="150"src="https://www.youtube.com/embed/UxOVSqnoF94" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
       <iframe width="250" height="150" src="https://www.youtube.com/embed/zxu6hkutoms" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
       
        
        <br /><br />
            


          
          <!-- /Video Tour -->
        <h2><span>Quick Links</span></h2>
          <nav>
            <ul>
              
            <li><a href="https://egov.uok.edu.in/courseinfo" target="_blank">Student Academic History</a></li>
             <li><a href="https://egov.uok.edu.in/eservices/syllabus/prelogin/course.aspx?coursetype=UGP" target="_blank">Syllabus & Statutes</a></li>
             <li><a href="Journal.aspx">KU Journals</a></li>
              <li><a href="alumni.aspx" style="color:Maroon" ><b>Alumni Registration</b></a></li>
            <li><a href="http://ddeku.edu.in/Main/ViewPage.aspx?Page=DIQA_DEB_NAAC_INFORMATION&active=lnk7" target="_blank" style="color:Maroon" ><b>UGC-DEB Proposal (2021)</b></a></li>
            
           
            
           
            
            
             
            
             
            
            
              

              
            </ul>
          </nav>
          <!-- /Sidebar Navigation --> 
          <!-- ########################################################################################## --> 
        </aside>
                </div>
                <!-- ########################################################################################## -->
                <!-- ########################################################################################## -->
                <!-- ########################################################################################## -->
            </div>
            <!-- ################################################################################################ -->
            <div class="clear">
            </div>
            <!-- Ensure That Everything Has Been Cleared -->
        </div>
        <!-- End class=container -->
    </div>
    <!-- End wrapper row4 -->
    <!-- ################################################################################################ -->
    <!-- ################################################################################################ -->
    <!-- Footer START -->
    <!-- LINK BLOCK -->
<div class="wrapper row5">
  <div class="linkblock">
    <!--<h2 class="title">Optional block of links</h2>-->
    <nav class="clear">
      <div class="col-1-5 first">
        <ul>
           <li><a href="Aid.aspx" >Scholarships & Student Aid</a></li>    
          <li><a href="https://egov.uok.edu.in/hms" target="_blank" >Hostel Accomodation</a></li>
          <li><a href="http://ccpc.uok.edu.in/" target="_blank">Career Counselling</a></li>
          <li><a href="http://dsw.uok.edu.in/" target="_blank">Student Welfare</a></li>
          <li><a href="http://healthcentre.uok.edu.in" >Health Services</a></li>
          <li><a href="http://pghostels.uok.edu.in/" target="_blank">Girls Hostel</a></li>    
          <li><a href="http://dpe.uok.edu.in/" >Sports</a></li> 
           <li><a href="http://nss.uok.edu.in" target="_blank">National Service Scheme</a></li>  
           <li><a href="http://ghouses.uok.edu.in" target="_blank">Hospitality & Protocol</a></li>   
        </ul>
      </div>
      <div class="col-1-5">
        <ul>
          <li><a href="http://prc.uok.edu.in/" target="_blank" >Public Relation Centre</a></li>
          <li><a href="http://ucc.uok.edu.in/" target="_blank">Convocation Complex</a></li>
          <li><a href="http://proctor.uok.edu.in/" target="_blank">Proctorial Organisation</a></li>
          <li><a href="http://icc.uok.edu.in/" target="_blank">Complaints Committee</a></li>
          <li><a href="download/antiragging.pdf" target="_blank">Norms Against Ragging</a></li>
          
          <li><a href="RTI.aspx" >RTI Information Cell</a></li>
          <li><a href="FBdisclaimer.aspx">KU Facebook Disclaimer</a></li>
            <li><a href="NRIF.aspx">NIRF</a></li>
            <li><a href="NAAC.aspx">NAAC</a></li>
            
          
          
        </ul>
      </div>
      <div class="col-1-5">
        <ul>      
          <li><a href="EmployeeDownloads.aspx">Employee Online Services</a></li>
          <li><a href="http://asc.uok.edu.in" target="_blank">HRD Centre</a></li>     
          <li><a href="https://uok.edu.in/estates/" target="_blank">Estates Section</a></li>
           <li><a href="eGov.aspx">e-Governance</a></li>
          <li><a href="http://www.gian.iitkgp.ac.in/" target="_blank">GIAN Portal</a></li>
           <li><a href="https://uok.edu.in/diqa/" >DIQA</a></li>
            <li><a href="https://uok.edu.in/Recruitment/" target="_blank">Recruitment</a></li>
            <li><a href="download/AntiPlagiarism.pdf" target="_blank">Anti Plagiarism</a></li>
            <li><a href="https://portal.mhrdnats.gov.in/boat/login/user_login.action" target="_blank">NATS Portal</a></li>
             <li><a href="https://gati.uok.edu.in/" target="_blank">GATI</a></li>
             
            
            
           
            
        </ul>
      </div>
      <div class="col-1-5">
        <ul>    
          <li><a href="download/Examination Statutes.pdf" target="_blank">Examination Statutes</a></li>
          <li><a href="download/UniCal.pdf" target="_blank">University Calender</a></li>
          <li><a href="download/Academic Calendar.pdf" target="_blank">Academic Calendar</a></li>
         
           <li><a href="https://egov.uok.edu.in/eConduct/about" target="_blank">Academic Section</a></li>
          <li><a href="download/UGC Guidelines.pdf" target="_blank">UGC Guidelines</a></li>
          <li><a href="http://set.uok.edu.in/" target="_blank">JKSET</a></li> 
          <li><a href="donations.aspx" >Donations</a></li>
           <li><a href="policies.aspx" >University Policies</a></li>
           <li><a href="cbcs.aspx" >CBCS</a></li>
           <li><a href="NEP.aspx" >NEP</a></li>
          
        </ul>
      </div>
      <div class="col-1-5">
        <ul>
          <li><a href="importantlinks.aspx">Important Links</a></li>
          <li><a href="notifications.aspx">Notifications</a></li>
         <li><a href="NAACVideos.aspx">NAAC Visit</a></li>
          <li><a href="Circular.aspx">Circulars</a></li>
          <li><a href="https://www.uok.edu.in/HelpDesk" target="_blank">Help Desk</a></li>
          <li><a href="FeeStructure.aspx" >Fee and Other Charges</a></li>
           <li><a href="http://www.vidyalakshmi.co.in" target="_blank" >Vidya Lakshmi Portal</a></li>
           <li><a href="download/Social_Media_Policy.pdf" target="_blank" >Social Media Policy</a></li>
           
          
          
        </ul>
      </div>
    </nav>
  </div>
</div>
<!-- ################################################################################################ --> 
<!-- ################################################################################################ --> 
<!-- FOOTER -->
<div class="wrapper row6">
  <footer role="contentinfo" id="p-footer" class="clear center"> 
    <!-- BLOCK 1 -->
    <div class="col-1-4 first">
    <a href="https://egov.uok.edu.in/feedbackforum" style="color:inherit">
      <div class="block push30"><span class="cc circle icon-paste"></span></div>
       <h6 class="push20">Feedback Forum</h6>
       <p class="nospace">Comment, Suggestion</p>
       <p class="nospace">Grievance ....</p>
    </a>
    </div>
    <!-- BLOCK 2 -->
    <div class="col-1-4">
    <a href="Directory.aspx"  style="color:inherit;">
      <div class="block push30"><span class="cc circle icon-phone"></span></div>
      <h6 class="push20">Telephone Directory</h6>
      <p class="nospace">+91 194 227 2096</p>
      <p class="nospace">+91 194 227 2097</p>
    </a>
    </div>
    <!-- BLOCK 3 -->
    <div class="col-1-4">
      <div class="block push30"><span class="cc circle icon-envelope-alt"></span></div>
      <h6 class="push20">Email</h6>
      <p class="nospace"><a href="#" style="color:White">info@uok.edu.in</a><br>
        <a href="#" style="color:White">pro@uok.edu.in</a></p>
    </div>
    <!-- BLOCK 4 -->
    <div class="col-1-4">

    <a href="contact.aspx" style="color:inherit;">
      <div class="block push30"><span class="cc circle icon-map-marker"></span></div>

      <h6 class="push20">Address</h6>
      <address>
      Hazratbal, Srinagar<br>
       J&K, India 190006
      </address>
      </a>
     
      <!--<form method="post" action="#">
        <input type="text" value="">
        <input type="submit" value="Subscribe">
      </form>-->
      
    </div>
  </footer>
  <!-- COPYRIGHT -->
  <div id="copyright" class="clear"> 
<center><a style="color:Green; text-decoration:none" href="https://play.google.com/store/apps/details?id=net.kashmiruniversity&hl=en" target="_blank"><img src="images/play2.png" style="width:120px" title="Download University of Kashmir Android App"/></a> </center> 
    <div class="fl_left">Copyright <a href='https://egov.uok.edu.in/CourseInfo/login.aspx' target="_blank" >&copy;</a> 2017 University of Kashmir | <a href="disclaimer.aspx">Disclaimer</a><!--|<a href="FBdisclaimer.aspx">KU Facebook Disclaimer</a>-->
   </div>
    <div class="fl_right">
      <ul class="nospace inline">
        <li><a href="http://itss.uok.edu.in" target="_blank">Developed & Maintained By Directorate of IT & SS</a></li>
         <!--<li><a href="disclaimer.aspx">Disclaimer</a>|</li><li><a href="FBdisclaimer.aspx">KU Facebook Disclaimer</a></li>
        <li><a href="#">Link 3</a> / </li>
        <li><a href="#">Link 4</a> / </li>
        <li><a href="#">Link 5</a></li>-->
      </ul>
    </div>
  </div>
</div>

<!-- END FOOTER --> 
<!-- ################################################################################################ --> 
<!-- ################################################################################################ --> 
<!-- BACK TO TOP BUTTON --> 
<a href="#top" id="scrolltotop" title="Back To Top"><span class="icon-arrow-up icon-2x"></span></a> 
<!-- ################################################################################################ --> 
<!-- ################################################################################################ --> 
    <!-- Footer END -->
    <!-- ################################################################################################ -->
    <!-- ################################################################################################ -->
    <!-- JAVASCRIPTS -->
    <!-- JS START -->
    <!-- JAVASCRIPTS --> 
<!-- <script src="http://code.jquery.com/jquery-latest.min.js"></script> --> 
<script src="layout/scripts/jquery-latest.min.js"></script> 
<!-- <script src="http://code.jquery.com/ui/1.10.3/jquery-ui.min.js"></script> --> 
<script src="layout/scripts/jquery-ui.min.js"></script> 
<!-- Media --> 
<script src="layout/scripts/fitvids/jquery.fitvids.js"></script> 
<!-- Custom Settings --> 
<script src="layout/scripts/custom.js"></script>
<script>
    $(document).ready(function () {

    $('head').append("<style>.ColouredList li:before{color:" + layoutColorName + ";} </style>");
    $(".logo").attr("src", "images/KU" + layoutColorName + ".png");
    });
</script>

    <!-- JS END -->
    <!-- Slider -->
    <script src="layout/scripts/flexslider/jquery.flexslider-min.js"></script>
    <script src="layout/scripts/flexslider/jquery.flexslider-setup.js"></script>
    
    <script>
        $(document).ready(function () {
            //            $("#lstEvents").niceScroll({ autohidemode: true, cursorcolor:layoutColor});
            //            $(".accordion-content").niceScroll({ autohidemode: true, cursorcolor: layoutColor });
            //            $(".alert-msg").niceScroll({ autohidemode: true, cursorcolor: layoutColor });
            $("li.active").removeClass("active");
            $("#lnkHome").addClass("active");
        });
    </script>
    <script src="JWPlayer/jwplayer.js" type="text/javascript"></script>
    <script type="text/javascript">
        jwplayer("player").setup({
            autostart: false,
            image: "images/demo/video0.png",
            flashplayer: "jwplayer/player.swf",
            file: "video/Tarana.flv",
            width: 250,
            height: 200
        });


       
    </script>
    </form>
</body>
</html>
