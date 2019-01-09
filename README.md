# Kotlin coding puzzles

This repository contains a set of programming puzzles that are solved using [Kotlin](https://kotlinlang.org/) language (no worries hints and
solutions are here as well). Goal of this repository is to help you to practice your coding skills and prepare for
[whiteboard coding](https://www.quora.com/What-is-whiteboard-coding) interviews. Keep in mind that each puzzle may have more than one solution


# How do I start?

## Opening this project
This project is [Android Studio](https://developer.android.com/studio/) project because it allows quick out of the box JUnit test support
and it is free.

1. Install Android Studio
2. Install git `brew install git` using cmd
3. Import project by using Android Studio menu: `File -> New -> Project From Version Control -> Git`
4. Enter Repository URL `https://github.com/igorwojda/kotlin-coding-puzzle.git`  and click `clone`
5. Navigate to [app/src/test/java/com/igorwojda](app/src/test/java/com/igorwojda/) folder in `Project` view or
   [app/java/com (test)/igorwojda](app/src/test/java/com/igorwojda/) in `Android` view in project panel.
6. Optionally install [Markdown Navigator](https://plugins.jetbrains.com/plugin/7896-markdown-navigator) plugin for Android studio to have
   ice preview of markdown files (files containing puzzles description)

## Puzzle structure
Each puzzle is located in separate package and it contains 3 files
([screen](./misc/images/SampleTask.png)):
* `Puzzle.md` - description of the puzzle
* `Puzzle.kt` - contains empty method/class where puzzle should be solved and set of tests to run
* `PuzzleSolution.kt - file that contains one or more puzzle solutions (encapsulated in Kotlin `object` just to avoid conflicts with
  other coding puzzles)

## Running tests

Open `Puzzle.kt` file for a any puzzle. Locate class with `Test` suffix (`PuzzleTest`). Click on the green green arrow close to line
number to run one or more tests in the class
([screen](./misc/images/RunTest.png)). After running the test you can rerun last
configuration using `Run command` (`⌘ + R`).

Larger puzzles will have larger test base, so tests have to be uncommented one by one while solving various steps of the given puzzle.

# Coding puzzles
Before solving any task I strongly encourage you to take a pen, piece of paper, take your time and think about the puzzle. Take your time
before you take a look at the presented solution (sometimes one-night sleep is all we need before solution pop-ups into our head).

Order of the programming puzzles is random for now, however, some of them may contain a reference to puzzles that should be solved before
to make the final puzzle easier. It all up to you how you approach this, just remember that to succeed you need to practice often, repeat
same tasks multiple times be patient and persistent over time.

## Algorithms

1. [Anagram](app/src/test/java/com/igorwojda/codingpuzzle/anagram/Anagram.md)
2. [Sentence capitalization](app/src/test/java/com/igorwojda/codingpuzzle/calitalisesentence/CapitalizeSentence.md)
3. [Fibonacci](app/src/test/java/com/igorwojda/codingpuzzle/fibonacci/basic/Fibonacci.md)
4. [Fibonacci add recursive cache](app/src/test/java/com/igorwojda/codingpuzzle/fibonacci/recursivecached/FibonacciRecursiveCached.md)
5. [Fizz Buzz](app/src/test/java/com/igorwojda/codingpuzzle/fizzbuzz/FizzBuzz.md)
6. [List chunking](app/src/test/java/com/igorwojda/codingpuzzle/listchunk/ListChunk.md)
7. [Spiral matrix generator](app/src/test/java/com/igorwojda/codingpuzzle/matrix/spiralnumbers/SpiralNumbers.md)
8. [Palindrome](app/src/test/java/com/igorwojda/codingpuzzle/palindrome/basic/Palindrome.md)
9. [Tolerant palindrome](app/src/test/java/com/igorwojda/codingpuzzle/palindrome/tolerant/TolerantPalindrome.md)
10. [Range contains range?](app/src/test/java/com/igorwojda/codingpuzzle/rangecontainsrange/RangeContainsRange.md)
11. [Factorial](app/src/test/java/com/igorwojda/codingpuzzle/factorial/Factorial.md)
12. [Print number](app/src/test/java/com/igorwojda/codingpuzzle/printnumber/basic/PrintNumber.md)
13. [Print number with steps](app/src/test/java/com/igorwojda/codingpuzzle/printnumber/steps/PrintNumberWithSteps.md)
14. [Int reversal](app/src/test/java/com/igorwojda/codingpuzzle/reverseint/ReverseInt.md)
15. [Pyramid shape](app/src/test/java/com/igorwojda/codingpuzzle/shape/pyramids/Pyramids.md)
16. [Steps shape](app/src/test/java/com/igorwojda/codingpuzzle/shape/steps/Steps.md)
17. [Max occurring char](app/src/test/java/com/igorwojda/codingpuzzle/string/maxchar/MaxOccurrentChar.md)
18. [String reversal](app/src/test/java/com/igorwojda/codingpuzzle/string/reverse/Reverse.md)
19. [Find the vowels](app/src/test/java/com/igorwojda/codingpuzzle/string/vowels/Vowels.md)

## Data structures

1. [Int queue](app/src/test/java/com/igorwojda/datastructure/queue/int/IntQueue.md)
2. [Generic queue](app/src/test/java/com/igorwojda/datastructure/queue/generic/GenericQueue.md)
3. [Int stack](app/src/test/java/com/igorwojda/datastructure/stack/int/IntStack.md)
4. [Combine two queues](app/src/test/java/com/igorwojda/datastructure/queue/weave/Weave.md)
5. [Generic stack](app/src/test/java/com/igorwojda/datastructure/stack/generic/GenericStack.md)
6. [Two stack queue](app/src/test/java/com/igorwojda/datastructure/queue/twostack/TwoStackQueue.md)
7. [Linked list](app/src/test/java/com/igorwojda/datastructure/linkedlist/base/LinkedList.md)
8. [Linked list midpoint](app/src/test/java/com/igorwojda/datastructure/linkedlist/midpoint/Midpoint.md)
9. [Circular linked list?](app/src/test/java/com/igorwojda/datastructure/linkedlist/circularcheck/CircularCheck.md)
10. [Linked list take n-th element from last](app/src/test/java/com/igorwojda/datastructure/linkedlist/fromlast/FromLast.md)
11. [Tree traversal](app/src/test/java/com/igorwojda/datastructure/tree/traversal/TreeTraversal.md)
11. [Tree level width](app/src/test/java/com/igorwojda/datastructure/tree/levelwidth/LevelWidth.md)

# Contribute

If you have any doubts, found a puzzle, have a better solution or simply you want to [add new puzzle](/misc/wiki/adding_new_puzzle.md)
please create PR or open a new issue.

# References
* [Big O Notation](https://medium.com/karuna-sehgal/a-simplified-explanation-of-the-big-o-notation-82523585e835)
* [Cracking the Coding Interview](https://www.amazon.co.uk/Cracking-Coding-Interview-6th-Programming/dp/0984782850/ref=pd_lpo_sbs_14_img_0?_encoding=UTF8&psc=1&refRID=ZKQA82B0MSD2GYPCCZYQ)

# Inspiration

For more detailed explanations of various puzzles please take a look at these courses and books:
* [The Coding Interview Bootcamp Algorithms + Data Structures](https://www.udemy.com/coding-interview-bootcamp-algorithms-and-data-structure/)

