# Simple embedded HTTP server example for Java with Undertow

This example repository goes with the article at:

<https://www.tutorialworks.com/java-simple-http-server-undertow/>

To run this demo:

```shell
mvn clean package

java -jar target/java-http-server-undertow-1.0-SNAPSHOT-jar-with-dependencies.jar
```

To test it, go to <http://localhost:8080/> in your browser.

To stop the server, press Ctrl-C.

## Technologies used

* [Maven](https://maven.apache.org/) - Dependency Management
* [Undertow](http://undertow.io/) - Embedded HTTP server

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
