# 1. Learning to Use AI Ethically as a Coder

# How have you used AI for coding so far?

As a coder, I've found AI tools incredibly helpful for generating code snippets, debugging, and learning new programming concepts. However, I've also learned the importance of using these tools ethically and responsibly.

I used to rely on AI mainly as a shortcut to get code written quickly. With time, I realized that if I want to become a real developer, I need to understand the logic myself before asking for help. Now I try to solve problems on my own first, and then I use AI to improve what I wrote, check my logic, or learn new concepts.

My goal is not only to write working code, but to understand why it works, so that I can explain it clearly in real situations such as interviews, exams, or production debugging. By using AI as a tool and not a replacement for thinking, I am building real skills that I can depend on even when AI is not available.

# Do you ask AI for solutions before trying yourself?

No — I always try to face the problem on my own first.
I sit with the code, think through the logic, and attempt a solution using whatever knowledge I already have. Only after I’ve tried, tested, failed a little, and understood where my thinking might be weak do I turn to AI for support.

AI becomes a guide after effort, not a shortcut before it.
That way, I build real skill, not borrowed answers.

# Can you explain code you've submitted without AI's help?

Yes — when the code is written by me, I can explain how it works without needing AI. I understand the logic, the flow, and why each part is written the way it is.

However, if the code was generated mostly by AI without my involvement, then explaining it becomes much harder. I may know what it does on the surface, but I wouldn’t fully understand the reasoning behind key decisions. That’s a sign that I must take ownership of the code I use, not just copy it.

So the goal is clear:
Even if AI helps, I should always make sure I truly understand the code — so I can explain it and defend it confidently anytime.

# What would happen if AI was suddenly unavailable during an exam or interview?

If AI became unavailable during an exam or interview, the situation would immediately test how much I have truly learned. If I relied too heavily on AI to produce answers without understanding them, I would struggle to explain my reasoning or develop a solution on my own. However, if I have been using AI as a learning tool rather than a crutch—practicing, thinking, and solving problems first on my own—I would still be able to work through the challenge. My performance would depend entirely on the knowledge I have built, not on whether the tool is available.

# 2. Identify your current pattern: Which learner are you now? Learner A: "AI is my answer generator"

Basically, if I had been using AI merely as a basic tool to generate code, I would have a big problem understanding what the AI wrote, why it wrote it that way, how it works, and how all the pieces fit together—something that would make it much harder to fully grasp and be able to explain in a short amount of time.

# Asks: "Write a function that does X"

If I asked AI to write something for me, it would most likely give me working code, but I wouldn’t know how or why it works, so I wouldn’t actually learn anything from it.

# Copies code without reading carefully

Copying code without even reading it would lead to huge problems and major gaps in my understanding and knowledge, because I wouldn’t know how or why the AI wrote it, or how the solution works. As a result, I would not be able to explain it or understand it at all.

# Moves on once it works

Sure, it would be faster, but you wouldn’t have the ability to understand the code or the logic behind it, so the problems I mentioned earlier would exist

# Cannot explain how the code works

Surely, this would be the natural outcome if AI kept writing the code instead of me, and I didn’t have the basic skills to understand how and why it works. It’s 100% certain that I wouldn’t be able to explain it at all.

# Learner B: "AI is my learning amplifier"

# Attempts the problem first

Basically, I always try to write my own code first so that I can apply my own logic and architecture. This way, I understand how it works and the reasoning behind it. After that, I use AI to improve it or make my code cleaner and more efficient.

# Asks: "Why does this approach work? What are the trade-offs?"

I ask questions like, “Why does this approach work? What are the trade-offs?” to make sure I fully understand the reasoning behind my solution. This helps me think critically about alternatives, potential limitations, and ways to improve the code rather than just accepting it as correct.

# Tests understanding by explaining concepts

I check my understanding by explaining the concepts involved, either to myself or in writing. This helps me ensure I truly grasp how the code works, why each part is needed, and how different components interact, rather than just running it and assuming it’s correct.

# Uses AI to explore deeper, not to avoid thinking

I use AI as a tool to deepen my understanding and explore alternative approaches, optimizations, or edge cases. I don’t use it to bypass thinking; instead, I first try to solve and reason through the problem myself, then leverage AI to expand or refine my knowledge.

# Write a brief paragraph: Where are you now, and where do you want to be?

Right now, I use AI as a learning amplifier. I try to solve coding problems on my own first, then I use AI to help me understand deeper concepts, find better solutions, or consider edge cases I might have missed. In the future, I want to become even more independent and confident in my coding skills, able to solve complex problems without relying on AI, while still using it thoughtfully as a guide to improve and expand my knowledge.

# Part B: The Wrong Way vs. The Right Way
Challenge: Implement a simple function to check if a string is a palindrome.
Track A — The Wrong Way (observe but DO NOT do this):

# Immediately ask AI for the function

def is_palindrome(s):
    return s == s[::-1]

# Copy the code

Copying the code without reading or understanding it means you take a solution as-is from AI (or another source) and use it. While it might make your program work immediately, you won’t really learn the logic, reasoning, or structure behind it, and you’ll struggle to explain, modify, or debug it later.

# Test it, submit it, move on
print(is_palindrome("racecar"))  # True
print(is_palindrome("hello"))    # False

Why this fails: You learn nothing, can't handle variations, can't explain your code, and train yourself to be dependent

# Track B — The Right Way (DO THIS): Step 1: Attempt independently

# Write pseudocode for a palindrome check

'''
FUNCTION is_palindrome(text):
    # 1. Read the original text and split each character into a separate element
    letters = split_into_characters(text)

    # 2. Put the letters in reverse order
    reversed_letters = reverse(letters)

    # 3. Compare the original letters with the reversed ones
    IF letters == reversed_letters:
        RETURN True  # It is a palindrome
    ELSE:
        RETURN False  # It is not a palindrome
'''

# Implement your solution in Python

def is_palindrome(text):
    # remove spaces and lowercase
    cleaned = "".join(text.lower().split())
    reversed_text = cleaned[::-1]
    return cleaned == reversed_text

# Test with examples: racecar, hello, A man a plan a canal Panama

# Tests

print(is_palindrome("racecar"))                     # True
print(is_palindrome("hello"))                       # False
print(is_palindrome("A man a plan a canal Panama")) # True 

# Debug any issues yourself

If you debug issues yourself, you actively engage with the code and learn how it behaves. You develop problem-solving skills, understand the underlying logic, and build confidence in fixing errors without relying on AI. This approach turns mistakes into valuable learning opportunities rather than just obstacles.

# Add comments explaining your logic

def is_palindrome(text):
    # Step 1: Convert the text to lowercase to make the comparison case-insensitive
    # and remove all spaces to ignore them in the palindrome check
    cleaned = "".join(text.lower().split())
    
    # Step 2: Reverse the cleaned text using slicing [::-1]
    reversed_text = cleaned[::-1]
    
    # Step 3: Compare the cleaned text with its reversed version
    # If they are the same, the text is a palindrome and return True
    # Otherwise, return False
    return cleaned == reversed_text

# Step 2: Strategic AI use After you have a working solution, ask AI:

# "I wrote a function to check palindromes. Here's my approach:
def is_palindrome(text):
    # remove spaces and lowercase
    cleaned = "".join(text.lower().split())
    reversed_text = cleaned[::-1]
    return cleaned == reversed_text

# What's the time complexity?
# AI Response:
The time complexity of your palindrome checking function is O(n), where n is the length of the input string. This is because you need to iterate through the string to clean it (remove spaces and convert to lowercase) and then again to create the reversed version for comparison.
# What edge cases am I missing?
# AI Response:
Some edge cases you might want to consider include:
1. Empty strings: An empty string should be considered a palindrome.
2. Strings with punctuation: You may want to ignore punctuation marks when checking for palindromes.
3. Single character strings: Any single character string should be considered a palindrome.

# Alternatives and trade-offs?
# AI Response:
Your current approach is efficient and straightforward, but here are some alternatives and their trade-offs:
1. Two-pointer technique: Instead of creating a reversed string, you could use two pointers (one at the start and one at the end) to compare characters moving towards the center. This approach uses O(1) space but still has O(n) time complexity.
2. Regular expressions: You could use regex to clean the string by removing non-alphanumeric characters. This can make your code cleaner but may introduce additional overhead in terms of performance.

# How does it perform on very long strings?
# AI Response:
Your function should perform well on very long strings, maintaining O(n) time complexity. However, keep in mind that the space complexity is also O(n) due to the creation of the cleaned and reversed strings. For extremely long strings, this could lead to higher memory usage. If memory is a concern, consider using the two-pointer technique mentioned earlier to reduce space complexity to O(1).  

# Step 3: Reflection

# What did you learn by struggling first?

By struggling first, I learned to think critically about the problem and develop my own solution. This process helped me understand the logic behind checking for palindromes, such as cleaning the input and comparing characters. It also made me more aware of potential edge cases and the importance of testing. Struggling through the problem allowed me to build confidence in my coding skills and reinforced the value of persistence and problem-solving in programming.

# How is your understanding different than if you'd just asked for the solution? 

My understanding is much deeper because I had to actively engage with the problem, think through the logic, and implement the solution myself. If I had just asked for the solution, I would have received a piece of code without fully grasping how it works or why certain decisions were made. By struggling first, I developed problem-solving skills, learned to debug issues, and gained insights into edge cases and optimizations that I might have overlooked otherwise. This hands-on experience is invaluable for building lasting knowledge and confidence in coding. 

# Can you now implement similar functions (reverse a string, find duplicates) without AI?

Yes, I can now implement similar functions like reversing a string or finding duplicates without AI. The process of struggling through the palindrome problem has strengthened my understanding of string manipulation and algorithmic thinking. For example, to reverse a string, I can use slicing or a loop to build the reversed version. To find duplicates, I can use data structures like sets or dictionaries to track occurrences of elements. The skills and confidence I've gained from solving the palindrome problem will help me tackle these similar tasks independently.

# What mental model did you build?
The mental model I built revolves around a structured approach to problem-solving in coding. It includes the following key steps:
1. Understand the Problem: Clearly define what needs to be accomplished and identify any constraints or requirements.
2. Plan the Solution: Break down the problem into smaller, manageable parts and outline a step-by-step approach (pseudocode).
3. Implement the Code: Write the actual code based on the planned solution, ensuring clarity and readability.
4. Test and Debug: Run tests with various inputs, including edge cases, and debug any issues that arise.
5. Reflect and Learn: Analyze the solution, consider alternative approaches, and understand the trade-offs involved.
This model emphasizes critical thinking, active engagement, and continuous learning, which are essential for becoming a proficient coder.

# Part C: Testing Your Understanding
Without using AI, complete these variations:

# Ignore spaces and punctuation 

import sstring

def is_palindrome_ignore_spaces_punctuation(text):
    # Remove spaces and punctuation, convert to lowercase
    cleaned = "".join(char.lower() for char in text if char.isalnum())
    reversed_text = cleaned[::-1]
    return cleaned == reversed_text

# Make it case-insensitive

def is_palindrome_case_insensitive(text):
    # Convert to lowercase
    cleaned = text.lower()
    reversed_text = cleaned[::-1]
    return cleaned == reversed_text

# Return the position where the string stops being a palindrome (if not a palindrome)

def palindrome_failure_position(text):
    cleaned = "".join(text.lower().split())
    left, right = 0, len(cleaned) - 1
    
    while left < right:
        if cleaned[left] != cleaned[right]:
            return left  # Return the position of the first mismatch
        left += 1
        right -= 1
    
    return -1  # Return -1 if it is a palindrome

# Then use AI strategically:I modified my palindrome function to handle these cases: [show your modifications] Did I miss any edge cases? How could I make this more efficient?"

# AI Response:

Your modifications to handle spaces, punctuation, and case insensitivity are solid. Here are a few additional edge cases you might want to consider:
1. Empty strings: Ensure that an empty string is considered a palindrome.
2. Strings with only punctuation or spaces: These should also be treated as palindromes.
3. Unicode characters: If your input may include accented characters or symbols, consider normalizing them.
To make your function more efficient, you could implement the two-pointer technique to avoid creating a reversed string, which reduces space complexity. Here’s an example of how you could do that:

```python
def is_palindrome_optimized(text):
    cleaned = "".join(char.lower() for char in text if char.isalnum())
    left, right = 0, len(cleaned) - 1
    
    while left < right:
        if cleaned[left] != cleaned[right]:
            return False
        left += 1
        right -= 1
    
    return True
```

# Part D: The Fairness Contract

# Create ex00_ai_ethics_coder.md with a personal code of ethics for AI use in learning:

# I will use AI when:
To understand why my solution works/doesn't
To explore alternatives after I have a working solution
To debug issues after I have tried to solve them myself
Only use AI to clarify concepts, not to write the whole solution.
Ask AI to explain edge cases I might have missed.
Use AI to review my code for readability or efficiency

# I will NOT use AI when:

To write code before I have attempted it myself
To copy-paste solutions without understanding them
To avoid thinking through problems or debugging
To complete assignments or exams without my own effort
To produce work that I cannot explain or defend
To submit code that I have not tested or verified myself

# I know I'm using AI fairly when:
I can explain every part of the code I submit
I understand the logic and reasoning behind my solutions
I have attempted to solve problems on my own first
I can handle variations of the problems without AI help
I use AI to enhance my learning, not replace it

sing: Alexander Galiandras
date:24/11/2025

# Part E: Real-World Scenario Analysis

# Interview: "Explain how you'd implement a caching system." If you always relied on AI, can you answer? 

If I had always relied on AI to answer such questions, I would likely struggle to provide a coherent and detailed explanation of how to implement a caching system. I might know some general concepts but lack the depth of understanding needed to discuss specific strategies, data structures, and trade-offs involved in caching.

# Production bug at 2 AM: AI is unavailable. Can you debug code you don't fully understand?

Basically, it would be impossible to debug code that I do not understand and that has no explanation. I would need to spend many hours trying to figure out how the code works and what it actually does in order to identify the problem and attempt to fix it. So my conclusion is that yes, it is possible, but it would be very time-consuming because first I have to understand what the code does and how it operates, which is not very efficient if immediate intervention is required.

# New tech with little documentation: If you never learned to read docs and experiment, what happens?

If I never learned to read documentation and experiment on my own, I would struggle significantly when faced with new technology that lacks extensive documentation. I would likely feel lost and unable to effectively utilize the technology, as I wouldn't have the skills to explore its features, understand its capabilities, or troubleshoot issues independently. This reliance on external help would hinder my ability to adapt quickly and efficiently in a fast-paced tech environment.

# Write a paragraph: How does using AI fairly now prepare you for these scenarios?

Using AI fairly now prepares me for these scenarios by ensuring that I build a strong foundation of knowledge and problem-solving skills. By attempting to solve problems independently before seeking AI assistance, I develop a deeper understanding of coding concepts, algorithms, and system design. This approach equips me to explain complex topics during interviews, debug unfamiliar code under pressure, and adapt to new technologies with minimal documentation. Ultimately, using AI as a learning tool rather than a crutch fosters self-reliance and critical thinking, which are essential qualities for success in real-world coding challenges.

# Part F: Building Irreplaceable Skills

# Rate yourself 1–5 and write an improvement plan for your lowest area:

| Skill                    | Description                               | Rating | Improvement Plan                                                                 |
|--------------------------|-------------------------------------------|--------|---------------------------------------------------------------------------------|
| Problem Decomposition    | Breaking down problems logically          | 4/5    | I break each problem into smaller steps or subproblems.<br>Draw flowcharts before coding.<br>Review each subproblem separately. |
| Systems Thinking         | Understanding how components interact    | 3/5    | Study system architecture examples and diagrams.<br>Design small projects with multiple modules.<br>Analyze dependencies in code. |
| Critical Evaluation      | Knowing when code is wrong or inefficient| 3/5    | Write test cases for edge cases.<br>Compare multiple implementations.<br>Analyze time and space complexity. |
| Debugging Mindset        | Investigating unexpected behavior        | 3/5    | Reproduce bugs consistently.<br>Use debugging tools to trace execution.<br>Keep a log of common errors and solutions. |
| Conceptual Understanding | Knowing WHY, not just HOW                | 4/5    | Explain each step before coding.<br>Study underlying concepts and algorithms.<br>Reflect on mistakes to deepen understanding. |
