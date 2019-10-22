## Kata Maxibon for Kotlin.

During this kata we will try to find how to use property based testing from different points of view:

* Using [TDD][tdd].


## Getting started

Jobandtalent developers love ice cream. And one of our favorites ice cream is named Maxibon:

![Maxibon][maxibon]

Summer is comming and our small team sometime needs Maxibons to work better. But in the Jobandtalent HQs finding a Maxibon is not always easy. We start every week with 10 Maxibons but once there are just 2 Maxibons or less we need to buy more.

Jobandtalent developers can consume zero or a positive number of maxibons. The Jobandtalent team is 
composed by five engineers and everytime some of these engineers go to the kitchen they grab some maxibons as follows:

* If the developer is Marcos, he grabs three maxibons.
* If the developer is Edu, he grabs one maxibon.
* If the developer is Luis, he does not grab any maxibon.
* If the developer is Chema, he grabs two maxibons.
* If the developer is Rúben, he grabs one maxibon.

When a Jobandtalent engineer goes to the kitchen, they can go in group if needed, and there are just 2 maxibons or less left he has to send a message through the Slack API saying ``"Hi guys, I'm <NAME OF THE DEVELOPER>. We need more maxibons!"``. And the number of maxibons available will be automatically incremented by 10 :). If the number of maxibons left is lower than the number of maxibons the developer tries to get he will get just the number of maxibons available.

## Tasks

Your task as Developer is to resolve this problem or test an already implemented software, 
depending on the path you have choosen before to start.

* If you want to practice TDD write a little piece of software to implement the already described scenario following the TDD cycle.

## Extra tasks:

* Change the initial number of maxibons to be configurable.
* Add the verbose modifier to the properties to review if the generation is working fine.
* Change your production code to check if your tests fail or not.
* Configure the number of generations used per property.

**This repository is ready to build the application, pass the checkstyle and your tests in Travis-CI environments.**

# License

Copyright 2017 Karumi

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

  http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

[maxibon]: ./art/maxibon.jpg
[tdd]: https://en.wikipedia.org/wiki/Test-driven_development
