# <p align="center">GoIT - HW 6 </br>Cypress Github Actions</p>

## <p align="center">Main goal</p>

The main goal was to make Github Actions Workflow, that initialize tests automaticly when new code is pushed to repository

## <p align="center">Resources used</p>

- Code from `cy-API-Tests` Repository

  > [Link to Repository](https://github.com/MioLuczak/cy-4-api-tests)

  - Http Bin API </br>

    > API that handles HTTP requests </br> [Link to API](https://httpbin.org/) </br> _Credits of API goes to their respective owner_

  - Cypress

    > npm package </br> [Link to package](https://www.npmjs.com/package/cypress)

  - http-server

    > npm package that runs simple http-server</br> [Link to package](https://www.npmjs.com/package/http-server)

## <p align="center">Files info</p>

- [httpAPI.cy.js](./cypress/e2e/httpAPI.cy.js)

  > Main test file, with test suites and test cases

- [main.yml](.github\workflows\main.yml)

  > Main workflow file, that describe jobs needs to be done on push to repository

## <p align="center">Execution</p>

|         |          | Tests  |        |         |
| :-----: | :------: | :----: | :----: | :-----: |
| In Spec | Executed | Passed | Failed | Skipped |
|   23    |    23    |   23   |   0    |    0    |

|           Workflows           |                                                              Link                                                               |
| :---------------------------: | :-----------------------------------------------------------------------------------------------------------------------------: |
|   CI/CD workflow trigger #2   | [Permalink to workflow summary](https://github.com/MioLuczak/cy-6-CI_CD/actions/runs/9990810979/attempts/1#summary-27612272189) |
| Change with in Cypress run #1 | [Permalink to workflow summary](https://github.com/MioLuczak/cy-6-CI_CD/actions/runs/9990774977/attempts/1#summary-27612156182) |
