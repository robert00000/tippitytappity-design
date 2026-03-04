# tippitytappity-design

tippitytappity is a program to practice typing


## Data model

```mermaid
---
title: Bank sign in
---
classDiagram
  class Account{
        - accountNum: int
        - email: string
        + account_name: string
        + password: string
  }
flowchart TB
    Account --> CreditCard
flowchart LR 
    CreditCard
  class CreditCard{
        - storage vector~char~
        + name: string
        + digits: string
        + expiration: string
        + zip: int
  }
  class AccountPage{
        - UUID: uuint
        + Title:  string
        + Balance:  float
  }
  class Database{
        - UUID: vector~uuint~ 
        - Encryption: char
        + info: string
  }
