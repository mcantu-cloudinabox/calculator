[![Build Status](https://dev.azure.com/michaelcantu/Calculator/_apis/build/status/mcantu-cloudinabox.calculator?branchName=master)](https://dev.azure.com/michaelcantu/Calculator/_build/latest?definitionId=10&branchName=master)

[![Board Status](https://dev.azure.com/michaelcantu/046bc579-329d-430e-8b14-ea82a28c64ab/15fd5090-5031-4b2c-afe0-156e93b78f51/_apis/work/boardbadge/636aac8e-fe0e-49eb-943a-cbf547cf0398?columnOptions=1)](https://dev.azure.com/michaelcantu/046bc579-329d-430e-8b14-ea82a28c64ab/_boards/board/t/15fd5090-5031-4b2c-afe0-156e93b78f51/Custom.98f10bb8-da6b-4ca5-8366-1c680e9fa3b3/)

Calculator.js: a node.js Demonstration Project
==============================================
An example node.js project, including tests with mocha, that behaves like
a pocket calculator.

The project contains a simple node.js application that exposes REST APIs
to perform arithmetic on integers, and provides a test suite with mocha
and chai.  The `mocha-junit-reporters` package is included to provide XML
output that can be presented in a continuous integration tool like
[Azure DevOps](https://azure.com/devops).

To build, simply:

1. Runs `npm install` to install dependencies.
2. Runs `npm test` to run Mocha and execute the unit tests.

