![1_g4OPeVwVbt0HTQo2dkV4ew](https://user-images.githubusercontent.com/37045332/124752079-c6e63580-defd-11eb-8b00-68f42c0f6689.png)
<h1>API-Rest-Java11</h1>
<h3>Desafio técnico IBM</h3>

> Status: concluído 🌐

### Objetivo:
#### Solução back-end para gerenciar sessões de votação.
#### Essa solução deve ser executada na nuvem e promover as seguintes funcionalidades através de uma API RST:
+ Cdastrar uma nova pauta;
+ Abrir uma sessão de votação em uma pauta (a sessão de votação deve ficar aberta por um tempo
determinado na chamada de abertura ou 1 minuto por default);
+ Receber votos dos associados em pautas (os votos são apenas 'Sim'/'Não'. Cada associado é
identificado por um id único e pode votar apenas uma vez por pauta);
+ Contabilizar os votos e dar o resultado da votação na pauta.
Para fins de exercício, a segurança das interfaces pode ser abstraída e qualquer chamada para as interfaces
pode ser considerada como autorizada. A escolha da linguagem,



### Tarefa Bônus 1 - Integração com sistemas externos
#### Integrar com um sistema que verifique, a partir do CPF do associado, se ele pode votar
+ GET https://user-info.herokuapp.com/users/{cpf}
+ Caso o CPF seja inválido, a API retornará o HTTP Status 404 (Not found). Você pode
usar geradores de CPF para gerar CPFs válidos;
+ Caso o CPF seja válido, a API retornará se o usuário pode (ABLE_TO_VOTE) ou não
pode (UNABLE_TO_VOTE) executar a operação

##Tecnologias e Ferramentas
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
