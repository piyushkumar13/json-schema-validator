One of the features of this library is to validate the YAML file in addition to the JSON. In fact, the main use case for this library is to be part of the light-4j framework to validate the request/response at runtime against the OpenAPI specification file openapi.yaml. If you are not using light-4j, you need to load the YAML with https://github.com/FasterXML/jackson-dataformats-text first, and then everything is the same as JSON.

### Usage

Add the dependency

```
        <dependency>
            <groupId>com.fasterxml.jackson.dataformat</groupId>
            <artifactId>jackson-dataformat-yaml</artifactId>
            <version>2.10.1</version>
        </dependency>
```

and created object mapper using yaml factory i.e ObjectMapper objMapper =new ObjectMapper(new YAMLFactory());

