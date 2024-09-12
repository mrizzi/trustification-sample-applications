To generate an SBOM, execute:

```shell
mvn org.cyclonedx:cyclonedx-maven-plugin:makeAggregateBom -f <folder-name>
```

where <folder-name> can be `mortgage`, `home-banking`, etc.