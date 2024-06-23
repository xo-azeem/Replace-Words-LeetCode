# Replace Words

LeetCode Q # 648.

In English, we have a concept called root, which can be followed by some other word to form another longer word - let's call this word derivative. For example, when the root "help" is followed by the word "ful", we can form a derivative "helpful".
Given a dictionary consisting of many roots and a sentence consisting of words separated by spaces, replace all the derivatives in the sentence with the root forming it. If a derivative can be replaced by more than one root, replace it with the root that has the shortest length.</br></br>
Return the sentence after the replacement.

Example 1:

>Input: dictionary = ["cat","bat","rat"], sentence = "the cattle was rattled by the battery"</br>
>Output: "the cat was rat by the bat"

Example 2:

>Input: dictionary = ["a","b","c"], sentence = "aadsfasf absbs bbab cadsfafs"</br>
>Output: "a a b c"

My Solution Analysis:

<div align = "center">

  ![image](https://github.com/xo-azeem/Replace-Words-LeetCode/assets/171427226/8b85e47b-8772-44f8-b62d-bd2a1f57c2d7)

  Time complexity: O(n).</br>Space complexity: O(n^2).
</div>
