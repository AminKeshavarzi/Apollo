[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

## Orchestration of an application using the [Apollo runtime system](https://apollowf.github.io/) developed
by the [DPS group](https://dps.uibk.ac.at/) of the [University of Innsbruck](https://www.uibk.ac.at/index.html.en)

### To access the required folders and files switch to master branch

## Task 1
Problem:
In this project, your goal is the implementation of an application to search through a given text string and count the
occurrences of a given string pattern in that text. The input and output of the application, thus, look as follows:<br>
Input:
–    A (potentially large) text string t <br>
–    A pattern string p <br>
–    An integer w  deﬁning the number of words per text batch <br>
–    
Output:
–    The number r  of occurrences of the pattern string in the text string <br>

### Solution:
- Defining workflow using [Apollo AFCL editor](https://github.com/Apollo-AFCL/AFCLEditor) --> Generated .yaml file is task1.yaml and exist in demoWfs folder
- Defining Python functions --> See [How to Implementing and Deploy Serverless Function Resources](https://github.com/Apollo-Core/Tutorial/tree/master/Part_2) and [How to Implement and Deploy Function Code as a Docker Image](https://github.com/Apollo-Core/Tutorial/tree/master/Part_3)
- [Running the implemented application](https://github.com/Apollo-Core/Tutorial/tree/master/Part_3.5)

### Points:
- To pull Docker image of Count function run `docker pull keshavarzi/count:latest`
- To pull Docker image of Split function run `docker pull keshavarzi/split:latest`
- To pull Docker image of Match function run `docker pull keshavarzi/match:latest`
