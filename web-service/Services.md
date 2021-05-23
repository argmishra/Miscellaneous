## Web Services
Web service is a technology to communicate one programming language with another or one device to
another or one component to another.

## Advantages
1. Both XML-Based and annotation based.
2. Loosely Coupled.
3. Ability to be Synchronous or Asynchronous.

## Types
1. SOAP web services = Its full form is Simple Object Access Protocol and it is XML based protocol.
2. RESTful web services =  Its full form is REpresentational State Transfer.

## Difference
| **SOAP**               |**REST**                             |
|------------------------|-------------------------------------|
| It is a protocol       | It is an architectural style        |
| URI to expose logic    | Service interface to expose logic   |
| It cann't use REST     | It can use SOAP                     |
| XML data format only   | Multiple formats                    |
| Strict standard        | No strict standard                  |
| Defines own security   | Inherties from underlying protocols |
| Require more bandwidth | Require less bandwidth              |
| Less preferred         | More preferred                      |

## Java Web Services Tutorial
1. JAX-WS = RPC and Document Style
2. JAX-RS = Jersey and RESTeasy Style

## Richardson Maturity Model
| **LEVELS** |**DESCRIPTION**               |
|------------|------------------------------|
| Level 0    | Only single URI              |
| Level 1    | Multiple URI but one method  |
| Level 2    | Multiple URI but many methods|
| Level 3    | Uses concept of HATEOAS      |