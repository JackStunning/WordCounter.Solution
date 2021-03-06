# Csharp-WordCounter

#### _Counts how many times a word occurs in a string, 3/6/2020_

#### By _**Jack Dunning**_

## Description

_This is an app that can take strings, a word and a sentence and find if the word occurs in the sentence._

## Setup/Installation Requirements

* _Download .NET from here: https://dotnet.microsoft.com/download/dotnet-core/current_
* _Download dotnet script in the Terminal with this command { dotnet tool install -g dotnet-script }_
* _In the Terminal run this command dotnet build_
* _In the Terminal run this command dotnet run_

## Specs

  * _Spec:_ When user runs dotnet run will recieve text in terminal.
      * _Input:_ dotnet run
      * _Output:_ "Enter a word"

  * _Spec:_ If user enters a word.
      * _Input:_ "cat"
      * _Output:_ "Enter a sentence"

  * _Spec:_ If user enters a sentence.
      * _Input:_ "I have a cat"
      * _Output:_ 1

  * _Spec:_ If user enters a sentence with the word mulitple times.
      * _Input:_ "cat cat cat cat cat cat cat"
      * _Output:_ 7

  * _Spec:_ If user enters a sentence without the word.
      * _Input:_ "No Match"
      * _Output:_ 0

  * _Spec:_ If user enters a word or sentence without letters it still works.
      * _Input:_ "userWord: '!@#$', userSentence: '!@#$ %^&*'"
      * _Output:_ "Matches: 1"

  * _Spec:_ If user enters a word or sentence with same or different symbols at the end will match.
      * _Input:_ "userWord: 'Hello.', userSentence: 'Hello, World.'"
      * _Output:_ "Matches: 1"

## Known Bugs

_No known bugs_

## Support and contact details

_Email: JackStunning9001@gmail.com_

## Technologies Used

_C#, .NET, MSTest_

### License

*Copyright (c)

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN*

Copyright (c) 2020 **_Jack Dunning_**