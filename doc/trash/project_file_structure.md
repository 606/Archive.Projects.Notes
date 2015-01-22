source: http://opensolution.org/Quick.Cms/docs/?id=en-files_structure

> Quick.Cms consists of several catalogues which store various file
> types. Below is a list of all catalogues with description:

 **- actions/** - you will find here actions files, which are controller
 
 **- core/** - here you can find all files with PHP functions and Java Script, which are responsible for loading or saving data to database
 
 **- core/libraries/** - this catalogue contains all “libraries”, which are responsible for: generating thumbs, uploading files to “files/” directory, parsing templates and others
 
 **- database/** - in this catalogue are placed all data concerning pages, photos and so on. Important is to set rights to writing to this files (chmod 777)
 
 **- database/config/** - in this catalogue is placed file "general.php" which contains general configuration data and "lang_*.php" which contains configuration data for particular languages. If you want to edit configuration data by administration,you should set rights to writing (chmod 777) for this files
 
 **- database/pages/** - in this catalogue are placed pages full description $config['pages_full_description_to_file'] if variable is set to true
 
**-database/translations/** - here you can find files with translations. If you want to add new language, use instruction. If you want to modify translations in administration panel, set rights to writing (chmod 777) to this files

 **- files/** - this catalogue contains uploaded pictures and files. You should set rights to writing (chmod 777) for all catalogues and files, if you want Quick.Cms to work correctly
 
**- plugins/** - all installed "plugins" like mlbox (displays enlarged images in a box), tinymce (WYSIWYG editor) and valums-file-uploader (uploading files to a server script) are located here
 
 **- templates/** - in this catalogue are placed all templates, and also graphic files. If you want to modify design of the site, edit a proper file from this catalogue.
