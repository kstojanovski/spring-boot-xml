# Spring Boot XML
## Introduction
This repository was meant to have an example of XML processing in a Spring Boot context.
## Project Structure (should be state)
Several cases can be used when processing a XML file including:
* API (programmatic) way:
  * Read a XML file from the file system, traverse it node by node, and extract some data into an object.
  * Create a XML file with the API and save it to a file.
* Object-Binding way:
  * Read the XML file through the Jackson API by unmarshalling.
  * Write the XML file through the Jackson API by marshaling.
## Links
* https://www.baeldung.com/jackson-xml-serialization-and-deserialization
* https://medium.com/@ya.aman.ay/how-to-serialize-and-deserialize-xml-with-jackson-in-java-991beeb2752f
