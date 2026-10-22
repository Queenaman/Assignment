# Module 1 : Assignment 1 - What happens between typing a URL and seeing the page?
Answer - When you type a URL into your browser and press Enter, a series of steps occur in the background to render the webpage. Here's a brief overview of the process:
* URL Parsing: The browser parses the URL to extract components like the protocol, domain, and path.
* DNS Lookup: The browser checks its cache for the IP address. If not found, it queries the operating system or a DNS resolver to find the IP address.
* TCP Connection: The browser establishes a TCP connection to the server using a three-way handshake.
* HTTP Request: The browser sends an HTTP request to the server, which processes the request and sends a response.
*Server Response: The server sends the response, which can be in various formats like JSON, XML, or HTML.
* HTML Parsing: The browser parses the HTML to build the Document Object Model (DOM).
* CSS and JavaScript Execution: The browser applies CSS styles and executes JavaScript to render the page.
* Rendering: Finally, the browser renders the page on the screen, making it visible to the user.





git config --global user.email "queenaman1223@gmail.com"
git config --global user.name "Queenaman"