<html>
<head>
#how-Browsers-Work
</head>
<body>
<p>A browser has a UI (user interface) that most commonly includes an address bar, back/forward button, and reload button.</P>
<p>When you navigate to a URL in the address bar you are making a “request” for the content at that URL.</P>
<p>That URL you typed into the address bar maps to an IP address.</p>
<p>This is called a DNS lookup. DNS stands for “Domain Name System” and it maps numeric computer addresses to human readable names.</p>
<p>All computers have an IP address.</p>
<p>Once the browser has the IP address it sends an HTTP request to the web server at that address.</p>
<P>HTTP stands for “Hypertext Transfer Protocol” and is used to facilitate requests from your client (the browser) and responses from the server.</p>
<p>As this HTML response is being sent to your browser, the browser’s rendering engine is displaying the requested content on your screen.</p>
<p>To accomplish this the rendering engine “parses” the HTML and creates a DOM tree.</p>
<p>Document Object Model (DOM) is a cross-platform and language-independent convention for representing and interacting with objects in HTML, XHTML, and XML documents.</P>
<p>The browser then parses style data (CSS or inline styles) and together with the HTML it constructs a render tree.</p>
<p>The render tree displays rectangles (that represent divisions, paragraphs, headlines, etc.) with a few visual attributes such as color and size dimensions.</p>
<p>These rectangles are displayed in order on the page.</p>
<p>Next, the browser lays out the contents in the position they will appear in the browser.</p>
<p>As the browser is rendering the HTML it will find tagsthat require files from other URLs.</p>
<p>The browser will send a request to the web server to get each of these files.</p>
</body>
</html>




