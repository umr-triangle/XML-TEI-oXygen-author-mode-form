# oXygen-Author-mode-form

Triangle digital edition team

February 29th, 2016 - ducumentation update

To use our project file to customize a TEI framework in oXygen see : https://github.com/umr-triangle/XML-TEI-oXygen-author-mode-form/blob/master/Tutoriel-Adaptation-Framework-oXygen.pdf

August 28th, 2015

An oXygen Author mode form for editing TEI corpus (css stylesheet + rng schema + xml tei corpus sample). This form was initially used for editing the "Roman des Morand" XML TEI corpus file.

February 12th, 2016 : updated into a oXygen project with a img folder for customizing the TEI P5 framework

TO USE: 

* download and unzip content - check that the whole content is in the same directory
* open the morand.xpr (= the oXygen Morand project)
* open Author Mode in oXygen
* open the teiCorpus_Morand_sample.xml file in oXygen 
* open the workshop.xml to test

TEI P5 customization with our Morand project
* Duplicate & rename TEI P5 framework
* Customize : 
* + add new actions like "ToggleSurroundWithElementOperation" for element del[@rend="overstrike"], add[@place="above"], etc. 
* + for each new action use the img-my-framework folder images (png for the 20*20 px and .gif for 16*16 px)
* Add your own XML and RNG files in the same directory + in the new framework
* Or open the Morand CSS File, change its name and adapt the CSS selectors according to your own XML file and RNG schema


TO ADD a named entiy:

* select text of the named entity
* + right click
* + select "refactorisation",
* + select "encadrer avec des balises"
* + select the appropriate element (here, "rs")
* + then the foldable list should appear on the right of the named entity : select the appropriate named entity or type a new one and press ENTER.
* + select "TEI P5", and "actualiser les références"

TO CUSTOMIZE: 


FURTHER HELP ON OXYGEN AUTHOR MODE AND CSS : 
* oXygen Video tutorial : http://www.oxygenxml.com/demo/CSS_Inspector.html
* oXygen Documentation on the Oxygen XML Author CSS Extensions : http://mirror.oxygenxml.com/doc/ug-author/index.html#concepts/dg-oXygen-css-extensions.html

