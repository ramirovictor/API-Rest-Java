![Java Logo](https://user-images.githubusercontent.com/37045332/124752079-c6e63580-defd-11eb-8b00-68f42c0f6689.png)

# API-Rest-Java 11 
## IBM Technical Challenge

> **Status:** 🌐 Done

## 🎯 Goal
Back-end solution to manage voting sessions. This solution must:

- Run in the cloud
- Provide the following features through a REST API:
  - 📌 Register a new agenda
  - ⏲️ Open a voting session on an agenda (the voting session must be open for a specified amount of time in the opening call or default to 1 minute)
  - ✅ Receive votes from members on agendas (votes are only 'Yes' or 'No'. Each member is identified by a unique ID and can vote only once per agenda)
  - 📊 Count the votes and provide the result of the vote on the agenda.

_Note: For exercise purposes, the security of the interfaces can be abstracted, and any calls to the interfaces can be considered as authorized._

## 🌟 Bonus Task 1 - Integration with External Systems
Integrate with a system that verifies, using the member's CPF, whether they are eligible to vote:

- GET `https://user-info.herokuapp.com/users/{cpf}`
  - If the CPF is invalid, the API returns HTTP Status 404 (Not Found). Use CPF generators to produce valid CPFs.
  - If the CPF is valid, the API will indicate if the user can (`ABLE_TO_VOTE`) or cannot (`UNABLE_TO_VOTE`) perform the operation.

_Note: Code is in Portuguese._

## 💼 Technologies and Tools
| Technology         | Version         |
|--------------------|-----------------|
| Java               | 11              |
| PostgreSQL         | 9.5*            |
| SpringToolSuite4   | 4.8.1.RELEASE   |
| Postman            | 7*              |
| Windows            | 10              |
