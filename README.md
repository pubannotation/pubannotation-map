# pubannotation-map

# Introduction
PubAnnotation Map is a zoomable treemap to visualise and discover the hierarchical data from <a href="http://pubannotation.org">PubAnnotation</a>.
Treemaps are a form of visualization where the area of each rectangle is proportional to its value. Originally developed by Mike Bostock the treemap uses D3.js. This version extends the original library allowing to use the treemap as a navigation device for web and mobile users.

Click any cell to zoom in, or the top facebook blue label to zoom out.
Cell size is proportional to the number of PubMed abstracts.
Different shades of color are related to the number of PubAnnotation 

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
