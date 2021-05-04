
-------------------------

:link: Official page: https://honest-metrics.com/

:speech_balloon: Official documentation: https://honest-metrics.com/gtm

:link: Template page in GTM gallery: https://tagmanager.google.com/gallery/#/owners/Honest-Metrics/templates/gtm_template

-------------------------

**Input data:**
- _siteId_<br>Site ID, which can be obtained in your Honest-Metrics account. Represents a positive integer. Required field.

**Methods:**
- _injectScript(url, onSuccess, onFailure[, cacheToken])_<br>Adds a script tag to the page to asynchronously load the provided URL. Callbacks are in the form of function instances wrapped in JavaScript function calls.

- _encodeUriComponent(str)_<br>Returns an encoded uniform resource identifier (URI) with escaped special characters. The returned string is the result of encoding the resulting string into a URI format.

**Permissions:**
- _injects scripts_<br>Allows you to upload only the script of the Honest-Metrics service to the site.

**Triggering:**
- _All Pages_<br>For the monitoring script to work on all pages of the target site.

-------------------------

**Configuration example:**

<img src="https://honest-metrics.com/img/screen-gtm.png" alt="drawing" width="900"/>
<img src="https://honest-metrics.com/img/screen-gtm-1.png" alt="drawing" width="900"/>
