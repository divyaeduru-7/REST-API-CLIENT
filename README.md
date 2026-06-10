# REST-API-CLIENT
TASK 2:REST API CLIENT

In modern software development, a Java program that handles HTTP requests and parses JSON responses serves as a bridge between your application and the rest of the internet. This is the fundamental mechanism used to interact with RESTful APIs, such as fetching weather data, processing payments via Stripe, or connecting to social media platforms. Here is a detailed description of how such a program works, the technologies involved, and a functional example.

The Core Components To build this in Java, you typically need two main pieces: The HTTP Client: This sends the request (like a browser does) to a URL and waits for a response. Since Java 11, the built-in java.net.http.HttpClient is the standard choice. The JSON Parser: API responses are usually returned as JSON (JavaScript Object Notation) strings. Java does not "understand" JSON by default, so we use a library like Jackson or Gson to convert that string into a Java Object (a process called Deserialization).
The Technical Workflow A typical execution follows these four steps: Request Construction: You define the Endpoint (URL), the Method (GET to retrieve data, POST to send data), and any required Headers (like API keys for security). Execution: The HttpClient sends the request across the network. Response Handling: The program receives an HttpResponse, which contains a status code (e.g., 200 for success, 404 for not found) and the Body (the JSON data). JSON Mapping: The JSON parser takes the raw string and maps it to a POJO (Plain Old Java Object), allowing you to access the data using standard getter methods like user.getName().


OUTPUT:
<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/3e0b9705-d6c4-455e-8de1-dfa11406c363" />
