## Welcome to my GitHub Pages  

<img src="./images/CupTrim.png" alt="Me"
	title="Cup winner" width="175" height="250" />

<a href = "mailto: drclongstaff@gmail.com">Contact me</a>

### This site contains links to my Shiny apps that deal with biochemical analysis, particularly in relation to haemostasis and the clotting and lysis of fibrin.

#### The apps are written using the Shiny package for R to help standardise methods and promote reproducible analysis.  Further details are published in the <A HREF = "https://onlinelibrary.wiley.com/doi/10.1111/jth.13656" TARGET="_blank">Journal of Thrombosis and Haemostasis</A>

<a name="top"></a>

<hr>

#### In this table choose see a brief description or follow the link to use the apps

<table>
	<tr> 
	<th>Brief description below</th> 
	<th>Link to online app</th> 
	</tr> 
	<tr> <td><a href="#lysis">Clot lysis</a></td> 
		<td>
			<A HREF = "https://drclongstaff.shinyapps.io/clotlysisCL_2019" TARGET="_blank">ClotlysisCL_2019</A>
		</td> 
	</tr> 
	<tr> <td><a href="#generation">Thrombin generation</a></td> 
		<td>
			<A HREF = "https://drclongstaff.shinyapps.io/ThrombinCL" TARGET="_blank">ThrombinCL</A>
		</td> 
	</tr>  
	 <tr> <td><a href="#tests">Screening tests</a></td> 
		<td>
			<A HREF = "https://drclongstaff.shinyapps.io/ScreeningCL" TARGET="_blank">ScreeningCL</A>
		</td> 
	</tr> 
	<tr> <td><a href="#activation">Zymogen activation</a></td> 
		<td>
		<A HREF = "https://drclongstaff.shinyapps.io/zymogenCL" TARGET="_blank">ZymogenCL</A>
		</td> 
	</tr> 
	<tr> <td><a href="#kinetics">Michaelis Menten kinetics</a></td> 
		<td>
			<A HREF = "https://drclongstaff.shinyapps.io/MichaelisMentenCL" TARGET="_blank">MichaelisMentenCL</A>
		</td> 
	</tr> 
	<tr> <td><a href="#plots">Scatchard plots</a></td> 
		<td>
		<A HREF = "https://drclongstaff.shinyapps.io/scatchardCL" TARGET="_blank">ScatchardCL</A>
		</td> 
	</tr> 
	<tr> <td><a href="#analysis">Fibrinolysis halo assays</a></td> 
		<td>
			<A HREF = "https://drclongstaff.shinyapps.io/HalolysisCL" TARGET="_blank">HalolysisCL</A>
		</td> 
	</tr> 
	<tr> <td><a href="#albumin">Prekallikrein activator in albumin</a></td> 
		<td>
		<A HREF = "https://drclongstaff.shinyapps.io/PKA_CL" TARGET="_blank">PKA_CL</A>
		</td> 
	</tr> 
</table>

<hr>

<a name="lysis"></a>
### Clot lysis

This app was designed to facilitate the analysis of fibrin clotting and lysis curves, such as the one shown below. 

 <img src="./images/CurveF10.PNG" alt="Curve"
	title="Clot lysis curve" width="350" height="300" />

The output from a set of clot lysis curves is shown here, along with the results for the time to 50% clot lysis. The app makes it easy to extract selected parameters from these curves, such as time to a chosen % lysis, maximum absorbance, area under the curve, etc.

<img src="./images/GraphTable.PNG" alt="GraphTable"
	title="Clot lysis results" width="650" height="600" />

Options are provided for baseline selection and curve fitting to facilitate reproducible, high throughput analysis

This is a link to the online app, please try it out <A HREF = "https://drclongstaff.shinyapps.io/clotlysisCL_2019" TARGET="_blank">ClotlysisCL_2019</A>


Detailed help notes are available <A HREF = "./docs/Clotlysis_CL_help_notes_2019.pdf" TARGET="_blank">here</A>


Return to <a href="#top">top</a>

<hr>

<a name="generation"></a>

### Thrombin generation

This app is similar to the clot lysis app, but the names of the parameters extracted from the curvees are different.  For example an initiation level is set to identify the change in thrombin that signifies the end of the lag time.

 <img src="./images/CaptureCurve.PNG" alt="Curve"
	title="Thrombin generation curve" width="500" height="400" />

Detailed help notes are available <A HREF = "./docs/TGA_help_notes_2019.pdf" TARGET="_blank">here</A>

Return to <a href="#top">top</a>

<hr>

<a name="tests"></a>	


### Screening tests and false positives, for example with D-dimer assays

This app was designed to help understand how sensitivity, specificity and prevalence affect rates of false positive and negative test result.  It uses some published numbers from D-dimer testing, but is useful for all kinds of screening tests.  The help tab covers some other possible applications.

 <img src="./images/screening1.PNG" alt="Screening"
	title="D-dimer test example" width="500" height="400" />
	
Return to <a href="#top">top</a>

<hr>

<a name="activation"></a>


### Zymogen activation, for example plasminogen activation assays

Clotting and fibrinolysis cascades involve zymogen activation reactions, which are often studied in isolation.  For example reaction mixtures of enzyme (streptokinase), substrate (plasminogen) and chromogenic substrate that is sensitive to the generated plasmin.  The rate of plasmin generation (in other words the activity of streptokinase) can be derived from plots of chromogenic substrate hydroloysis versus time squared.  This app makes these calculations easy to perform.

<img src="./images/screenCapSq.png" alt="zymogen"
	title="Curves and calculations for zymogen activation" width="602" height="826" />
	
The app can be used to calculate rates of simple chromogenic substrate hydroloysis, rates of absorbance versus time squared, or by providing a few parameters, the rate of substrate activation in pM/s
	

Detailed help notes are available <A HREF = "./docs/ZymogenActn06_help_notes.pdf" TARGET="_blank">here</A>

Return to <a href="#top">top</a>

<hr>

<a name="kinetics"></a>	

### Michaelis Menten kinetics and linear transformations

This app analysis Michaelis Menten curves and compares results for various common linear transformations

 <img src="./images/MMcurve.PNG" alt="MMenten"
	title="Example MM analysis" width="500" height="500" />
	
Return to <a href="#top">top</a>

<hr>

<a name="plots"></a>
### Binding curves and Scatchard plots

 <img src="./images/Binding_scatch.PNG" alt="Scatchard"
	title="Scatchard transformation" width="500" height="450" />
	
Return to <a href="#top">top</a>

<hr>

<a name="analysis"></a>	
### Fibrinolysis halo assays

 <img src="./images/curveEg.png" alt="Halo"
	title="A halo assay curve" width="400" height="300" />
	
Return to <a href="#top">top</a>

<hr>

<a name="albumin"></a>	
### Prekallikrein activator contamination in albumin or immunoglobulins

This is how the plate looks with background subtraction from the top half of the plate

 <img src="./images/PKA_plots.PNG" alt="Curve"
	title="PKA plots" width="500" height="400" />
	

Detailed help notes are available <A HREF = "./docs/PKA_assay_help_notes.pdf" TARGET="_blank">here</A>

Return to <a href="#top">top</a>
