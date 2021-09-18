# spacex-client-scala

Unofficial purely functional CLI client written in Scala3 + typelevel stack for SpaceX Apis: https://github.com/r-spacex/SpaceX-API

## Run the tests

```shell
sbt test
```

## Build fat jar 

The project uses `sbt-assembly` to create a "fat" jar
```
sbt assembly
```

The plugin is configured explicitly to run tests on `assembly` task. The generated jar is `spacex-client-scala.jar.jar`
