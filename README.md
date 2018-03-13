# pubannotation-map

# Introduction
PubAnnotation Map is a zoomable <a href="https://en.wikipedia.org/wiki/Treemapping">treemap</a> to display and discover the hierarchical data from <a href="http://pubannotation.org">PubAnnotation</a>. 



# Data format 
```json
{ 
	"_comment": "value: Number of PubMed abstracs. proj: Number of PubAnnotation projects. ann: Number of PubAnnotation annotations. abs: Number of PubAnnotation abstracts",
	"name": "All Categories", "children": [
		{
			"name": "Chemicals and Drugs Category", "children": [
				{"name": "Enzymes and Coenzymes", "value": 2747112, "ann": 23881, "abs": 1157, "proj": 1, "link": "<a href=http://pubannotation.org/projects/PennBioIE>PennBioIE 0.9</a>", "corpus": "PennBioIE 0.9"}]}]}
```
![alt text](logo.png)

# Usage
Click any cell to zoom in, or the top facebook blue label to zoom out.<br>
<li>Cell size is proportional to the number of PubMed abstracts.</li>
<li>Different shades of color are related to the number of PubAnnotation </li>

# Acknowledgements
Zoomable treemap was originally developed by <a href="https://bost.ocks.org/mike/treemap/">Mike Bostock</a> using the javascript libray <a href="https://d3js.org">D3.js</a>. 

# License
PubAnnotation Map is freely available to anyone. 
