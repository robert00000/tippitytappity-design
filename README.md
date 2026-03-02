# tippitytappity-design

tippitytappity is a program to practice typing


## Data model

```mermaid
classDiagram
  ExampleParent <|-- ExampleChild
  class ExampleParent{
        - name: string
        - email: string
        - password: string
        + login(user: string, pass: string) boolean
        + get_email() string
  }
  class ExampleChild{
        - badges vector~string~
        + add_badge(title: string)
        + get_badges() vector~string~
  }
  class Login{
        - accountNum: int
        + name: string
        + password: string
  }
  class CreditCard{
        - storage vector~char~
        + name: string
        + digits: string
        + expiration: string
        + zip: int
  }
```
