# axios-cors
Wrapper library around axios to provide CORS validation for testing CORS on the backend

This libary implements the CORS protocol in typescript/node to provide built-in CORS validation for backend integration tests against any REST API.  By performing the same steps that the browser performs when validating CORS, integration tests can prove that a REST API is CORS compliant before actually integrating with a UI running in a browser.  This allows bugs to be caught sooner and reduce the number of feedback cycles caused by CORS failures at the point of UI integration with a REST API.
