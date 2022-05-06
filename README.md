# Simple Microservice Based Store
A microservice architecture based store using NestJS, grpc, API gateway and authentication
## Store Architecture
![App Architeture](https://user-images.githubusercontent.com/46327178/160545884-38f8927e-f4e8-4ad9-81ce-d651e2e95467.jpeg)

## Architecture Details
our simple e-commerce has fowlling four main parts:
* API gateway: recieve and manage incoming HTTP requests and forwrd them to right services.
* Authentication Service: this service provides the signing up and signing in for the users and also it's authorize user's request(using JWT tokens)
* Product Service: creating and finding products is provided by this service.
* Order Service: incoming oreders is handled by this service.

The API gateway works with RESTFUL API while other services work with GRPC.

# Installation
```
git clone --recurse-submodules
