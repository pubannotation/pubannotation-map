# Introduction
<a href="https://en.wikipedia.org/wiki/Treemapping">Treemap</a> is a form used to display/discover hierarchical data. PubAnnotation Map is a zoomable treemap to easily get the clear view of the <a href="http://pubannotation.org">PubAnnotation</a> datasets. 

# Demo
<a href="https://s3-ap-northeast-1.amazonaws.com/treemap.pubannotation.org/index.1.0.html">Here<a/>. 

# Data format 
```json
{ 
	"_comment": "value: Number of PubMed abstracts. proj: Number of PubAnnotation projects. ann: Number of PubAnnotation annotations. abs: Number of PubAnnotation abstracts",
	"name": "All Categories", "children": [
		{
			"name": "Chemicals and Drugs Category", "children": [
				{"name": "Enzymes and Coenzymes", "value": 2747112, "ann": 23881, "abs": 1157, "proj": 1, "link": "<a href=http://pubannotation.org/projects/PennBioIE>PennBioIE 0.9</a>", "corpus": "PennBioIE 0.9"}]}]}
```


# Usage
Click any cell to zoom in, or the top facebook blue label to zoom out.<br>
<li>Cell size is proportional to the number of PubMed abstracts.</li>
<li>Different shades of color are related to the number of PubAnnotation </li>

# Acknowledgements
PubAnnotation Map was based on the original work of <a href="https://bost.ocks.org/mike/treemap/">Mike Bostock</a> using the javascript libray <a href="https://d3js.org">D3.js</a> and the work of <a href="https://gist.github.com/JacquesJahnichen/42afd0cde7cbf72ecb81">Jahnichen Jacques</a>.

# License
All rights reserved belongs to PubAnnotation. 
<!---![alt text](logo.png)--->
