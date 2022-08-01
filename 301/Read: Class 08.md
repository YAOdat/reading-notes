## Readings: APIs

### **[API Design Best Practices](https://docs.microsoft.com/en-us/azure/architecture/best-practices/api-design)**

**1. What does REST stand for?**

Representational State Transfer


**2. REST APIs are designed around a.**

resources, which are any kind of object, data, or service that can be accessed by the client.

**3. What is an identifer of a resource? Give an example.**

The URI for a particular customer order might be:  https://adventure-works.com/orders/1

**4. What are the most common HTTP verbs?**

They are GET, POST, PUT, PATCH, and DELETE.

**5. What should the URIs be based on?**

should be based on nouns (the resource) and not verbs (the operations on the resource).
https://adventure-works.com/orders // Good

https://adventure-works.com/create-order // Avoid

**5. Give an example of a good URI.**

https://adventure-works.com/orders // Good

**6. What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?**

sending a lot of small requests

It is a bad thing that exposes a large number of small resources.

**7. What status code does a successful GET request return?**

HTTP status code 200 (OK).

**8. What status code does an unsuccessful GET request return?**

404 (Not Found).

**9. What status code does a successful POST request return?**

HTTP status code 201 (Created).

**10. What status code does a successful DELETE request return?**

HTTP status code 204

### **[RegExr ](https://regexr.com/)**

**1. How would you match your name using RegEx?**

/yaser\b/g
