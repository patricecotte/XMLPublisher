XMLPublisher
============

The XMLPublisher project contains the examples referenced in the MyDocbook book and web pages.

MyDocbook explains how create in an Eclipse IDE an XML project and implement in that project the tools that can generate 
epub and pdf books as well as web pages from XML Docbook documents. 

If imported into Eclipse as an XML project the XMLPublisher will be structured as outlined below. 



XMLpublisher
	docbook-xsl
		fo		division.xsl
				docbook.xsl
		webhelp
			template
				common		main.js
					css		positionning.css				
			xsl				webhelp.xsl
	input
		epub	mimetype
				test_epub.xml
				test.xml
			images
				Eclipse Kepler splash screen.png
				Patrice_Cotte_coverpage_My_Docbook.jpg
		pdf
				test_pdf.xml
				test.xml
			images
			  Eclipse Kepler splash screen.png
				Patrice Cotte backcoverpage.jpg
				Patrice Cotte coverpage My Docbook.jpg
		webhelp		
				test_webhelp.xml
				test.xml
			images	
				Eclipse Kepler splah screen.png
				Home_green.png
				Magnifying glass_48.png
				Media-Play_green.png
				Media-Playback_green.png
				Patrice Cotte web page My Docbook.jpg
				Up_green.png
	buildSimpleBook.xml
	Readme.txt

