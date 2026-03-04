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
    id1(Account) --> id2(CreditCard)
flowchart LR 
    id2(CreditCard)
  class CreditCard{
        - storage vector~char~
        + name: string
        + digits: string
        + expiration: string
        + zip: int
  }
