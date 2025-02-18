# SUMMARY

Answer all the questions. Please put your answers _after_ the brackets with
point values.

## Transcripts

Paste transcripts into the below sections. Put each within triple back-quotes,
like this:

```
This is an example.
```

All transcripts should start with the first text output from the program.
Provide a transcript even if your code did not work correctly. **Do not** modify
transcripts.

### Transcript 1

_Paste in the transcript for Problem 1. It should show at least one win and one loss
with the text-human combination._ [5 points]

```
Enter a guess: 
sound
Your guess: SOUND
Feedback: +.+..
Enter a guess: 
heart
Your guess: HEART
Feedback: *....
Enter a guess: 
plays
Your guess: PLAYS
Feedback: ...++
Enter a guess: 
round
Your guess: ROUND
Feedback: ..+..
Enter a guess: 
drive
Your guess: DRIVE
Feedback: .....
Enter a guess: 
husky
Your guess: HUSKY
Feedback: *****
Phew
```

```
Enter a guess: 
sound
Your guess: SOUND
Feedback: +.+..
Enter a guess: 
heart
Your guess: HEART
Feedback: *....
Enter a guess: 
plays
Your guess: PLAYS
Feedback: ...++
Enter a guess: 
plane
Your guess: PLANE
Feedback: .....
Enter a guess: 
shows
Your guess: SHOWS
Feedback: ++...
Enter a guess: 
frees
Your guess: FREES
Feedback: ....+
The secret word is: HUSKY
```

### Transcript 2

_Paste in the transcript for Part 2._ [5 points]

```
2024-11-19T18:04:10.210-0800 [QUIET] [system.out] Your guess: ADIEU
2024-11-19T18:04:10.210-0800 [QUIET] [system.out] Feedback: ....+
2024-11-19T18:04:11.216-0800 [QUIET] [system.out] Your guess: CUPPA
2024-11-19T18:04:11.216-0800 [QUIET] [system.out] Feedback: .*...
2024-11-19T18:04:12.222-0800 [QUIET] [system.out] Your guess: GURKS
2024-11-19T18:04:12.222-0800 [QUIET] [system.out] Feedback: .*.*+
2024-11-19T18:04:13.227-0800 [QUIET] [system.out] Your guess: MUSKY
2024-11-19T18:04:13.227-0800 [QUIET] [system.out] Feedback: .****
2024-11-19T18:04:14.234-0800 [QUIET] [system.out] Your guess: TUSKY
2024-11-19T18:04:14.234-0800 [QUIET] [system.out] Feedback: .****
2024-11-19T18:04:15.242-0800 [QUIET] [system.out] Your guess: BUSKY
2024-11-19T18:04:15.242-0800 [QUIET] [system.out] Feedback: .****
2024-11-19T18:04:15.242-0800 [QUIET] [system.out] The secret word is: HUSKY
```

## Logistics

### Did you successfully implement everything that was requested?

_Answer "Yes", or state here which parts did not work or which tests did not
pass._ [1 point]

Yes

### How long did the assignment take?

_Rather than giving a range, if you are unsure, give the average of the range._
[1 point]

3 hours

### Who did you work with and how?

_Discussing the assignment with people not on your team is fine as long as you
don't share code. Please state whether you attended any office hours. We especially
like hearing about helpful TAs._ [1 points]

I worked with Timothy Bernardo who helped me with the implementation of incorporateFeedback for ArtificialPlayer.

### What was your AI usage?

_State explicitly (yes or no) whether you used AI. If so, say which tools you
used and what your prompts were. Your assignment will not be graded if you do
not answer this question._ [1 point]

I did not use AI.

### What resources did you use?

_Please give specific URLs (not "Stack Overflow" or "Google") and state which
ones were particularly helpful._ [2 points]

https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/first.html
I found this website for the first() method helpful when implementing generateGuess in ArtificialPlayer.

## Reflections

_Give **one or more paragraphs** reflecting on your experience with the
assignment, including answers to all of these questions:_

* What was the most difficult part of the assignment?
* What was the most rewarding part of the assignment?
* What did you learn doing the assignment?

_Constructive and actionable suggestions for improving assignments, office
hours, and lecture are always welcome._
[4 points]

The most difficult part of the assignment was Part 2 of implementing ArtificialPlayer. Specifically, making sure the AI
takes into account the specific constraints after each turn. I sometimes kept running into an error where the AI would
repeat the same incorrect guess and then I figured out that I had to add that to my constraints checking that the word
that the AI just guessed is not equal to the guess that it will do next.

The most rewarding part of the assignment was seeing the AI work its magic and guess a word correctly. By doing the
assignment, I learned how many rules there are to making the perfect guess in Wordle.