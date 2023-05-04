Download Link: https://assignmentchef.com/product/solved-cs575-assignment-2
<br>
<p class="MsoNormal" style="mso-outline-level: 1;"><b style="mso-bidi-font-weight: normal;"><u><span lang="EN-US" style="font-family: 'Arial',sans-serif;">Objective: </span></u></b>

<p class="MsoNormal" style="margin-left: 36.0pt; text-indent: -18.0pt; mso-outline-level: 1; mso-list: l4 level1 lfo1; tab-stops: list 36.0pt;"><!-- [if !supportLists]--><span lang="EN-US" style="font-family: 'Arial',sans-serif; mso-fareast-font-family: Arial;"><span style="mso-list: Ignore;">(1)<span style="font: 7.0pt 'Times New Roman';">  </span></span></span><!--[endif]--><span lang="EN-US" style="font-family: 'Arial',sans-serif;">Design and analyze an algorithm using divide and conquer strategy </span>

<p class="MsoNormal" style="margin-left: 36.0pt; text-indent: -18.0pt; mso-outline-level: 1; mso-list: l4 level1 lfo1; tab-stops: list 36.0pt;"><!-- [if !supportLists]--><span lang="EN-US" style="font-family: 'Arial',sans-serif; mso-fareast-font-family: Arial;"><span style="mso-list: Ignore;">(2)<span style="font: 7.0pt 'Times New Roman';">  </span></span></span><!--[endif]--><span lang="EN-US" style="font-family: 'Arial',sans-serif;">Establish recurrence equation and solve it.</span>

<p class="MsoNormal" style="margin-left: 36.0pt; text-indent: -18.0pt; mso-outline-level: 1; mso-list: l4 level1 lfo1; tab-stops: list 36.0pt;"><!-- [if !supportLists]--><span lang="EN-US" style="font-family: 'Arial',sans-serif; mso-fareast-font-family: Arial;"><span style="mso-list: Ignore;">(3)<span style="font: 7.0pt 'Times New Roman';">  </span></span></span><!--[endif]--><span lang="EN-US" style="font-family: 'Arial',sans-serif;">Enhance the concept of proof of correctness for algorithms.</span>

<p class="MsoNormal" style="mso-outline-level: 1;"><span lang="EN-US" style="font-family: 'Arial',sans-serif;">There are two parts in this assignment: (A) Theory part and (B) programming part</span>

<p class="MsoNormal" style="mso-outline-level: 1;"><b style="mso-bidi-font-weight: normal;"><u><span lang="EN-US" style="font-family: 'Arial',sans-serif;">[Part A] Theory </span></u></b>

<p class="MsoNormal" style="mso-outline-level: 1;"><b style="mso-bidi-font-weight: normal;"><u><span lang="EN-US" style="font-family: 'Arial',sans-serif;"><span style="text-decoration: none;"> </span></span></u></b>

<ol style="margin-top: 0cm;" start="1" type="1">

 <li class="MsoNormal" style="mso-outline-level: 1; mso-list: l1 level1 lfo2; tab-stops: list 36.0pt;"><span lang="EN-US" style="font-size: 11.0pt;">(9%) Given an image which shows two white regions, design an algorithm to fill the region 1 by the red color, and fill the region 2 by the blue color. Assume the image is represented by a Matrix with the size of N by N (e.g., color[x, y]), use the <i style="mso-bidi-font-style: normal;">recursive</i> algorithm to solve this problem. (Assume the value of color is either WHITE, or RED, or BLUE). White a pseudo-code.</span></li>

</ol>

<p class="MsoNormal" style="margin-left: 18.0pt; mso-outline-level: 1;"><span lang="EN-US" style="font-size: 11.0pt;"> </span>

<p class="MsoNormal" style="margin-left: 18.0pt; mso-outline-level: 1;"><!-- [if mso & !supportInlineShapes & supportFields]><spanlang=EN-US style='font-size:11.0pt'><span style='mso-element:field-begin;mso-field-lock:yes'></span><span style='mso-spacerun:yes'> </span>SHAPE<spanstyle='mso-spacerun:yes'>  </span>* MERGEFORMAT <span style='mso-element:field-separator'></span></span><![endif]--><span lang="EN-US" style="font-size: 11.0pt;"><!-- [if gte vml 1]><v:group id="_x0000_s1026" editas="canvas" style='width:315.8pt;height:110.75pt; mso-position-horizontal-relative:char;mso-position-vertical-relative:line' coordorigin="3071,3684" coordsize="5263,1846"> <o:lock v:ext="edit" aspectratio="t"/> <v:shapetype id="_x0000_t75" coordsize="21600,21600" o:spt="75"  o:preferrelative="t" path="m@4@5l@4@11@9@11@9@5xe" filled="f" stroked="f">  <v:stroke joinstyle="miter"/>  <v:formulas>   <v:f eqn="if lineDrawn pixelLineWidth 0"/>   <v:f eqn="sum @0 1 0"/>   <v:f eqn="sum 0 0 @1"/>   <v:f eqn="prod @2 1 2"/>   <v:f eqn="prod @3 21600 pixelWidth"/>   <v:f eqn="prod @3 21600 pixelHeight"/>   <v:f eqn="sum @0 0 1"/>   <v:f eqn="prod @6 1 2"/>   <v:f eqn="prod @7 21600 pixelWidth"/>   <v:f eqn="sum @8 21600 0"/>   <v:f eqn="prod @7 21600 pixelHeight"/>   <v:f eqn="sum @10 21600 0"/>  </v:formulas>  <v:path o:extrusionok="f" gradientshapeok="t" o:connecttype="rect"/>  <o:lock v:ext="edit" aspectratio="t"/> </v:shapetype><v:shape id="_x0000_s1027" type="#_x0000_t75" style='position:absolute;  left:3071;top:3684;width:5263;height:1846' o:preferrelative="f">  <v:fill o:detectmouseclick="t"/>  <v:path o:extrusionok="t" o:connecttype="none"/>  <o:lock v:ext="edit" text="t"/> </v:shape><v:rect id="_x0000_s1028" style='position:absolute;left:3078;top:3703;  width:2200;height:1820' fillcolor="black"/> <v:shapetype id="_x0000_t56" coordsize="21600,21600" o:spt="56" path="m10800,l,8259,4200,21600r13200,l21600,8259xe">  <v:stroke joinstyle="miter"/>  <v:path gradientshapeok="t" o:connecttype="custom" o:connectlocs="10800,0;0,8259;4200,21600;10800,21600;17400,21600;21600,8259"   o:connectangles="270,180,90,90,90,0" textboxrect="4200,5077,17400,21600"/> </v:shapetype><v:shape id="_x0000_s1029" type="#_x0000_t56" style='position:absolute;  left:3190;top:4028;width:900;height:925'/> <v:oval id="_x0000_s1030" style='position:absolute;left:4528;top:4003;width:462;  height:1150'/> <v:rect id="_x0000_s1031" style='position:absolute;left:6128;top:3691;width:2200;  height:1820' fillcolor="black"/> <v:shape id="_x0000_s1032" type="#_x0000_t56" style='position:absolute;left:6240;  top:4016;width:900;height:925' fillcolor="red"/> <v:oval id="_x0000_s1033" style='position:absolute;left:7578;top:3991;width:462;  height:1150' fillcolor="#36f"/> <v:line id="_x0000_s1034" style='position:absolute;flip:y' from="5446,4609"  to="5983,4609">  <v:stroke endarrow="block"/> </v:line><w:wrap type="none"/> <w:anchorlock/></v:group><![endif]--><!-- [if !vml]--><img decoding="async" width="422" height="149" data-src="file:///C:/Users/Cindy/AppData/Local/Temp/msohtmlclip1/01/clip_image001.gif" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

  <noscript>

   <img decoding="async" src="file:///C:/Users/Cindy/AppData/Local/Temp/msohtmlclip1/01/clip_image001.gif" width="422" height="149">

  </noscript><!--[endif]--></span><!-- [if mso & !supportInlineShapes & supportFields]><spanlang=EN-US style='font-size:11.0pt'><v:shape id="_x0000_i1025" type="#_x0000_t75" style='width:315.8pt;height:110.75pt'> <v:imagedata croptop="-65520f" cropbottom="65520f"/></v:shape><span style='mso-element:field-end'></span></span><![endif]-->

<p class="MsoNormal" style="margin-left: 18.0pt; mso-outline-level: 1;"><span lang="EN-US" style="font-size: 11.0pt;"> </span>

<p class="MsoNormal" style="margin-left: 18.0pt; mso-outline-level: 1;"><span lang="EN-US" style="font-size: 11.0pt;"> </span>

<p class="MsoNormal" style="margin-left: 18.0pt; mso-outline-level: 1;"><span lang="EN-US" style="font-size: 11.0pt;"> </span>

<p class="MsoNormal" style="margin-left: 18.0pt; mso-outline-level: 1;"><span lang="EN-US" style="font-size: 11.0pt;"> </span>

<ol style="margin-top: 0cm;" start="2" type="1">

 <li class="MsoNormal" style="mso-outline-level: 1; mso-list: l1 level1 lfo2; tab-stops: list 36.0pt;"><span lang="EN-US" style="font-size: 11.0pt;">(8%) Given a sorted array of distinct integers A[1, …, n], you want to find out whether there is an index i for which A[i]=i. Give a divide-and-conquer algorithm to solve this problem. Derive the time complexity. (Note: the running time much be less than O(n)).</span></li>

</ol>

<p class="MsoNormal" style="margin-left: 18.0pt; mso-outline-level: 1;"><span lang="EN-US" style="font-size: 11.0pt;"> </span>

<p class="MsoNormal" style="margin-left: 18.0pt; mso-outline-level: 1;"><span lang="EN-US" style="font-size: 11.0pt;"> </span>

<p class="MsoNormal" style="margin-left: 18.0pt; text-align: justify; line-height: 150%;"><span lang="EN-US" style="font-size: 11.0pt; mso-bidi-font-size: 12.0pt; line-height: 150%;">3. [10%] Write a piece of pseudo-code to plot the following graph. Assuming that the plotting function has been provided as DrawSquare(x, y, r), which draw a square of size 2r with center (x, y). </span>

<p class="MsoNormal" style="margin-left: 18.0pt; text-align: justify; line-height: 150%;"><span lang="EN-US" style="font-size: 11.0pt; mso-bidi-font-size: 12.0pt; line-height: 150%;">(1) Pseudo-Code to plot following graph. (4%)</span>

<p class="MsoNormal" style="margin-left: 18.0pt; text-align: justify; line-height: 150%;"><span lang="EN-US" style="font-size: 11.0pt; mso-bidi-font-size: 12.0pt; line-height: 150%;">(2) Write the recurrence equation for your algorithm. (3%) </span>

<p class="MsoNormal" style="margin-left: 18.0pt; text-align: justify; line-height: 150%;"><span lang="EN-US" style="font-size: 11.0pt; mso-bidi-font-size: 12.0pt; line-height: 150%;">(3) Plot the recursion tree to derive the solution of T(r). (3%) </span>

<p class="MsoNormal" style="margin-left: 18.0pt; text-align: justify; line-height: 150%;"><span lang="EN-US" style="font-size: 11.0pt; mso-bidi-font-size: 12.0pt; line-height: 150%;">(Note: r is the input size, which is the power of 2. The time complexity for drawing one square is O(1)). (Hint: The input of function can be: int x, int y, int r)</span>

<p class="MsoNormal" style="margin-left: 18.0pt; text-align: justify; line-height: 150%;"><span lang="EN-US" style="font-size: 11.0pt; mso-bidi-font-size: 12.0pt; line-height: 150%;"> </span>

<p class="MsoNormal" style="text-align: justify; line-height: 150%;"><!-- [if gte vml 1]><v:rect id="_x0000_s1038" style='position:absolute;left:0;text-align:left; margin-left:112.2pt;margin-top:75.55pt;width:74.8pt;height:74.8pt;z-index:251646464' filled="f" fillcolor="yellow" strokecolor="blue"/><v:rect id="_x0000_s1040" style='position:absolute;left:0;text-align:left;margin-left:168.3pt; margin-top:133.05pt;width:36pt;height:36pt;z-index:251648512' filled="f" fillcolor="yellow"/><v:rect id="_x0000_s1042" style='position:absolute;left:0; text-align:left;margin-left:93.5pt;margin-top:133.05pt;width:36pt;height:36pt; z-index:251650560' filled="f" fillcolor="yellow"/><v:rect id="_x0000_s1043" style='position:absolute;left:0;text-align:left;margin-left:168.3pt; margin-top:56.85pt;width:36pt;height:36pt;z-index:251651584' filled="f" fillcolor="yellow"/><v:rect id="_x0000_s1055" style='position:absolute;left:0; text-align:left;margin-left:94.9pt;margin-top:56.85pt;width:36pt;height:36pt; z-index:251663872' filled="f" fillcolor="yellow"/><v:line id="_x0000_s1056" style='position:absolute;left:0;text-align:left;z-index:251664896' from="220.15pt,16.05pt" to="220.9pt,323.05pt"> <v:stroke dashstyle="dash"/></v:line><v:line id="_x0000_s1058" style='position:absolute;left:0; text-align:left;z-index:251666944' from="188.25pt,25.7pt" to="220.5pt,25.7pt"> <v:stroke endarrow="block"/></v:line><v:rect id="_x0000_s1035" style='position:absolute;left:0; text-align:left;margin-left:261.8pt;margin-top:75.55pt;width:74.8pt;height:74.8pt; z-index:251643392' filled="f" fillcolor="yellow" strokecolor="blue"/><v:rect id="_x0000_s1048" style='position:absolute;left:0;text-align:left; margin-left:317.9pt;margin-top:133.05pt;width:36pt;height:36pt;z-index:251656704' filled="f" fillcolor="yellow"/><v:rect id="_x0000_s1049" style='position:absolute; left:0;text-align:left;margin-left:243.1pt;margin-top:133.05pt;width:36pt; height:36pt;z-index:251657728' filled="f" fillcolor="yellow"/><v:rect id="_x0000_s1050" style='position:absolute;left:0;text-align:left;margin-left:317.9pt; margin-top:56.85pt;width:36pt;height:36pt;z-index:251658752' filled="f" fillcolor="yellow"/><v:rect id="_x0000_s1051" style='position:absolute;left:0; text-align:left;margin-left:243.1pt;margin-top:56.85pt;width:36pt;height:36pt; z-index:251659776' filled="f" fillcolor="yellow"/><v:line id="_x0000_s1057" style='position:absolute;left:0;text-align:left;z-index:251665920' from="298.15pt,16.05pt" to="298.15pt,110.05pt"> <v:stroke dashstyle="dash"/></v:line><v:line id="_x0000_s1059" style='position:absolute;left:0; text-align:left;flip:x;z-index:251667968' from="297.75pt,25.7pt" to="334.5pt,25.7pt"> <v:stroke endarrow="block"/></v:line><v:shapetype id="_x0000_t202" coordsize="21600,21600" o:spt="202" path="m,l,21600r21600,l21600,xe"> <v:stroke joinstyle="miter"/> <v:path gradientshapeok="t" o:connecttype="rect"/></v:shapetype><v:shape id="_x0000_s1060" type="#_x0000_t202" style='position:absolute; left:0;text-align:left;margin-left:246pt;margin-top:13.7pt;width:22.5pt; height:25.5pt;z-index:251668992' stroked="f"> <v:textbox>  <![if !mso]><table cellpadding=0 cellspacing=0 width="100%"><tr><td><![endif]><div><p class=MsoNormal><span lang=EN-US style='font-size:14.0pt'>r<o:p></o:p></span></div><![if !mso]></td></tr></table><![endif]></v:textbox></v:shape><![endif]--><!-- [if !vml]-->

<table cellspacing="0" cellpadding="0" align="left">

 <tbody>

  <tr>

   <td width="124" height="19"></td>

   <td width="172"></td>

   <td width="27"></td>

   <td width="150"></td>

  </tr>

  <tr>

   <td height="4"></td>

   <td colspan="2"></td>

   <td rowspan="2" align="left" valign="top"><img decoding="async" width="150" height="210" data-src="file:///C:/Users/Cindy/AppData/Local/Temp/msohtmlclip1/01/clip_image002.gif" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

    <noscript>

     <img decoding="async" src="file:///C:/Users/Cindy/AppData/Local/Temp/msohtmlclip1/01/clip_image002.gif" width="150" height="210">

    </noscript></td>

  </tr>

  <tr>

   <td height="206"></td>

   <td rowspan="2" align="left" valign="top"><img decoding="async" width="172" height="411" data-src="file:///C:/Users/Cindy/AppData/Local/Temp/msohtmlclip1/01/clip_image003.gif" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

    <noscript>

     <img decoding="async" src="file:///C:/Users/Cindy/AppData/Local/Temp/msohtmlclip1/01/clip_image003.gif" width="172" height="411">

    </noscript></td>

  </tr>

  <tr>

   <td height="205"></td>

  </tr>

 </tbody>

</table>

<!--[endif]--><span lang="EN-US" style="font-size: 11.0pt; mso-bidi-font-size: 12.0pt; line-height: 150%;"> </span>




<p class="MsoNormal" style="text-align: justify; line-height: 150%;"><span lang="EN-US" style="font-size: 11.0pt; mso-bidi-font-size: 12.0pt; line-height: 150%;"> </span>

<p class="MsoNormal" style="text-align: justify; line-height: 150%;"><span lang="EN-US" style="font-size: 11.0pt; mso-bidi-font-size: 12.0pt; line-height: 150%;"> </span>




<p class="MsoNormal" style="text-align: justify; line-height: 150%;"><span lang="EN-US" style="font-size: 11.0pt; mso-bidi-font-size: 12.0pt; line-height: 150%;"><span style="mso-spacerun: yes;">   </span></span>

<p class="MsoNormal" style="text-align: justify; line-height: 150%;"><span lang="EN-US" style="font-size: 11.0pt; mso-bidi-font-size: 12.0pt; line-height: 150%;"> </span>

<p class="MsoNormal" style="text-align: justify; line-height: 150%;"><!-- [if gte vml 1]><v:rect id="_x0000_s1036" style='position:absolute;left:0;text-align:left; margin-left:149.6pt;margin-top:15.5pt;width:149.6pt;height:149.6pt;z-index:251644416' filled="f" strokecolor="red"/><![endif]--><!-- [if !vml]-->

<table cellspacing="0" cellpadding="0" align="left">

 <tbody>

  <tr>

   <td width="198" height="20"></td>

  </tr>

  <tr>

   <td></td>

   <td><img decoding="async" width="202" height="201" data-src="file:///C:/Users/Cindy/AppData/Local/Temp/msohtmlclip1/01/clip_image004.gif" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

    <noscript>

     <img decoding="async" src="file:///C:/Users/Cindy/AppData/Local/Temp/msohtmlclip1/01/clip_image004.gif" width="202" height="201">

    </noscript></td>

  </tr>

 </tbody>

</table>

<!--[endif]--><span lang="EN-US" style="font-size: 11.0pt; mso-bidi-font-size: 12.0pt; line-height: 150%;"> </span>







<p class="MsoNormal" style="text-align: justify; line-height: 150%;"><span lang="EN-US" style="font-size: 11.0pt; mso-bidi-font-size: 12.0pt; line-height: 150%;"><span style="mso-spacerun: yes;">                </span></span>

<p class="MsoNormal" style="text-align: justify; line-height: 150%;"><span lang="EN-US" style="font-size: 11.0pt; mso-bidi-font-size: 12.0pt; line-height: 150%;"> </span>

<p class="MsoNormal" style="text-align: justify; line-height: 150%;"><!-- [if gte vml 1]><v:shape id="_x0000_s1062" type="#_x0000_t202" style='position:absolute;left:0; text-align:left;margin-left:205.5pt;margin-top:17.15pt;width:30pt;height:24pt; z-index:251671040' stroked="f"/><![endif]--><!-- [if !vml]-->

<table cellspacing="0" cellpadding="0" align="left">

 <tbody>

  <tr>

   <td width="274" height="23"></td>

  </tr>

  <tr>

   <td></td>

   <td style="vertical-align: top; background: white;" bgcolor="white" width="44" height="36"><!--[endif]--><!-- [if !mso]-->

    <table width="100%" cellspacing="0" cellpadding="0">

     <tbody>

      <tr>

       <td><!--[endif]--><!-- [if !mso]--></td>

      </tr>

     </tbody>

    </table><!--[endif]--><!-- [if !mso & !vml]--> <!--[endif]--><!-- [if !vml]--></td>

  </tr>

 </tbody>

</table>

<!--[endif]--><span lang="EN-US" style="font-size: 11.0pt; mso-bidi-font-size: 12.0pt; line-height: 150%;"> </span>







<p class="MsoNormal" style="text-align: justify; line-height: 150%;"><!-- [if gte vml 1]><v:line id="_x0000_s1061" style='position:absolute;left:0;text-align:left;z-index:251670016' from="30pt,11.7pt" to="445.5pt,11.7pt"> <v:stroke dashstyle="dash"/></v:line><![endif]--><!-- [if !vml]--><span style="mso-ignore: vglayout; position: absolute; z-index: 251670016; left: 0px; margin-left: 39px; margin-top: 15px; width: 556px; height: 2px;"><img decoding="async" width="556" height="2" data-src="file:///C:/Users/Cindy/AppData/Local/Temp/msohtmlclip1/01/clip_image005.gif" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

  <noscript>

   <img decoding="async" src="file:///C:/Users/Cindy/AppData/Local/Temp/msohtmlclip1/01/clip_image005.gif" width="556" height="2">

  </noscript></span><!--[endif]--><span lang="EN-US" style="font-size: 11.0pt; mso-bidi-font-size: 12.0pt; line-height: 150%;"><span style="mso-spacerun: yes;">                                                                              </span></span>

<p class="MsoNormal" style="text-align: justify; line-height: 150%;"><!-- [if gte vml 1]><v:rect id="_x0000_s1052" style='position:absolute;left:0;text-align:left; margin-left:243.1pt;margin-top:14.15pt;width:36pt;height:36pt;z-index:251660800' filled="f" fillcolor="yellow"/><![endif]--><!-- [if !vml]--><span style="mso-ignore: vglayout; position: absolute; z-index: 251660800; left: 0px; margin-left: 323px; margin-top: 17px; width: 50px; height: 50px;"><img decoding="async" width="50" height="50" data-src="file:///C:/Users/Cindy/AppData/Local/Temp/msohtmlclip1/01/clip_image006.gif" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

  <noscript>

   <img decoding="async" src="file:///C:/Users/Cindy/AppData/Local/Temp/msohtmlclip1/01/clip_image006.gif" width="50" height="50">

  </noscript></span><!--[endif]--><!-- [if gte vml 1]><v:rect id="_x0000_s1045" style='position:absolute;left:0;text-align:left;margin-left:168.3pt; margin-top:14.15pt;width:36pt;height:36pt;z-index:251653632' filled="f" fillcolor="yellow"/><![endif]--><!-- [if !vml]--><span style="mso-ignore: vglayout; position: absolute; z-index: 251653632; left: 0px; margin-left: 223px; margin-top: 17px; width: 50px; height: 50px;"><img decoding="async" width="50" height="50" data-src="file:///C:/Users/Cindy/AppData/Local/Temp/msohtmlclip1/01/clip_image007.gif" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

  <noscript>

   <img decoding="async" src="file:///C:/Users/Cindy/AppData/Local/Temp/msohtmlclip1/01/clip_image007.gif" width="50" height="50">

  </noscript></span><!--[endif]--><!-- [if gte vml 1]><v:rect id="_x0000_s1044" style='position:absolute;left:0;text-align:left;margin-left:93.5pt; margin-top:14.15pt;width:36pt;height:36pt;z-index:251652608' filled="f" fillcolor="yellow"/><![endif]--><!-- [if !vml]--><span style="mso-ignore: vglayout; position: absolute; z-index: 251652608; left: 0px; margin-left: 124px; margin-top: 17px; width: 50px; height: 50px;"><img decoding="async" width="50" height="50" data-src="file:///C:/Users/Cindy/AppData/Local/Temp/msohtmlclip1/01/clip_image008.gif" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

  <noscript>

   <img decoding="async" src="file:///C:/Users/Cindy/AppData/Local/Temp/msohtmlclip1/01/clip_image008.gif" width="50" height="50">

  </noscript></span><!--[endif]--><!-- [if gte vml 1]><v:rect id="_x0000_s1041" style='position:absolute;left:0;text-align:left;margin-left:317.9pt; margin-top:14.15pt;width:36pt;height:36pt;z-index:251649536' filled="f" fillcolor="yellow"/><![endif]--><!-- [if !vml]--><span style="mso-ignore: vglayout; position: absolute; z-index: 251649536; left: 0px; margin-left: 423px; margin-top: 17px; width: 50px; height: 50px;"><img decoding="async" width="50" height="50" data-src="file:///C:/Users/Cindy/AppData/Local/Temp/msohtmlclip1/01/clip_image009.gif" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

  <noscript>

   <img decoding="async" src="file:///C:/Users/Cindy/AppData/Local/Temp/msohtmlclip1/01/clip_image009.gif" width="50" height="50">

  </noscript></span><!--[endif]--><span lang="EN-US" style="font-size: 11.0pt; mso-bidi-font-size: 12.0pt; line-height: 150%;"><span style="mso-spacerun: yes;">                                                                              </span></span><!-- [if gte vml 1]><v:rect id="_x0000_s1037" style='position:absolute; left:0;text-align:left;margin-left:261.8pt;margin-top:13.85pt;width:74.8pt; height:74.8pt;z-index:251645440;mso-position-horizontal-relative:text; mso-position-vertical-relative:text' filled="f" fillcolor="yellow" strokecolor="blue"/><![endif]--><!-- [if !vml]--><span style="mso-ignore: vglayout; position: absolute; z-index: 251645440; left: 0px; margin-left: 348px; margin-top: 17px; width: 102px; height: 102px;"><img decoding="async" width="102" height="102" data-src="file:///C:/Users/Cindy/AppData/Local/Temp/msohtmlclip1/01/clip_image010.gif" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

  <noscript>

   <img decoding="async" src="file:///C:/Users/Cindy/AppData/Local/Temp/msohtmlclip1/01/clip_image010.gif" width="102" height="102">

  </noscript></span><!--[endif]--><!-- [if gte vml 1]><v:rect id="_x0000_s1046" style='position:absolute;left:0;text-align:left;margin-left:168.3pt; margin-top:72.3pt;width:36pt;height:36pt;z-index:251654656' filled="f" fillcolor="yellow"/><v:rect id="_x0000_s1053" style='position:absolute;left:0; text-align:left;margin-left:317.9pt;margin-top:72.3pt;width:36pt;height:36pt; z-index:251661824' filled="f" fillcolor="yellow"/><v:rect id="_x0000_s1054" style='position:absolute;left:0;text-align:left;margin-left:243.1pt; margin-top:72.3pt;width:36pt;height:36pt;z-index:251662848' filled="f" fillcolor="yellow"/><v:rect id="_x0000_s1047" style='position:absolute;left:0; text-align:left;margin-left:93.5pt;margin-top:72.3pt;width:36pt;height:36pt; z-index:251655680' filled="f" fillcolor="yellow"/><![endif]--><!-- [if !vml]-->

<table cellspacing="0" cellpadding="0" align="left">

 <tbody>

  <tr>

   <td width="124" height="16"></td>

   <td width="50"></td>

   <td width="49"></td>

   <td width="50"></td>

   <td width="50"></td>

   <td width="50"></td>

   <td width="50"></td>

   <td width="50"></td>

  </tr>

  <tr>

   <td height="50"></td>

   <td align="left" valign="top"><img decoding="async" width="50" height="50" data-src="file:///C:/Users/Cindy/AppData/Local/Temp/msohtmlclip1/01/clip_image011.gif" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

    <noscript>

     <img decoding="async" src="file:///C:/Users/Cindy/AppData/Local/Temp/msohtmlclip1/01/clip_image011.gif" width="50" height="50">

    </noscript></td>

   <td></td>

   <td align="left" valign="top"><img decoding="async" width="50" height="50" data-src="file:///C:/Users/Cindy/AppData/Local/Temp/msohtmlclip1/01/clip_image012.gif" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

    <noscript>

     <img decoding="async" src="file:///C:/Users/Cindy/AppData/Local/Temp/msohtmlclip1/01/clip_image012.gif" width="50" height="50">

    </noscript></td>

   <td></td>

   <td align="left" valign="top"><img decoding="async" width="50" height="50" data-src="file:///C:/Users/Cindy/AppData/Local/Temp/msohtmlclip1/01/clip_image013.gif" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

    <noscript>

     <img decoding="async" src="file:///C:/Users/Cindy/AppData/Local/Temp/msohtmlclip1/01/clip_image013.gif" width="50" height="50">

    </noscript></td>

   <td></td>

   <td align="left" valign="top"><img decoding="async" width="50" height="50" data-src="file:///C:/Users/Cindy/AppData/Local/Temp/msohtmlclip1/01/clip_image014.gif" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

    <noscript>

     <img decoding="async" src="file:///C:/Users/Cindy/AppData/Local/Temp/msohtmlclip1/01/clip_image014.gif" width="50" height="50">

    </noscript></td>

  </tr>

 </tbody>

</table>

<!--[endif]--><!-- [if gte vml 1]><v:rect id="_x0000_s1039" style='position:absolute; left:0;text-align:left;margin-left:112.2pt;margin-top:13.85pt;width:74.8pt; height:74.8pt;z-index:251647488;mso-position-horizontal-relative:text; mso-position-vertical-relative:text' filled="f" fillcolor="yellow" strokecolor="blue"/><![endif]--><!-- [if !vml]--><span style="mso-ignore: vglayout; position: absolute; z-index: 251647488; left: 0px; margin-left: 149px; margin-top: 17px; width: 101px; height: 102px;"><img decoding="async" width="101" height="102" data-src="file:///C:/Users/Cindy/AppData/Local/Temp/msohtmlclip1/01/clip_image015.gif" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

  <noscript>

   <img decoding="async" src="file:///C:/Users/Cindy/AppData/Local/Temp/msohtmlclip1/01/clip_image015.gif" width="101" height="102">

  </noscript></span><!--[endif]-->




<p class="MsoNormal" style="text-align: justify; line-height: 150%;"><span lang="EN-US" style="font-size: 11.0pt; mso-bidi-font-size: 12.0pt; line-height: 150%;"> </span>

<p class="MsoNormal" style="text-align: justify; line-height: 150%;"><span lang="EN-US" style="font-size: 11.0pt; mso-bidi-font-size: 12.0pt; line-height: 150%;"> </span>

<p class="MsoNormal" style="text-align: justify; line-height: 150%;"><span lang="EN-US" style="font-size: 11.0pt; mso-bidi-font-size: 12.0pt; line-height: 150%;"> </span>

<p class="MsoNormal" style="text-align: justify; line-height: 150%;"><span lang="EN-US" style="font-size: 11.0pt; mso-bidi-font-size: 12.0pt; line-height: 150%;"> </span>

<p class="MsoNormal" style="text-align: justify; line-height: 150%;"><span lang="EN-US" style="font-size: 11.0pt; mso-bidi-font-size: 12.0pt; line-height: 150%;"> </span>




<p class="MsoNormal" style="margin-left: 18.0pt; text-align: justify; text-indent: -18.0pt; line-height: 150%; tab-stops: list 18.0pt;"><span lang="EN-US" style="font-size: 11.0pt; mso-bidi-font-size: 12.0pt; line-height: 150%; mso-bidi-font-style: italic;"><span style="mso-spacerun: yes;"> </span></span>

<p class="MsoNormal" style="mso-outline-level: 1;"><span lang="EN-US" style="font-size: 11.0pt;"> </span>

<ol style="margin-top: 0cm;" start="4" type="1">

 <li class="MsoNormal" style="mso-outline-level: 1; mso-list: l6 level1 lfo5; tab-stops: list 36.0pt;"><span lang="EN-US" style="font-size: 11.0pt;">(9%) An Array A[1,…,n] is said to have a majority element if more than half of its entries are the same. Given an array, the task is to design an efficient algorithm to tell whether the array has a majority element, and, if so, to find that element. Show how to solve this problem in O(nlgn) time.(Hint: Split the array A into two arrays A1 and A2 of half the size. Does knowing the majority elements of A1 and A2 help you figure out the majority element of A?) Note that it is required to use a divide-and-conquer approach with O(nlgn) time complexity.</span></li>

</ol>

<p class="MsoNormal" style="mso-outline-level: 1;"><span lang="DE" style="font-size: 11.0pt; mso-ansi-language: DE;"> </span>

<ol style="margin-top: 0cm;" start="5" type="1">

 <li class="MsoNormal" style="mso-outline-level: 1; mso-list: l6 level1 lfo5; tab-stops: list 36.0pt;"><span lang="EN-US">(6%) Suppose you are choosing between the following three algorithms:</span></li>

</ol>

<p class="MsoNormal" style="margin-left: 19.8pt; text-indent: 7.2pt; mso-outline-level: 1; mso-list: l2 level1 lfo3; tab-stops: list 45.0pt;"><!-- [if !supportLists]--><span lang="EN-US" style="font-family: Symbol; mso-fareast-font-family: Symbol; mso-bidi-font-family: Symbol;"><span style="mso-list: Ignore;">·<span style="font: 7.0pt 'Times New Roman';">         </span></span></span><!--[endif]--><span lang="EN-US">Algorithm A solves<span style="mso-spacerun: yes;">  </span>problems by dividing them into five sub-problems of half size, recursively solving each sub-problem, and then combining the solutions in linear time.</span>

<p class="MsoNormal" style="margin-left: 19.8pt; text-indent: 7.2pt; mso-outline-level: 1; mso-list: l2 level1 lfo3; tab-stops: list 45.0pt;"><!-- [if !supportLists]--><span lang="EN-US" style="font-family: Symbol; mso-fareast-font-family: Symbol; mso-bidi-font-family: Symbol;"><span style="mso-list: Ignore;">·<span style="font: 7.0pt 'Times New Roman';">         </span></span></span><!--[endif]--><span lang="EN-US">Algorithm B solves problems of size n by recursively solving two sub-problems of size n-1 and then combining the solutions in constant time.</span>

<p class="MsoNormal" style="margin-left: 19.8pt; text-indent: 7.2pt; mso-outline-level: 1; mso-list: l2 level1 lfo3; tab-stops: list 45.0pt;"><!-- [if !supportLists]--><span lang="EN-US" style="font-family: Symbol; mso-fareast-font-family: Symbol; mso-bidi-font-family: Symbol;"><span style="mso-list: Ignore;">·<span style="font: 7.0pt 'Times New Roman';">         </span></span></span><!--[endif]--><span lang="EN-US">Algorithm C solves problems of size n by dividing them into nine sub-problems of size n/3, recursively solving each sub-problem, and then combining the solutions in O(n<sup>2</sup>) time.</span>

<p class="MsoNormal" style="margin-left: 72.0pt; text-align: justify; line-height: 150%;"><span lang="EN-US" style="font-size: 11.0pt; mso-bidi-font-size: 12.0pt; line-height: 150%; mso-bidi-font-style: italic;"> </span>

<p class="MsoNormal" style="margin-left: 19.8pt; text-align: justify; line-height: 150%;"><span lang="EN-US" style="font-size: 11.0pt; mso-bidi-font-size: 12.0pt; line-height: 150%; mso-bidi-font-style: italic;">What are the running times of each of these algorithms (in big-O notation), and which would you choose</span><span lang="EN-US" style="font-size: 11.0pt; mso-bidi-font-size: 12.0pt; line-height: 150%; color: windowtext; mso-bidi-font-style: italic;">?<span style="mso-spacerun: yes;">  </span><u>(Note: strategy for solving the problem and its sub-problems is same). </u></span>

<p class="MsoList" style="text-indent: -18.0pt; mso-list: l6 level1 lfo5; tab-stops: list 36.0pt;"><!-- [if !supportLists]--><span lang="EN-US"><span style="mso-list: Ignore;">6.<span style="font: 7.0pt 'Times New Roman';">      </span></span></span><!--[endif]--><span lang="EN-US"><span style="mso-spacerun: yes;"> </span>[10%]</span>

<p class="MsoList" style="margin-left: 72.0pt; text-indent: -18.0pt; mso-list: l6 level2 lfo5; tab-stops: list 72.0pt;"><!-- [if !supportLists]--><i><span lang="EN-US"><span style="mso-list: Ignore;">a.<span style="font: 7.0pt 'Times New Roman';">      </span></span></span></i><!--[endif]--><span lang="EN-US">[3%]Write the recurrence equation for the code below. Use the number of comparisons as your barometer operation (The <i style="mso-bidi-font-style: normal;">min</i> operation requires 1 comparison and the <i style="mso-bidi-font-style: normal;">max</i> operation requires 1 comparison): <i>):<span style="mso-spacerun: yes;">  </span>(Note: you can count min and max as the comparison operation and skip the rt-lt &lt;=1)</i></span>

<p class="MsoList" style="mso-list: none;"><span lang="EN-US"> </span>

<p class="code"><span lang="EN-US"><span style="mso-spacerun: yes;">                </span>MinMax(A,lt,rt)<span style="mso-spacerun: yes;">  </span></span>

<p class="code"><span lang="EN-US"><span style="mso-spacerun: yes;">                </span>// return a pair with the minimum and the maximum</span>

<p class="code"><span lang="EN-US"><span style="mso-spacerun: yes;">                   </span>if (rt – lt </span><span lang="EN-US" style="font-family: Symbol;">£</span><span lang="EN-US"> 1)</span>

<p class="code"><span lang="EN-US"><span style="mso-spacerun: yes;">                       </span>return (min(A[lt], A[rt]), max(A[lt],A[rt]));</span>

<p class="code"><span lang="EN-US"><span style="mso-spacerun: yes;">                   </span>(min1, max1) = MinMax(A,lt, </span><span lang="EN-US" style="font-family: Symbol;">ë</span><span lang="EN-US">(lt+rt)/2</span><span lang="EN-US" style="font-family: Symbol;">û</span><span lang="EN-US"> );</span>

<p class="code"><span lang="EN-US"><span style="mso-spacerun: yes;">                   </span>(min2, max2) = MinMax(A, </span><span lang="EN-US" style="font-family: Symbol;">ë</span><span lang="EN-US"> (lt+rt)/2</span><span lang="EN-US" style="font-family: Symbol;"> û</span><span lang="EN-US"> +1,rt);</span>

<p class="code"><span lang="EN-US"><span style="mso-spacerun: yes;">                   </span>return (min (min1, min2), max(max1, max2));</span>

<p class="MsoList" style="margin-left: 72.0pt; text-indent: -18.0pt; mso-list: l6 level2 lfo5; tab-stops: list 72.0pt;"><!-- [if !supportLists]--><span lang="EN-US"><span style="mso-list: Ignore;">b.<span style="font: 7.0pt 'Times New Roman';">      </span></span></span><!--[endif]--><span lang="EN-US">[4%] Show the recursion tree and solve the recurrence equation for this code. For simplicity assume n = 2<i><sup>k</sup></i>. </span>

<ol style="margin-top: 0cm;" start="6" type="1">

 <li style="list-style-type: none">

  <ol style="margin-top: 0cm;" start="3" type="a">

   <li class="MsoNormal" style="mso-outline-level: 1; mso-list: l6 level2 lfo5; tab-stops: list 72.0pt;"><span lang="EN-US" style="font-family: 'Arial',sans-serif;">[3%] Prove the solution using induction</span></li>

  </ol></li>

</ol>

<p class="MsoNormal" style="mso-outline-level: 1;"><span lang="EN-US" style="font-family: 'Arial',sans-serif;"> </span>

<ol style="margin-top: 0cm;" start="7" type="1">

 <li class="MsoNormal" style="mso-outline-level: 1; mso-list: l6 level1 lfo5; tab-stops: list 36.0pt;"><span lang="EN-US" style="font-family: 'Arial',sans-serif;">[5%] Find the asymptotic bound of the divide and conquer recurrence T(n) using master method: (1) T(n)=16T(n/4)+n^4+3;</span></li>

</ol>

<p class="MsoNormal" style="mso-outline-level: 1;"><span lang="EN-US" style="font-family: 'Arial',sans-serif;"> </span>

<ol style="margin-top: 0cm;" start="8" type="1">

 <li class="MsoNormal" style="mso-outline-level: 1; mso-list: l6 level1 lfo5; tab-stops: list 36.0pt;"><span lang="EN-US" style="font-family: 'Arial',sans-serif;">[5%] Solve the following recurrence equation using methods of characteristic equation. </span></li>

</ol>

<p class="MsoNormal" style="mso-outline-level: 1;"><span lang="EN-US" style="font-family: 'Arial',sans-serif;"> </span>

<p class="MsoNormal" style="mso-outline-level: 1;"><span lang="EN-US" style="font-family: 'Arial',sans-serif;">T(n)=5T(n-1)-8T(n-2)+4T(n-3) for n&gt;2</span>

<p class="MsoNormal" style="mso-outline-level: 1;"><span lang="EN-US" style="font-family: 'Arial',sans-serif;">T(0)=0</span>

<p class="MsoNormal" style="mso-outline-level: 1;"><span lang="EN-US" style="font-family: 'Arial',sans-serif;">T(1)=1</span>

<p class="MsoNormal" style="mso-outline-level: 1;"><span lang="EN-US" style="font-family: 'Arial',sans-serif;">T(2)=2</span>

<p class="MsoNormal" style="margin-left: 18.0pt; text-align: justify; text-indent: -18.0pt; line-height: 150%; tab-stops: list 18.0pt;"><i style="mso-bidi-font-style: normal;"><span lang="EN-US" style="font-size: 11.0pt; mso-bidi-font-size: 12.0pt; line-height: 150%;">Hint: if there are two same roots, the solution template is T(n) = C1*r1^n + C2*r2^n + C3*n*r3^n</span></i>

<p class="MsoNormal" style="margin-left: 13.5pt; text-indent: -13.5pt; mso-outline-level: 1; mso-list: l6 level1 lfo5; tab-stops: list 31.5pt;"><!-- [if !supportLists]--><span lang="EN-US" style="font-family: 'Arial',sans-serif; mso-fareast-font-family: Arial;"><span style="mso-list: Ignore;">9.<span style="font: 7.0pt 'Times New Roman';">  </span></span></span><!--[endif]--><span lang="EN-US" style="font-family: 'Arial',sans-serif;">(9%)</span>

<p class="MsoNormal" style="mso-outline-level: 1;"><span lang="EN-US" style="font-family: 'Arial',sans-serif;"><!-- [if gte vml 1]><v:shape id="_x0000_i1026" type="#_x0000_t75" style='width:318.75pt;height:196.5pt' o:ole=""> <v:imagedata src="file:///C:/Users/Cindy/AppData/Local/Temp/msohtmlclip1/01/clip_image016.emz"  o:title=""/></v:shape><![endif]--><!-- [if !vml]--><img decoding="async" width="425" height="262" data-src="file:///C:/Users/Cindy/AppData/Local/Temp/msohtmlclip1/01/clip_image017.gif" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

  <noscript>

   <img decoding="async" src="file:///C:/Users/Cindy/AppData/Local/Temp/msohtmlclip1/01/clip_image017.gif" width="425" height="262">

  </noscript><!--[endif]--><!-- [if gte mso 9]><xml> <o:OLEObject Type="Embed" ProgID="AcroExch.Document.11" ShapeID="_x0000_i1026"  DrawAspect="Content" ObjectID="_1709471059"> </o:OLEObject></xml><![endif]--></span>

<p class="MsoNormal" style="mso-outline-level: 1;"><span lang="EN-US" style="font-family: 'Arial',sans-serif;"> </span>

<p class="MsoNormal" style="mso-outline-level: 1;"><span lang="EN-US" style="font-family: 'Arial',sans-serif;"> </span>

<p class="MsoNormal" style="margin-left: 36.0pt; text-indent: -18.0pt; mso-outline-level: 1; mso-list: l5 level1 lfo6;"><!-- [if !supportLists]--><span lang="EN-US" style="font-family: 'Arial',sans-serif; mso-fareast-font-family: Arial;"><span style="mso-list: Ignore;">(1)<span style="font: 7.0pt 'Times New Roman';">  </span></span></span><!--[endif]--><span lang="EN-US" style="font-family: 'Arial',sans-serif;">What is the time complexity of the above algorithm; (2%)</span>

<p class="MsoNormal" style="margin-left: 36.0pt; text-indent: -18.0pt; mso-outline-level: 1; mso-list: l5 level1 lfo6;"><!-- [if !supportLists]--><span lang="EN-US" style="font-family: 'Arial',sans-serif; mso-fareast-font-family: Arial;"><span style="mso-list: Ignore;">(2)<span style="font: 7.0pt 'Times New Roman';">  </span></span></span><!--[endif]--><span lang="EN-US" style="font-family: 'Arial',sans-serif;">Improve the above algorithm with an asymptotically better running time. Show your algorithm, and the time complexity (4%)</span>

<p class="MsoNormal" style="margin-left: 36.0pt; text-indent: -18.0pt; mso-outline-level: 1; mso-list: l5 level1 lfo6;"><!-- [if !supportLists]--><span lang="EN-US" style="font-family: 'Arial',sans-serif; mso-fareast-font-family: Arial;"><span style="mso-list: Ignore;">(3)<span style="font: 7.0pt 'Times New Roman';">  </span></span></span><!--[endif]--><span lang="EN-US" style="font-family: 'Arial',sans-serif;">Proof of correctness of your algorithm (3%)</span>

<p class="MsoNormal" style="mso-outline-level: 1;"><span lang="EN-US" style="font-family: 'Arial',sans-serif;"> </span>

<p class="MsoNormal" style="margin-left: 36.0pt; text-indent: -18.0pt; mso-outline-level: 1; mso-list: l3 level1 lfo7;"><!-- [if !supportLists]--><span lang="EN-US" style="font-size: 11.0pt;"><span style="mso-list: Ignore;">10<span style="font: 7.0pt 'Times New Roman';">     </span></span></span><!--[endif]--><span lang="EN-US" style="font-size: 11.0pt;">(8%) Design an algorithm for visible lines detection:<span style="mso-spacerun: yes;">  </span>Given <i style="mso-bidi-font-style: normal;">n</i> non-vertical lines in a plane, labeled <i style="mso-bidi-font-style: normal;">L1…., Ln</i>, with line equation <i style="mso-bidi-font-style: normal;">y=ai*x +bi (i=1, …n).</i> We can make an assumption that no three of the lines all meet at a single point.<span style="mso-spacerun: yes;">  </span></span>

<p class="MsoListParagraph"><span lang="EN-US" style="font-size: 11.0pt;"> </span>

<p class="MsoNormal" style="text-align: justify; mso-outline-level: 1;"><span lang="EN-US" style="font-size: 11.0pt;">Definition: line <i style="mso-bidi-font-style: normal;">Li</i> is uppermost at a given x-coordinate <i style="mso-bidi-font-style: normal;">x0</i> if its y-coordinate at <i style="mso-bidi-font-style: normal;">x0</i> is greater than the y-coordinates of all the other lines at <i style="mso-bidi-font-style: normal;">x0</i>.<span style="mso-spacerun: yes;">  </span>Line <i style="mso-bidi-font-style: normal;">Li</i> is visible if there is some x-coordinate at which it is uppermost – intuitively, some portion of it can be seen if you look from infinity of y (<i style="mso-bidi-font-style: normal;">y = </i></span><i style="mso-bidi-font-style: normal;"><span lang="EN-US" style="font-size: 11.0pt; font-family: Symbol; mso-ascii-font-family: 'Times New Roman'; mso-hansi-font-family: 'Times New Roman'; mso-char-type: symbol; mso-symbol-font-family: Symbol;"><span style="mso-char-type: symbol; mso-symbol-font-family: Symbol;">µ</span></span></i><i style="mso-bidi-font-style: normal;"><span lang="EN-US" style="font-size: 11.0pt;">)</span></i><span lang="EN-US" style="font-size: 11.0pt;">; For example: following figure is an instance of visible lines (labeled 1-5). All the lines except for 2 are visible.</span>

<p class="MsoNormal" style="margin-left: 36.0pt; mso-outline-level: 1;"><span lang="EN-US" style="font-size: 11.0pt;"> </span>

<p class="MsoNormal" style="text-align: center; mso-outline-level: 1;" align="center"><span lang="EN-US" style="font-size: 11.0pt;"><!-- [if gte vml 1]><v:shape id="_x0000_i1027" type="#_x0000_t75" style='width:297pt;height:147.75pt' o:ole=""> <v:imagedata src="file:///C:/Users/Cindy/AppData/Local/Temp/msohtmlclip1/01/clip_image018.emz"  o:title=""/></v:shape><![endif]--><!-- [if !vml]--><img decoding="async" width="396" height="197" data-src="file:///C:/Users/Cindy/AppData/Local/Temp/msohtmlclip1/01/clip_image019.gif" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

  <noscript>

   <img decoding="async" src="file:///C:/Users/Cindy/AppData/Local/Temp/msohtmlclip1/01/clip_image019.gif" width="396" height="197">

  </noscript><!--[endif]--><!-- [if gte mso 9]><xml> <o:OLEObject Type="Embed" ProgID="AcroExch.Document.11" ShapeID="_x0000_i1027"  DrawAspect="Content" ObjectID="_1709471060"> </o:OLEObject></xml><![endif]--></span>

<p class="MsoNormal" style="mso-outline-level: 1;"><span lang="EN-US" style="font-size: 11.0pt;"> </span>

<p class="MsoNormal" style="margin-left: 36.0pt; mso-outline-level: 1;"><span lang="EN-US" style="font-size: 11.0pt;">Give an algorithm that takes n lines as input and in no more than O(n^3) time returns all of the ones that are visible.<span style="mso-spacerun: yes;">  </span>Show the time complexity.</span>

<p class="MsoNormal" style="mso-outline-level: 1;"><span lang="EN-US" style="font-family: 'Arial',sans-serif;"> </span>

<p class="MsoNormal" style="mso-outline-level: 1;"><span lang="EN-US" style="font-family: 'Arial',sans-serif;"> </span>

<p class="MsoNormal" style="mso-outline-level: 1;"><span lang="EN-US" style="font-family: 'Arial',sans-serif;"> </span>

<p class="MsoNormal" style="mso-outline-level: 1;"><span lang="EN-US" style="font-family: 'Arial',sans-serif;"> </span>

<p class="MsoNormal" style="mso-outline-level: 1;"><b style="mso-bidi-font-weight: normal;"><u><span lang="EN-US" style="font-family: 'Arial',sans-serif;">[Part B]: Divide and Conquer Programming (21%)</span></u></b>

<p class="MsoNormal" style="mso-outline-level: 1;"><span lang="EN-US" style="font-family: 'Arial',sans-serif;"> </span>

<p class="MsoNormal" style="mso-outline-level: 1;"><span lang="EN-US" style="font-family: 'Arial',sans-serif;"> </span>

<p class="MsoNormal" style="mso-outline-level: 1;"><span lang="EN-US" style="color: windowtext; mso-bidi-language: AR-SA;">1. [12%] </span><span lang="EN-US" style="font-family: 'Arial',sans-serif;">Implement the algorithm for finding the closest pair of points in two dimension plane using divide and conquer strategy.</span>

<p class="MsoNormal" style="mso-margin-top-alt: auto; mso-margin-bottom-alt: auto;"><span lang="EN-US" style="color: windowtext; mso-bidi-language: AR-SA;">A system for controlling air or sea traffic might need to know which are the two closest vehicles in order to detect potential collisions. This part solves the problem of finding the closest pair of points in a set of points. The set consists of points in R<sup>2</sup> defined by both an x and a y coordinate. The “closest pair” refers to the pair of points in the set that has the smallest Euclidean distance, where Euclidean distance between points p<sub>1</sub>=(x<sub>1</sub>,y<sub>1</sub>) and p<sub>2</sub>=(x<sub>2</sub>,y<sub>2</sub>) is simply sqrt((x<sub>1</sub>-x<sub>2</sub>)<sup>2</sup>+(y<sub>1</sub>-y<sub>2</sub>)<sup>2</sup>). If there are two identical points in the set, then the closest pair distance in the set will obviously be zero. </span>

<p class="MsoNormal" style="mso-margin-top-alt: auto; mso-margin-bottom-alt: auto;"><span lang="EN-US" style="color: windowtext; mso-bidi-language: AR-SA;">Input data:<span style="mso-spacerun: yes;">  </span>n points with coordinates:</span>

<p class="MsoNormal" style="mso-margin-top-alt: auto; mso-margin-bottom-alt: auto;"><span lang="EN-US" style="color: windowtext; mso-bidi-language: AR-SA;">X coordinates: p[0].x, p[1].x,<span style="mso-spacerun: yes;">  </span>p[2].x,…., p[n].x</span>

<p class="MsoNormal" style="mso-margin-top-alt: auto; mso-margin-bottom-alt: auto;"><span lang="ES-TRAD" style="color: windowtext; mso-ansi-language: ES-TRAD; mso-bidi-language: AR-SA;">Y coordinates: p[0].y, p[1].y,<span style="mso-spacerun: yes;">  </span>p[2].y,…., p[n].y</span>

<p class="MsoNormal" style="mso-margin-top-alt: auto; mso-margin-bottom-alt: auto;"><span lang="EN-US" style="color: windowtext; mso-bidi-language: AR-SA;">Output: minimum distance between points p[i] and p[j]<span style="mso-spacerun: yes;">  </span>(index i and j should be identified)</span>

<p class="MsoNormal" style="text-align: justify; line-height: 150%; tab-stops: list 18.0pt;"><span lang="EN-US" style="font-size: 11.0pt; mso-bidi-font-size: 12.0pt; line-height: 150%;"><span style="mso-spacerun: yes;"> </span>Input data for test:</span>

<p class="MsoNormal" style="text-align: justify; line-height: 150%; tab-stops: list 18.0pt;"><span lang="EN-US" style="font-size: 11.0pt; mso-bidi-font-size: 12.0pt; line-height: 150%;"><span style="mso-spacerun: yes;">                </span>n = 10000; </span>

<p class="MsoNormal" style="text-align: justify; line-height: 150%; tab-stops: list 18.0pt;"><span lang="EN-US" style="font-size: 11.0pt; mso-bidi-font-size: 12.0pt; line-height: 150%;"><span style="mso-spacerun: yes;">                </span>for(i=0; i&lt;n; i++)</span>

<p class="MsoNormal" style="text-align: justify; line-height: 150%; tab-stops: list 18.0pt;"><span lang="EN-US" style="font-size: 11.0pt; mso-bidi-font-size: 12.0pt; line-height: 150%;"><span style="mso-spacerun: yes;">                 </span>{</span>

<p class="MsoNormal" style="text-align: justify; line-height: 150%; tab-stops: list 18.0pt;"><span lang="EN-US" style="font-size: 11.0pt; mso-bidi-font-size: 12.0pt; line-height: 150%;"><span style="mso-spacerun: yes;">                   </span>p[i].x= n- i;</span>

<p class="MsoNormal" style="text-align: justify; line-height: 150%; tab-stops: list 18.0pt;"><span lang="EN-US" style="font-size: 11.0pt; mso-bidi-font-size: 12.0pt; line-height: 150%;"><span style="mso-spacerun: yes;">             </span><span style="mso-spacerun: yes;">      </span>p[i].y= n- i; </span>

<p class="MsoNormal" style="text-align: justify; line-height: 150%; tab-stops: list 18.0pt;"><span lang="EN-US" style="font-size: 11.0pt; mso-bidi-font-size: 12.0pt; line-height: 150%;"><span style="mso-spacerun: yes;">                    </span>}</span>

<p class="MsoNormal" style="text-align: justify; line-height: 150%; tab-stops: list 18.0pt;"><span lang="EN-US" style="font-size: 11.0pt; mso-bidi-font-size: 12.0pt; line-height: 150%;"> </span>

<p class="MsoNormal" style="text-align: justify; line-height: 150%; tab-stops: list 18.0pt;"><span lang="EN-US" style="font-size: 11.0pt; mso-bidi-font-size: 12.0pt; line-height: 150%;">Other Input data for test:</span>

<p class="MsoNormal" style="text-align: justify; line-height: 150%; tab-stops: list 18.0pt;"><span lang="EN-US" style="font-size: 11.0pt; mso-bidi-font-size: 12.0pt; line-height: 150%;"><span style="mso-spacerun: yes;">                </span>n = 10000; </span>

<p class="MsoNormal" style="text-align: justify; line-height: 150%; tab-stops: list 18.0pt;"><span lang="EN-US" style="font-size: 11.0pt; mso-bidi-font-size: 12.0pt; line-height: 150%;"><span style="mso-spacerun: yes;">                </span>for(i=0; i&lt;n; i++)</span>

<p class="MsoNormal" style="text-align: justify; line-height: 150%; tab-stops: list 18.0pt;"><span lang="EN-US" style="font-size: 11.0pt; mso-bidi-font-size: 12.0pt; line-height: 150%;"><span style="mso-spacerun: yes;">                 </span>{</span>

<p class="MsoNormal" style="text-align: justify; line-height: 150%; tab-stops: list 18.0pt;"><span lang="EN-US" style="font-size: 11.0pt; mso-bidi-font-size: 12.0pt; line-height: 150%;"><span style="mso-spacerun: yes;">                   </span>p[i].x= i*i;</span>

<p class="MsoNormal" style="text-align: justify; line-height: 150%; tab-stops: list 18.0pt;"><span lang="EN-US" style="font-size: 11.0pt; mso-bidi-font-size: 12.0pt; line-height: 150%;"><span style="mso-spacerun: yes;">                   </span>p[i].y= i*i; </span>

<p class="MsoNormal" style="text-align: justify; line-height: 150%; tab-stops: list 18.0pt;"><span lang="EN-US" style="font-size: 11.0pt; mso-bidi-font-size: 12.0pt; line-height: 150%;"><span style="mso-spacerun: yes;">                  </span><span style="mso-spacerun: yes;">  </span>}</span>

<p class="MsoNormal" style="mso-margin-top-alt: auto; mso-margin-bottom-alt: auto;"><span lang="EN-US" style="color: windowtext; mso-bidi-language: AR-SA;"><span style="mso-spacerun: yes;">  </span></span>

<p class="MsoNormal"><span lang="EN-US">Or: </span>

<p class="MsoNormal"><span lang="EN-US"> </span>

<p class="MsoNormal"><span lang="EN-US">Input: </span>

<p class="MsoNormal"><span lang="EN-US"> </span>

<p class="MsoNormal"><span lang="EN-US">If X&gt;0</span>

<p class="MsoNormal"><span lang="EN-US">X=1, 3, 5, 7, 9, 11, 13, 15, 17, 19, 21, 23, ……,19995, 19997, 19999<span style="mso-spacerun: yes;">    </span>(odd numbers)</span>

<p class="MsoNormal"><span lang="EN-US">Y=int(<span style="position: relative; top: 6.0pt; mso-text-raise: -6.0pt;"><!-- [if gte vml 1]><v:shape id="_x0000_i1028" type="#_x0000_t75" style='width:117.75pt;height:21.75pt' o:ole=""> <v:imagedata src="file:///C:/Users/Cindy/AppData/Local/Temp/msohtmlclip1/01/clip_image020.wmz"  o:title=""/></v:shape><![endif]--><!-- [if !vml]--><img decoding="async" width="157" height="29" data-src="file:///C:/Users/Cindy/AppData/Local/Temp/msohtmlclip1/01/clip_image021.gif" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

   <noscript>

    <img decoding="async" src="file:///C:/Users/Cindy/AppData/Local/Temp/msohtmlclip1/01/clip_image021.gif" width="157" height="29">

   </noscript><!--[endif]--></span><!-- [if gte mso 9]><xml> <o:OLEObject Type="Embed" ProgID="Equation.3" ShapeID="_x0000_i1028"  DrawAspect="Content" ObjectID="_1709471061"> </o:OLEObject></xml><![endif]--><span style="mso-spacerun: yes;">    </span>)</span>

<p class="MsoNormal"><span lang="EN-US"> </span>

<p class="MsoNormal"><span lang="EN-US">Else</span>

<p class="MsoNormal"><span lang="EN-US">X=0, -2, -4, -6, -8, -10, -12, ……,<span style="mso-spacerun: yes;">  </span>-19996, -19998, -20000<span style="mso-spacerun: yes;">  </span>(even number)</span>

<p class="MsoNormal"><span lang="EN-US">Y= int(<span style="position: relative; top: 6.0pt; mso-text-raise: -6.0pt;"><!-- [if gte vml 1]><v:shape id="_x0000_i1029" type="#_x0000_t75" style='width:123.75pt;height:21.75pt' o:ole=""> <v:imagedata src="file:///C:/Users/Cindy/AppData/Local/Temp/msohtmlclip1/01/clip_image022.wmz"  o:title=""/></v:shape><![endif]--><!-- [if !vml]--><img decoding="async" width="165" height="29" data-src="file:///C:/Users/Cindy/AppData/Local/Temp/msohtmlclip1/01/clip_image023.gif" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

   <noscript>

    <img decoding="async" src="file:///C:/Users/Cindy/AppData/Local/Temp/msohtmlclip1/01/clip_image023.gif" width="165" height="29">

   </noscript><!--[endif]--></span><!-- [if gte mso 9]><xml> <o:OLEObject Type="Embed" ProgID="Equation.3" ShapeID="_x0000_i1029"  DrawAspect="Content" ObjectID="_1709471062"> </o:OLEObject></xml><![endif]--><span style="mso-spacerun: yes;">    </span>)</span>

<p class="MsoNormal" style="mso-margin-top-alt: auto; mso-margin-bottom-alt: auto;"><span lang="EN-US" style="color: windowtext; mso-bidi-language: AR-SA;"> </span>

<p class="MsoNormal" style="text-align: justify; line-height: 150%; tab-stops: list 18.0pt;"><span lang="EN-US" style="font-size: 11.0pt; mso-bidi-font-size: 12.0pt; line-height: 150%;"> </span>

<p class="MsoNormal" style="text-align: justify; line-height: 150%; tab-stops: list 18.0pt;"><span lang="EN-US" style="color: windowtext; mso-bidi-language: AR-SA;"><span style="mso-spacerun: yes;"> </span>2. (9%) </span><span lang="EN-US" style="font-size: 11.0pt; mso-bidi-font-size: 12.0pt; line-height: 150%;">Use the brute-force approach to solve the above problem. Compare the two implemented algorithms in terms of time complexity. Print out the time cost during the execution of these two algorithms.</span>

<p class="MsoNormal" style="mso-margin-top-alt: auto; mso-margin-bottom-alt: auto;"><span lang="EN-US" style="color: windowtext; mso-bidi-language: AR-SA;">3. (Extra 9%) apply the close-pair algorithm to the three dimensional case. </span>

<p class="MsoNormal" style="mso-outline-level: 1;"><span lang="EN-US" style="font-family: 'Arial',sans-serif;"> </span>

<p class="MsoNormal" style="mso-outline-level: 1;"><u><span lang="EN-US" style="font-family: 'Arial',sans-serif; color: red;">Note 1:</span></u>

<p class="MsoNormal" style="mso-outline-level: 1;"><span lang="EN-US" style="font-family: 'Arial',sans-serif; color: red;"><span style="mso-spacerun: yes;">     </span></span>

<p class="MsoNormal" style="mso-outline-level: 1;"><span lang="EN-US" style="font-family: 'Arial',sans-serif; color: windowtext;">Your report (.doc) of the programming part should follow the following format:</span>

<p class="MsoNormal" style="mso-outline-level: 1;"><span lang="EN-US" style="font-family: 'Arial',sans-serif; color: windowtext;"> </span>

<p class="MsoNormal" style="margin-left: 18.0pt; mso-outline-level: 1;"><span lang="EN-US" style="font-family: 'Arial',sans-serif; color: windowtext;"> </span>

<p class="MsoNormal" style="margin-left: 36.0pt; text-indent: -18.0pt; mso-outline-level: 1; mso-list: l0 level1 lfo4; tab-stops: list 36.0pt;"><!-- [if !supportLists]--><span lang="EN-US" style="font-family: 'Arial',sans-serif; mso-fareast-font-family: Arial; color: windowtext;"><span style="mso-list: Ignore;">(1)<span style="font: 7.0pt 'Times New Roman';">  </span></span></span><!--[endif]--><span lang="EN-US" style="font-family: 'Arial',sans-serif; color: windowtext;">Algorithm description</span>

<p class="MsoNormal" style="mso-outline-level: 1;"><span lang="EN-US" style="font-family: 'Arial',sans-serif; color: windowtext;"> </span>

<p class="MsoNormal" style="margin-left: 36.0pt; text-indent: -18.0pt; mso-outline-level: 1; mso-list: l0 level1 lfo4; tab-stops: list 36.0pt;"><!-- [if !supportLists]--><span lang="EN-US" style="font-family: 'Arial',sans-serif; mso-fareast-font-family: Arial; color: windowtext;"><span style="mso-list: Ignore;">(2)<span style="font: 7.0pt 'Times New Roman';">  </span></span></span><!--[endif]--><span lang="EN-US" style="font-family: 'Arial',sans-serif; color: windowtext;">Major codes</span>

<p class="MsoNormal" style="mso-outline-level: 1;"><span lang="EN-US" style="font-family: 'Arial',sans-serif; color: windowtext;"> </span>

<p class="MsoNormal" style="margin-left: 36.0pt; text-indent: -18.0pt; mso-outline-level: 1; mso-list: l0 level1 lfo4; tab-stops: list 36.0pt;"><!-- [if !supportLists]--><span lang="EN-US" style="font-family: 'Arial',sans-serif; mso-fareast-font-family: Arial; color: windowtext;"><span style="mso-list: Ignore;">(3)<span style="font: 7.0pt 'Times New Roman';">  </span></span></span><!--[endif]--><span lang="EN-US" style="font-family: 'Arial',sans-serif; color: windowtext;">Running results</span>

<p class="MsoNormal" style="mso-outline-level: 1;"><span lang="EN-US" style="font-family: 'Arial',sans-serif; color: windowtext;"> </span>

<p class="MsoNormal" style="margin-left: 36.0pt; text-indent: -18.0pt; mso-outline-level: 1; mso-list: l0 level1 lfo4; tab-stops: list 36.0pt;"><!-- [if !supportLists]--><span lang="EN-US" style="font-family: 'Arial',sans-serif; mso-fareast-font-family: Arial; color: windowtext;"><span style="mso-list: Ignore;">(4)<span style="font: 7.0pt 'Times New Roman';">  </span></span></span><!--[endif]--><span lang="EN-US" style="font-family: 'Arial',sans-serif; color: windowtext;">Report of any bugs</span>

<p class="MsoNormal" style="mso-outline-level: 1;"><span lang="EN-US" style="font-family: 'Arial',sans-serif; color: windowtext;"> </span>

<p class="MsoNormal" style="mso-outline-level: 1;"><span lang="EN-US" style="font-family: 'Arial',sans-serif; color: red;"> </span>

<p class="MsoNormal" style="mso-outline-level: 1;"><u><span lang="EN-US" style="font-family: 'Arial',sans-serif; color: red;">Note 2:</span></u>

<p class="MsoNormal" style="mso-outline-level: 1;"><span lang="EN-US" style="font-family: 'Arial',sans-serif;"> </span>

<p class="MsoNormal" style="mso-outline-level: 1;"><span lang="EN-US" style="font-family: 'Arial',sans-serif;">2.1 For Part B, your code package includes your code, makefile, executable file, and write-up (.doc).  </span>

<p class="MsoNormal" style="mso-outline-level: 1;"><span lang="EN-US" style="font-family: 'Arial',sans-serif;"> </span>

<p class="MsoNormal" style="mso-outline-level: 1;"><span lang="EN-US" style="font-family: 'Arial',sans-serif;"> </span>

<p class="MsoNormal" style="mso-outline-level: 1;"><span lang="EN-US" style="font-family: 'Arial',sans-serif;">2.2 Your program will read an input file and write an output file.</span>

<p class="MsoNormal" style="mso-outline-level: 1;"><span lang="EN-US" style="font-family: 'Arial',sans-serif;"> </span>

<p class="MsoNormal" style="mso-outline-level: 1;"><span lang="EN-US" style="font-family: 'Arial',sans-serif;">2.3 Your program should be invoked like this…</span>

<p class="MsoNormal" style="mso-outline-level: 1;"><span lang="EN-US" style="font-family: 'Arial',sans-serif;"> </span>

<p class="MsoNormal" style="mso-outline-level: 1;"><span lang="EN-US" style="font-family: 'Arial',sans-serif;"><span style="mso-spacerun: yes;">        </span>prompt&gt;submission inputFile.txt outputFile.txt</span>

<p class="MsoNormal" style="mso-outline-level: 1;"><span lang="EN-US" style="font-family: 'Arial',sans-serif;"> </span>

<p class="MsoNormal" style="mso-outline-level: 1;"><span lang="EN-US" style="font-family: 'Arial',sans-serif;"><span style="mso-spacerun: yes;">        </span>where inputFile.txt is referring to an input file, </span>

<p class="MsoNormal" style="mso-outline-level: 1;"><span lang="EN-US" style="font-family: 'Arial',sans-serif;"><span style="mso-spacerun: yes;">                   </span>ouputFile.txt is referring to an output file. </span>

<p class="MsoNormal" style="mso-outline-level: 1;"><span lang="EN-US"> </span>

5/5 - (1 vote)