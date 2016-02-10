## Install from MODX Extras

Search for PDFResource in the Package Manager of a MODX installation and install it in there.

## Manual installation

If you can't access the MODX Extras Repository in your MODX installation, you can manually install PDFResource.

* Download the transport package from [MODX Extras](http://modx.com/extras/package/pdfresource)
  (or one of the pre built transport packages in [_packages](https://github.com/Jako/PDFResource/tree/master/_packages))
* Upload the zip file to your MODX installation's `core/packages` folder.
* In the MODX Manager, navigate to the Package Manager page, and select 'Search locally for packages' from the dropdown 
  button.
* PDFResource should now show up in the list of available packages. Click the corresponding 'Install' button and follow 
  instructions to complete the installation.

## Build it from source

To build and install the package from source you could use [Git Package Management](https://github.com/TheBoxer/Git-Package-Management). 
The GitHub repository of PDFResource contains a [config.json](https://github.com/Jako/PDFResource/blob/master/_build/config.json) 
to build that package locally. After downloading the github repository, you have to change into the `core/components/pdfresource` folder 
and install mpdf with composer by invoking `composer install`. Use this option, if you want to debug PDFResource and/or contribute 
bugfixes and enhancements.

<!-- Piwik -->
<script type="text/javascript">
  var _paq = _paq || [];
  _paq.push(['trackPageView']);
  _paq.push(['enableLinkTracking']);
  (function() {
    var u="//piwik.partout.info/";
    _paq.push(['setTrackerUrl', u+'piwik.php']);
    _paq.push(['setSiteId', 18]);
    var d=document, g=d.createElement('script'), s=d.getElementsByTagName('script')[0];
    g.type='text/javascript'; g.async=true; g.defer=true; g.src=u+'piwik.js'; s.parentNode.insertBefore(g,s);
  })();
</script>
<noscript><p><img src="//piwik.partout.info/piwik.php?idsite=18" style="border:0;" alt="" /></p></noscript>
<!-- End Piwik Code -->
