
TestLink Java API is a Java API that interfaces TestLink XML-RPC API. This API lets you call TestLink internal
methods such as createTestProject, uploadAttachment, getTestProjectByName among others.

## Building

The project is built with Maven:

    mvn

You can also use the Docker files included in this project repository to set up an environment
with the PHP TestLink project. Simply run:

    docker-compose up
    
That should create two containers (`web` and `db`). The MySQL database will be available on
`localhost:3306`, and the web application on `http://localhost:8000`.

## Versioning

The API version matches the version of TestLink it was developed for. So for TestLink 1.9.15, you should use
testlink-java-api-1.9.15-x. Where x is an internal sequential number, used to distinguish between project releases.

If you use the API version 1.9.15-0 against TestLink 1.9.16, there is no guarantee it will work.
 
https://www.youtube.com/watch?v=CktDiS_-n_8
