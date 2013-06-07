##PrizmCloud-Joomla

Joomla 2.5 Extension for PrizmCloud Embedded Document Viewer. Embed our document viewer in your site. Your visitors view your documents in any of 300+ file types. Just like that.

You will need a PrizmCloud account to use PrizmCloud Document Viewer. [PrizmCloud Sign Up](http://prizmcloud.accusoft.com/register.html "PrizmCloud") 

View a [demo](http://prizmcloud.accusoft.com/demo.html)

##Installation Instructions
1. Download the zip file, unzip.
2. Login into Joomla! Administration and navigate to Extension Manager.
3. You will see something similar to 'Upload Package File'.
4. Select the PrizmCloud-Joomla2.5.zip file and install.
5. Within the Plug-in Manager, find Content - PrizmCloud Document Viewer and Button - PrizmCloud Document Viewer and enable both plugins.
6. Within the Content - PrizmCloud Viewer Plugin Basic Options, add your PrizmCloud Key

###Content Plugin

This allows you to add a line of text (see below) to any content editor.

Usage: 

```
{Prizmcloud-viewer}
```

This tag accepts the following parameters:

* **vtype**: is the viewer type (either flash or html5)
* **doc_url**: is the document url
* **vwidth**: is the viewer width in px
* **vheight**: is the viewer height in px
* **print_button**: options 'Yes' or 'No'
* **toolbar_color**: hex color, no '#' for example "CCCCCC"

For example:
```
{Prizmcloud-viewer vtype="html5" vwidth="800" vheight="600" doc_url="http://domain.com/path/to/file.ext" print_button="Yes" toolbar_color="999999"}
```

###Editor Button Plugin

This puts an easy to use button below the content editor that dynamically adds the above line of code to your editor.
