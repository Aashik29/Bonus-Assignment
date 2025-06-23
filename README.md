# Bonus-Assignment

Name:Aashik Shaik

700#: 700758163

CRN: 30672


Here’s a concise README overview of your Bonus Assignment:

Bonus Assignment Overview
Student: Aashik Shaik
Points: 1
Submission Requirements:


Push source code to GitHub.


Include a clearly written README with explanation and student info.


Submit GitHub link and a 2–3 minute demo/explanation video on BrightSpace.


Late submissions not accepted.



Assignment Tasks



1. Question Answering with Transformers (Hugging Face)
You’ll build a basic QA system using Hugging Face’s transformers and torch.
Tasks:


Set up a basic QA pipeline and test it.


Swap in a custom model like deepset/roberta-base-squad2.


Write your own context and ask two questions with expected scores > 0.70.




2. Conditional GAN for Digit Generation
You’ll implement a Conditional GAN to generate MNIST digits based on class labels (0–9).
Tasks:


Modify a vanilla GAN to take label input.


Concatenate labels with noise (generator) and images (discriminator).


Train and visualize outputs by label.


Expect clearer digit control over time, even if loss fluctuates.



Conceptual Questions
Q: How does a Conditional GAN differ from a vanilla GAN?



Aspect
Vanilla GAN
Conditional GAN (cGAN)




Input
Noise only
Noise + condition (e.g., class label)


Output Control
Random outputs
Targeted outputs (e.g., digit "7")


Discriminator Input
Image only
Image + label



Real-world example: Generating specific clothing styles by gender/season.

Q: What does the discriminator learn in image-to-image GANs?
It learns to judge whether the output matches the input — not just realism, but relevance.
Why pairing matters: Without paired input-output samples, the generator may produce random but irrelevant images — totally useless for structured tasks like sketch-to-photo translation.

Let me know if you'd like this overview exported as a markdown, PDF, or Word document!
