# README

## Commands Reference

### To Install or Deploy

Parent project includes test configuration, but it does not actually have tests.

Make sure to skip tests during deployment or installation:

    mvn clean install -DskipTests
    mvn clean deploy -DskipTests

## References

1. [MUnit - To Perate the MUnit Maven Plugin](https://docs.mulesoft.com/munit/2.1/munit-maven-plugin) contains instruction how to skip tests.
