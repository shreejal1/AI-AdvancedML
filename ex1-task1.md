1. What is the difference between AI, ML, and deep learning?
Ans:
Artificial Intelligence (AI): The broad discipline of creating intelligent machines that can simulate human capability and behavior.

Machine Learning (ML): A specific subset of AI. It involves the use of algorithms that allow computers to learn from data and improve their performance without being explicitly programmed for every specific rule.

Deep Learning (DL): A specialized subset of Machine Learning inspired by the structure of the human brain. It uses multi-layered artificial neural networks to solve complex problems like image and speech recognition.

AI - covers the whole idea of smart machines.
ML - is a specific technique of learning from examples.
DL - inside ML, its a powerful type of learning that mimics how the brain's neurons connect

2. What is machine learning?
Ans:
Machine learning is the study of computer algorithms that improve automatically through experience and the use of data. Instead of writing code that says "if X happens, do Y," you feed data into an algorithm, and the algorithm builds its own logic to determine the output.
Traditional Programming: You have to manually write rules: "Look for pointy ears, whiskers, and a tail."

You show a computer 1000 pictures of cats and say, "These are cats." The computer will eventually figure out on its own what makes a cat - a cat, often noticing patterns that you might have missed.


3. What is the primary difference between unsupervised and supervised machine learning?
Ans:
Supervised Learning: The model is trained on "labeled" data. This means the input data comes with the correct answer (the label). The model tries to map the input to the correct output. It’s like a student learning with a teacher who has an answer key. The student takes a practice test, and the teacher corrects them: "No, that's wrong, here is the right answer."

Unsupervised Learning: The model is trained on "unlabeled" data. The system tries to learn the patterns and the structure from the data without any explicit guidance on what the outcome should be. It’s like a baby playing with blocks. There is no teacher to say "this is a square." The baby just figures out on their own that "these blocks all have sharp corners" and "those blocks are round," grouping them by similarity.

Supervised: Like a student learning with teacher who has the answer, the student takes a test, and teacher corrects him/her.
Unsupervised: Like a baby playing with blocks. Observing and choosing the group with similar patterns, (round corners, sharp corners, etc.)

4. What is reinforcement learning?
Ans:
Reinforcement Learning (RL) is a type of ML where an agent learns to make decisions by performing actions in an environment and receiving feedback in the form of rewards or penalties. The goal is to maximize the cumulative reward over time.

You don’t tell the dog how to move its muscles to sit. You say "Sit!"
If the dog sits, you give it a treat (Reward). If the dog jumps on you, you say "No!" (Penalty). Eventually, the dog learns that "Sitting = Good things happen," so it does it more often.

5. What types of problems can machine learning solve well when compared to traditional programming?
Ans:
ML excels at problems involving:
High Complexity: Where the rules are too nuanced to write down (ex: facial recognition).
Scale: Handling massive datasets that humans cannot analyze manually.
Dynamic Environments: Situations where data changes over time (ex: personalized Netflix recommendations or stock market prediction).

Traditional programming is good for calculator, or, the things which are strictly correct. example, 2+2=4. Ml is greate for recognizing handwritings. Well, everbody writes A with different styles, which the traditional programming fails to be compatible here. Whereas, ML learns from the examples, and figures it out.

6. What types of problems can you solve with unsupervised machine learning?
Ans:
Unsupervised learning is typically used for:
Clustering: Grouping similar data points together (ex: customer segmentation).
Anomaly Detection: Finding outliers in data (ex: credit card fraud detection).
Association: Discovering rules that describe large portions of your data (ex: "People who buy X also buy Y").

If theres a big bucket for messy lego bricks. Unsupervised learning is used to sort the bucket, you don't know the names of the pieces, but you can separate them into piles: "These are all red," "These are all tiny," or "These look weird and don't fit anywhere"

7. What types of problems can you solve with supervised machine learning?
Ans:
Supervised learning is generally divided into two types of problems:
Classification: Predicting a category (ex: "Is this email Spam or Not Spam?").
Regression: Predicting a continuous number (ex: "What will the price of this house be next year?").

Classification is like a doctor diagnosing a patient ("Sick" or "Healthy") based on past patients' symptoms. Regression is like predicting how long your commute will be based on the traffic history at this time of day.

8. Explain the difference between a ML algorithm and a ML model?
Ans:
Algorithm: The mathematical method or procedure used to learn from the data (ex: Linear Regression, Decision Tree). It is the logic before training.
Model: The specific artifact created after you run the algorithm on your specific data. It is the "trained" program that can now make predictions.

The Algorithm is the Recipe. It’s just instructions on a page. The Model is the Cake you actually baked using your specific ingredients. we can use the same recipe (Algorithm) to make many different cakes (Models) depending on the ingredients (Data) you use.

9. List some of the challenges of machine learning and provide concrete examples?
Ans:
Data Quality/Quantity: ML models require massive amounts of clean data. "Garbage in, garbage out."
Bias: If the training data is biased, the model will be biased.
Overfitting: The model memorizes the training data but fails to generalize to new, unseen data.
Explainability (Black Box): In complex models like Deep Learning, it is often difficult to understand why the model made a specific decision.

Bias (The "Bad Textbook" Problem): If you teach a child about the world using only books from 1950, they might learn outdated or unfair views. Similarly, if you train a hiring AI on resumes from a company that historically only hired men, the AI might learn to reject women.

Overfitting (The "Memorization" Problem): a student who memorizes the answers to the practice test but doesn't learn the concepts. They get 100% on the practice test, but when they take the real exam (new data), they fail completely.