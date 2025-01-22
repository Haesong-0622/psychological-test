#### Implement psychological testing with Python 

#### How the program works

1. main menu
When running the program, the user selects one of the five psychological tests:
MBTI test
Psychopath Test
a psychological test of values
Adult Attachment Type Test
a love psychology test
The test function is called according to the selected number.
2. After the test is finished
After completing the test, ask the user if they want to exit the program or proceed with another test.
Depending on the input, the program will exit or return to the menu.

#### Description of each test

1. MBTI Test (mbti_test)
The user answers a total of 12 questions with a or b.
Each question measures a specific MBTI characteristic (E/I, S/N, F/T, P/J).
The score of each attribute is accumulated according to the answer selected by the user.
The higher score side determines the final MBTI type.
Output: MBTI type for the user.
2. Psychopath Test (psychopath_test)
For 20 questions, choose one of 1 (not), 2 (normal), and 3 (yes).
Evaluate your psychopathic temperament by summing up your answer scores:
0-10 points: normal
11-18 points: Attention required
19-24 points: some psychopathic disposition
25 Points or More: Psychopaths
Output: Total score and result message.
3. Value_test
Read a short story (the story of a musician and a poet trying to cross a river), and choose the worst person among the characters.
The choice determines the value (lover, self, work, goals, friends) that you value most.
Output: Value description based on selection.
4. Adult attachment type test (attachment_test)
Answer 33 questions from 1 (not at all) to 5 (very much so).
Determine the type of attachment by calculating the avoidance and anxiety scores:
Stable attachment: low avoidance, low anxiety
Immersive attachment: low avoidance, high anxiety
Rejected Avoidance Attachment: High Avoidance, Low Anxiety
Fear-type avoidance attachment: high avoidance, high anxiety
Output: Attachment type and description.
5. Love_psychology_test
Present a situation in which you evaluate your friend's lover.
Let the user choose one of the four answers given to them.
Your choice will determine your love propensity:
a failed relationship student
What a smart guy
Sportsman type
a princely soldier/princess soldier
Output: Dating tendencies and explanations.

#### Key features of the entire code

Validation of Input: If the user enters an incorrect value, a warning message is output and the user receives the input again.
Various feedbacks: Provide detailed explanations and advice based on test results.
Repeat Run: You can continue with another test unless the user chooses to exit.

#### Please check the code

#### Thank you :)
