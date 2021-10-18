![1_g4OPeVwVbt0HTQo2dkV4ew](https://user-images.githubusercontent.com/37045332/124752079-c6e63580-defd-11eb-8b00-68f42c0f6689.png)
<h1>API-Rest-Java 11</h1>
<h3>IBM technical challenge</h3>

> Status: Done 🌐

### goal:
#### Back-end solution to manage voting sessions.
#### This solution must run in the cloud and promote the following features through an RST API:
+ Register a new agenda;;
+ Open a voting session on an agenda (the voting session must be open for a specified amount of time in the opening call or 1 minute by default);
+ Receive votes from members on agendas (votes are only 'Yes'/'No'. Each member is identified by a unique id and can vote only once per agenda);
+ Count the votes and give the result of the vote on the agenda.
For exercise purposes, the security of the interfaces can be abstracted and any calls to the interfaces can be considered as authorized. The choice of language,

### Bonus Task 1 - Integration with external systems
#### Integrate with a system that checks, from the member's CPF, whether he can vote
+ GET https://user-info.herokuapp.com/users/{cpf}
+ If the CPF is invalid, the API will return HTTP Status 404 (Not found). You can use CPF generators to generate valid CPFs;
+ If the CPF is valid, the API will return if the user can (ABLE_TO_VOTE) or cannot (UNABLE_TO_VOTE) execute the operation

####code in portuguese

## Technologies and Tools
<table>
  <tr> 
    <td>Java</td>
    <td>PostgreSQL</td>
    <td>SpringToolSuite4</td>
    <td>Postman</td>
    <td>Windows</td>
  </tr>
  <tr> 
    <td>11</td>
    <td>9.5*</td>
    <td>4.8.1.RELEASE</td>
    <td>7*</td>
    <td>10</td>
  </tr>
</table>
