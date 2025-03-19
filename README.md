# ZETA-AI

ZETA AI, is built using HTML, CSS, and JavaScript. The HTML files (index.html and chat.html) structure the web pages, defining sections like the header, chat container, and features. The CSS file (styles.css) styles the website, providing themes, layouts, and animations, including support for dark mode. JavaScript (script.js) adds interactivity, handling chat messages, user input, and theme toggling.

My project also integrates an external API—Google's Gemini AI (https://generativelanguage.googleapis.com/v1beta/models/gemini-2.0-flash:generateContent). The API processes user input and returns AI-generated responses. However, using the API requires an API key, and storing it directly in JavaScript is insecure. So for that storing in backend is also necessary.

The script formats user messages, displays chat history, and handles dark mode toggling with local storage support. It also includes functions for message formatting, escaping HTML, and handling errors. Overall, ZETA AI combines front-end technologies with an AI-powered chatbot using an external API.
