## Part A: The Critical Distinction


1. WRITING DOWN MY HONEST ANSWERS.


# How have you used AI for coding so far?
ANSWER:
I have use AI so far to understand,generate and debug.


# Do you ask AI for solutions before trying yourself?
ANSWER:
I ask AI to breakdown the question to my understanding.


# Can you explain code you've submitted without AI's help?
ANSWER:
for now i will not be able to explain my code,because i am still a beginner.


 # What would happen if AI was suddenly unavailable during an exam or interview?
 ANSWER:
 I  will read books and answer question based on my understanding.


 2. IDENTIFY YOUR CURRENT PATTERN:


 # Learner B: "AI is my learning amplifier"

     Attempts the problem first

    Asks: "Why does this approach work? What are the trade-offs?"

    Tests understanding by explaining concepts

    Uses AI to explore deeper, not to avoid thinking



3. Write a brief paragraph: Where are you now, and where do you want to be?
ANSWER:
i am currently in my learning stage and i want to be someone who is focused on learning,understands,share my knowlegde with the society and i will be able to do things without the help of AI.


## Part B: The Wrong Way vs. The Right way


1. Write pseudocode for a palindrome check


FUNCTION ispalindrome(text)

SET forward = 0 SET backward = length of text - 1

WHILE forward < backward:

IF text[forward] is not equal to text[backward]:
    RETURN FALSE
          
    INCREMENT forward by 1
    DECREMENT backward by 1


2. Implement your solution in Python



def isPalindrome(text): # define the function

  text = text.replace(" ", "").lower() # remove spaces from character and convert everything to lower case 


  forward = 0  # start at the first index

  backward = len(text) - 1 # start at the end of the index

  while forward < backward:
     # loop until it get to the middle character

    if text[forward] != text[backward]:
     #compares characters from both ends

      return False #if the character did not match is not a palindrome,it return false

    forward += 1  # move the forward pointer one step to the right

    backward -= 1  # move the backward pointer one step to the left

  return True # if all the character matches is a palindrome,it return true




Test with examples:


print(isPalindrome("racecar"))
print(isPalindrome("hello"))
print(isPalindrome("A man a plan a canal panama"))


Debug any issues yourself 
ANSWER
i debug using python playground.


# comment explaining my reasoning 

i wrote a function named ispalindrome that remove space from the character and makes everything a lower case,
create a pointer that access the first and the last index,
if there is a mismatch in our check it returns false otherwise, return true i.e when no mismatch is found.



## Step 2: Strategic AI use After you have a working solution, ask AI:



1. What's the time complexity? 
ANSWER:
It describe the amount of time an algorithm takes to run as a fucntion of the input size.


2. What edge cases am I missing?
ANSWER:
My codes does not handle non-string input safely and ignore punctuation.


3. Alternatives and trade-offs?
ANSWER:

Alternative approaches are different ways to solve the same problem.

Trade-offs are the advantages and disadvantages you accept when choosing one approach over another.




4. How does it perform on very long strings?
ANSWER:
Time grows linearly (0(n))
Memory usage stays constant (0(1))
Your two-pointer solution performs efficiently.
It is safe and scalable for large inputs.



# STEP 3: REFLECTION

What did you learn by struggling first?
ANSWER:
i learnt how palindrome works.



How is your understanding different than if you'd just asked for the solution?
ANSWER:
i would not have deeper understanding of this project.




Can you now implement similar functions (reverse a string, find duplicates) without AI?
ANSWER:
partially.




What mental model did you build? 
ANSWER:
I have build a critical thinking metal model.




## Part C: Testing Your Understanding




def isPalindrome(text):
    clear = ''.join(t.lower() for t in text if t.isalnum())
    forward = 0
    backward = len(clear) - 1
    
    while forward < backward:
        if clear[forward] != clear[backward]:
            return False, forward, backward
        forward += 1
        backward -= 1
    
    return True, None, None




1. edge cases i missed?
ANSWER:
My function did not handle non-string input.


2. how could i make it more efficient?
ANSWER:
it can be efficient when i don't create a new string,moving inward,and ignoring characters that aren't letters or numbers.




## Part D: The Fairness Contract



1. I will use AI when:

I've attempted a problem for at least 20 minutes.

i want to understand why my solution works/doesn't.

To explore alternatives after I have a working solution.

i want a better approach to my code.



2. I will NOT use AI when:

I haven't tried the problem myself.

I'm taking an assessment or test.

I need to build fundamentals.



3. I know I'm using AI fairly when:

I can explain my code without looking at AI's response.

I could solve similar problems without AI.

I feel more confident in my abilities.

i can debug myself.

i can explain my codes in a very understanding way.



SIGNED BY: EYIKWODANI CLEMENTINA ENEWA
DATE: 20TH FEBRUARY,2026 




## Part E: Real-World Scenario Analysis


1. Interview: "Explain how you'd implement a caching system." If you always relied on AI, can you answer?

ANSWER:
I would not be able to do that excellently.



2. Production bug at 2 AM: AI is unavailable. Can you debug code you don't fully understand?

ANSWER:
No,i will not be able to do that.


3.New tech with little documentation: If you never learned to read docs and experiment, what happens?

ANSWER:
 I will not have a good understanding of the basis and fundamental of some language


 4. How does using AI fairly now prepare you for these scenarios?

ANSWER:
AI will help build my knowledge in this scenarios and not completly give me answers.



## Part F: Building Irreplaceable Skills



1. problem decomposition     rating:   1/5

2. system thinking            rating:  2/5

3. critical evaluation         rating   2/5

4. debugging mindset           rating   1/5

5. conceptual  understanding ("the why")  1/5





## Action plan: 3 specific actions this week to improve it without outsourcing thinking to AI.



1. i will create a studing time.

2. i will focused more on understanding the fundamentals.

3. i will start giving myself task at the end of every quest to test my understanding.












