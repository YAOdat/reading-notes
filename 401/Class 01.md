# Readings: Express


## PUT vs PATCH

PUT is used to update the entire resource, whereas PATCH is used to update partial data of the source.

## Alternatives to JSON-Server:

1. Httpie
2. Mocky
3. Mockoon

## Swagger vs APIDoc.js

Swagger:

```
 responses:
        '200':
          description: OK
        '400':
          description: Bad request. User ID must be an integer and larger than 0.
        '401':
          description: Authorization information is missing or invalid.
        '404':
          description: A user with the specified ID was not found.
        '5XX':
          description: Unexpected error.
``` 
[1](https://swagger.io/docs/specification/describing-responses/)

APIDoc.js:

```
 @apiSuccessExample Success-Response:
 *     HTTP/1.1 200 OK
 
 * @apiErrorExample Error-Response:
 *     HTTP/1.1 404 Not Found
```
[2](https://apidocjs.com/#params)

## SOAP vs ReST

![](https://3.bp.blogspot.com/-zg3xuzcWTXg/Vaj0gLvGabI/AAAAAAAADZU/fhE-v_AXJFA/w1200-h630-p-k-no-nu/SOAP%2Bvs%2BREST%2Bin%2BJava.png)


## Topics Learned:

Web Server
Express
Routing
WRRC

## Preview:

Which 3 things had you heard about previously and now have better clarity on?

1. Express
2. Web Server
3. WRRC

Which 3 things are you hoping to learn more about in the upcoming lecture/demo?
1. Routing
2. Web Server
3. WRRC

What are you most excited about trying to implement or see how it works?
Web Server

