# Apache Jena

Welcome to Apache Jena, a Java framework for storing and querying RDF data
and a library for writing Semantic Web applications.

<p align="center"><a href="https://jena.apache.org/">https://jena.apache.org/</a></p>

Jena provides a SPARQL triplestore (Fuseki), an RDF database (TDB), text search, command line tools, an  RDF API, a SPARQL API, and more.

<table>
  <tbody>
    <tr>
      <td>Key 1</td>
      <td>Value 1</td>
    </tr>
    <tr>
      <td>Key 2</td>
      <td>Value 2</td>
    </tr>
  </tbody>
</table>

| What | Where |
|:-----|:------|
| Documentation         | https://jena.apache.org/               |
| Codebase              | https://github.com/apache/jena         |
| Download information  | https://jena.apache.org/download/      |
| Releases              | https://apache.org/dist/jena/          |
| Release Archive       | https://archive.apache.org/dist/jena/  |
| RDF Tutorial          | https://jena.apache.org/tutorials/rdf_api.html |
| SPARQL Tutorial       | https://jena.apache.org/tutorials/sparql.html  |
| Fuseki                | https://jena.apache.org/documentation/fuseki2/ |
| SPARQL Client API     | https://jena.apache.org/documentation/rdfconnection/ |

## Obtaining Apache Jena

The binaries for running a Fuseki server are available in the "apache-jena-fuseki-VERSION" artifact from https://apache.org/dist/jena/binaries.

The command line tools are available in the "apache-jena-VERSION" artifact: https://apache.org/dist/jena/binaries.

The core library is:

    <dependency>
      <groupId>org.apache.jena</groupId>
      <artifactId>apache-jena-libs</artifactId>
      <type>pom</type>
      <version>X.Y.Z</version>
    </dependency>

includes the [Model API](https://jena.apache.org/documentation/rdf/index.html),
[RDFConnection](https://jena.apache.org/documentation/rdfconnection/) for working with SPARQL
and Jena's [SHACL](https://jena.apache.org/documentation/shacl/) implementation.

For more information : https://jena.apache.org/download/maven.html.

## Questions?

See the [Apache jena website](https://jena.apache.org/) for the project website, including documentation.

The users mailing list is users@jena.apache.org (subscription is required, this reduced unwanted email, : send an email to users-subscribe@jena.apache.org).

StackOverflow (tags #sparql, #jena, #fuseki) also has many questions and answers about Apache Jena.

## Contributors

Apache Jena is an open sources and project and welcomes contributions whether by github pull requests.
Please see [Contributing](CONTRIBUTING.md) for details and drop into the developer's mailing list 
dev@jena.apache.org.

The [code on github](https://github.com/apache/jena) - clone, contribute and send a pull request!

For information on building from the source, see ["Build from source"](BUILD.md).
