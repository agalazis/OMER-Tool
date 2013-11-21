OMER-Tool
=========

OMER tool (Open Menu easy evaluation tool for developers who want to find out if the data are suitable for their projects)

The tool
=========

The tool consists of a crawler a harvester and a menu counter

Step 1:The Crawler
=============

You may run the harvester using:

./crawler\<your first country here\> \<your second country here\>  \<your third country here\>

The crawler accepts countries as arguments ad finds the links of open menus(from al the cities of each country) which are saved to a .crawl file which is the cleaned from duplicates and is output to a .cleaned file

Step 2:The harvester
=============

When you are done with the crowler you can rub the harvester using:

./harvester 

The harvester dowloads all the menus in the ./harvestedmenus directory according to the cleaned file of links generated by the harvester.


Step 3:The manu counter
=============
I you want to count the menus downloaded you may use the counter tool:
./countmenus
