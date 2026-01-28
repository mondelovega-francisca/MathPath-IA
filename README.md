# MathPath-IA
![image of MathIA app](/MathIA.png)
An artificial intelligence–based adaptive mathematics learning system that models student knowledge through response analysis, error patterns, and temporal dynamics. It generates personalized learning paths for remediation, consolidation, enrichment, and intensive exam preparation, supporting data-informed pedagogical decisions.
<!-- This is the markdown template for the final project of the Building AI course, 
created by Reaktor Innovations and University of Helsinki. 
Copy the template, paste it to your GitHub README and edit! -->

# Project Title
MathPath-IA
Final project for the Building AI course

## Summary
An artificial intelligence–based adaptive mathematics learning system that models student knowledge through response analysis, error patterns, and temporal dynamics. It generates personalized learning paths for remediation, consolidation, enrichment, and intensive exam preparation, supporting data-informed pedagogical decisions.

## Background

*Lack of personalized diagnosis in mathematics learning. Many students fail or struggle in mathematics because specific conceptual or procedural difficulties are not identified early. This problem is very common in secondary education, where assessment focuses on final results rather than learning processes.

*Inefficient and generic remediation strategies. Traditional reinforcement activities are usually uniform for all students, regardless of their actual needs. This leads to wasted study time and limited improvement, especially in large or heterogeneous classrooms.

*Poor use of assessment data. Student responses, error patterns, and timing data are rarely analyzed in depth, despite containing valuable information about learning gaps. This represents a missed opportunity to support data-informed teaching.

*High anxiety and low efficiency in exam preparation. Many students need to prepare mathematics exams in short time frames without clear guidance on what content is essential. This situation is frequent in recovery exams and contributes to stress and poor outcomes.

*Personal motivation. As an educator, I observe daily that students with similar grades often have very different underlying difficulties. I am motivated to design a system that helps diagnose these differences and supports both students and teachers with actionable insights.

*Importance of the topic. Mathematics is a foundational subject with strong cumulative dependencies. Improving how mathematical understanding is diagnosed and supported can significantly impact academic success, equity in education, and long-term access to STEM pathways.


## How is it used?

The solution is used as an adaptive learning tool in mathematics, both in the classroom and for independent study at home. Students interact by solving digital exercises, while the system analyzes their answers, times, and error patterns to estimate their level of mastery of each concept.

Based on this analysis, the AI ​​generates personalized learning paths, adjusting the pace, difficulty, and type of activities (reinforcement, consolidation, or extension). The tool is especially useful in contexts of continuous assessment, content review, and intensive exam preparation in short periods of time.

The main users are secondary and high school students and teachers. Considerations must include the diversity of learning paces, the clarity of feedback for students, the interpretability of data for teachers, and respect for the privacy of educational information.

![image of MathIA app](/Mates.png)


## Data sources and AI methods
Methods from the "Building AI" course that fit your project (and why)
*Supervised learning (classification)
The main problem is diagnosing the type of difficulty (e.g., sign error, rule confusion, conceptual error) based on the evidence or data provided by the learner: response, steps, time, error patterns.
*Linear regression (supervised regression)
Useful for predicting continuous variables such as "risk of failure," "expected grade," "estimated mastery time," or "probability of passing the exam in X hours."
*k-NN
As a benchmark: compare the learner to "similar learners" based on error patterns and make a decision.
*Logistic regression / Small neural networks (MLP)
When the features are not linear (combination of time + sequence of steps + type of error).
*Overfitting control (validation, regularization, and dropout, for example)
The application will have noisy data (students "trolling," incomplete answers, stress).
*Reinforcement Learning (RL)
This could be used later to optimize the sequence of activities as an "agent" that maximizes reward (passing/retention), but it is not necessary for the first version.


## Challenges

This project is not intended to replace teachers, formal assessment, or comprehensive learning analysis systems. It focuses on diagnosing specific conceptual and procedural difficulties within a mathematical domain, and its conclusions are limited by the scope and quality of the available data.

The AI ​​model does not infer students' motivation, emotional state, or learning potential. It only analyzes observable interaction data (responses, timing, and simple behavioral cues), which may not fully reflect student understanding. Therefore, misdiagnoses are possible, especially with limited data or atypical student behavior.

The system relies on synthetic or small-scale datasets in its initial stages. Consequently, the model's performance may not be generalizable to diverse student populations without further data collection and validation. The project does not address long-term learning outcomes or the causal effects of interventions.

From an ethical perspective, the system must ensure student privacy and data protection, particularly when collecting interaction-level data. All student data must be anonymized, stored securely, and used exclusively for educational purposes. The system should avoid high-risk decisions and be used as a support tool rather than an authoritative evaluator, with teachers retaining full pedagogical control.

## What next?

This project can evolve by expanding both its pedagogical scope and its AI components. In the short term, the system could incorporate topics and skills from other subjects, allowing the diagnostic model to operate within a broader curriculum, rather than solely focusing on mathematical concepts. This would facilitate more meaningful learning pathways and longitudinal analysis of student progress across various competencies.

From a technical perspective, future versions could integrate knowledge tracking models to estimate skill mastery over time, as well as improved feature extraction from student responses. Collecting real-world classroom data would significantly enhance the model's validity and robustness.

Moving forward, the project would require collaboration with educators to refine pedagogical guidelines and validate recommendations, along with support from data protection and ethics specialists to ensure responsible implementation. Additional skills in educational data mining, user interface design, and scalable systems deployment would also be needed to transition from a prototype to a production-ready educational tool.


## Acknowledgments

* My students and of course my cat

