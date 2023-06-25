# SwaggerAndOAPI
This is a repository that contains the swagger and the Open API specifications for APIs. This project was created to build APIs from the swagger (OpenAPI) definition.

# Table of Contents
1. [Install Swagger editor-s](#Swagger-Editors)
2. [Books swagger](#Books-Swagger)

# Swagger Editors
In order to make modifications to the swaggers you will need to install the editor, to do so, you have two different options:
- You can download the de Swagger UI and Editor from this [repository](https://github.com/swagger-api) then create a *http-server* using node:

```console
npm install  -g http-server
```
- You can download the following [VSCode extention](https://marketplace.visualstudio.com/items?itemName=42Crunch.vscode-openapi)

# Books Swagger
This is an API that provides different operations to manage a Book such as:
- Getting all books
- Getting an specific book
- Insert a Book

### API Design
Open API defines an Application Interface (API) using the following structure:

![](./swagger/images/OpenAPI%203.0.png)

#### Parts of the OpenAPI 3.0 structure
#### Info
In this section we can describe the general functionality of the API and provide some contact information about the developers, versioning, terms of services, and license.

#### Servers
In this section we can add information about the API hosting implementation such as the URLs for Production, Development and Testing environments.

#### Secutiry
This section describes the security implemented in the API such as cookies, authorization and authentication to use this resource.

#### Paths
This section has the endpoints and the different operations that this API is able to perform.

#### Tags And ExternalDocs
These two sections have additional information about the API like external links for further reference.

#### Components
This has a set of reusable objects that can be used in different parts of the API.

# SwaggerHub

## Advanced Capabilities
- Domains provide object reusability across APIs
- API management capabilities such as security, versioning, and source control integration
- API definition and documentation hosting
- API mocking and virtualization
- Swagger Editor enhancement

## Benefits
- Promotes consistent API design across organizations and teams
- Eases collaboration amongs API developers
- Reduces time and effort required to design APIs
- Supports parallel development via contract-first approach
- 