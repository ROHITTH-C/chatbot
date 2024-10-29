# chatbot
takes input of chat history and gives related mcqs and an article

Dependencies
Flask==2.1.2, 
pdfplumber==0.7.4, 
python-docx==0.8.11, 
google-generative-ai==0.2.0, 
Werkzeug==2.1.2, 
fpdf==1.7.2

steps to run 
first in terminal run
pip install Flask pdfplumber python-docx google-generative-ai Werkzeug fpdf
next run 
python web.py
and go to the given link in terminal

given test chat is:

Alice: Hey Bob, have you heard about the new features in Python 3.10?

Bob: Yes, I read about the structural pattern matching. It looks powerful!

Alice: Exactly! It allows you to match complex data structures easily.

Bob: What about type hinting? I heard they improved it too.

Alice: Right! They added more precise types, like Union and Literal.

Bob: That’s helpful for making code more readable. Have you tried using it?

Alice: I have! It definitely helps with debugging and understanding function signatures.

Bob: I think I should start using it in my projects. Any other features you like?

Alice: I also love the new syntax for parenthesized context managers. It simplifies code a lot.

Bob: Sounds great! Do you think I should upgrade my current projects to 3.10?

Alice: If you’re using a lot of type hinting, it’s worth it. Just check for library compatibility first.

Bob: Good point! I'll make sure to do that. Thanks for the info!

Alice: No problem! Let me know if you have any questions while upgrading.

output given is:

Question: Which Python 3.10 feature does Bob find powerful for its ability to match complex data structures?

Options:

A) Type hinting

B) Parenthesized context managers

C) Structural pattern matching

D) Union and Literal types

Correct Answer: C) Structural pattern matching

Explanation: Bob explicitly mentions that he read about structural pattern matching and finds it powerful for handling complex data structures.

Question: What advice does Alice give to Bob regarding upgrading his projects to Python 3.10?

Options:

A) Upgrade all projects immediately.

B) Only upgrade if using structural pattern matching.

C) Check for library compatibility before upgrading.

D) Wait for the next Python version release.

Correct Answer: C) Check for library compatibility before upgrading.

Explanation: Alice cautions Bob to ensure his current libraries are compatible with Python 3.10 before upgrading.

and given article is:

Python 3.10: To Upgrade or Not to Upgrade?

Introduction 
The release of a new Python version always brings excitement and a wave of questions for developers. Python 3.10 is no exception, boasting powerful features that promise to enhance coding efficiency and readability. But with any upgrade, it's essential to weigh the benefits against potential compatibility issues. Let's delve into a conversation between two developers, Alice and Bob, as they discuss the compelling features of Python 3.10 and the decision to upgrade existing projects.

Exploring the Highlights of Python 3.10 #

Power of Structural Pattern Matching Alice and Bob kick off the conversation discussing structural pattern matching, a flagship feature in Python 3.10. This powerful addition allows for elegant and concise code when dealing with complex data structures, eliminating the need for verbose if-else chains. #

Enhanced
Type Hinting: Clarity and Readability Type hinting has been significantly improved in 3.10, with the introduction of more precise types like `Union` and `Literal`. Alice highlights how this enhances code readability and aids in debugging. Bob acknowledges the benefit of increased clarity in function signatures, making the code easier to understand and maintain. #

Simplified
Syntax: Parenthesized Context Managers Alice raves about the new syntax for parenthesized context managers, a seemingly small change that significantly simplifies code structure, particularly when nesting multiple context managers.

Upgrade Dilemma: Weighing the Pros and Cons While excited about the new features, Bob raises a crucial question: should he upgrade his existing projects to 3.10? Alice wisely advises considering the extent of type hinting used in the projects, as this is where the most immediate benefits would be seen. However, she emphasizes the critical need to check for library compatibility before making the jump, highlighting a potential challenge in any upgrade process.

Conclusion 
The conversation between Alice and Bob provides a realistic glimpse into the decision-making process for developers considering an upgrade to Python 3.10. The new features, especially structural pattern matching and enhanced type hinting, offer significant advantages in terms of code clarity, efficiency, and readability. However, compatibility checks are crucial to ensure a smooth transition. By carefully weighing the benefits against potential challenges, developers can make an informed decision about upgrading to harness the exciting capabilities of Python 3.10.
