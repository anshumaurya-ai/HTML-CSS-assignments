# Assignment 1 – What Happens Between Typing a URL and Seeing the Page?

When I type a URL into the browser and press Enter, several steps happen before the webpage appears.

1. **Browser Cache:** The browser first checks its cache for previously stored information.

2. **DNS Lookup:** The browser contacts a DNS server to translate the domain name into an IP address.

3. **TCP Connection:** The browser opens a TCP connection to the server.

4. **TLS Handshake:** For HTTPS websites, the browser performs a TLS handshake to encrypt communication.

5. **HTTP Request:** The browser sends an HTTP request to the server.

6. **Server Response:** The server processes the request and sends a response with a status code such as 200 OK and the HTML document.

7. **HTML Parsing:** The browser parses HTML and creates the DOM (Document Object Model).

8. **Resource Loading:** The browser loads CSS, JavaScript, images and fonts.

9. **Render Tree:** The browser combines DOM and CSSOM to create the render tree.

10. **Layout and Painting:** The browser calculates the layout and displays pixels on the screen.

11. **JavaScript Execution:** JavaScript runs and can update the webpage further.

**Conclusion:** All these steps work together to display a webpage in the browser.