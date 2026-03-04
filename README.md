# tippitytappity-design

tippitytappity is a program to practice typing


## Data model

```mermaid
classDiagram
  class Account{
        - accountNum: int
        - email: string
        + account_name: string
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
