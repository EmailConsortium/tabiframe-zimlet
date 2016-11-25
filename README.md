# tabiframe-zimlet
This zimlet is to add a new tab onto Zimbra webmail that loads a complete web page in an iframe. The webpage URL is defined in com_zimbra_tabiframe.js.

To build and install the zimlet:
* Clone the git repository
* Modify tab-url, tab-label properties in config_template.xml to your right webpage
* Run "sh build.sh" to build your zimlet
* Deploy zimlet from the new .zip file
