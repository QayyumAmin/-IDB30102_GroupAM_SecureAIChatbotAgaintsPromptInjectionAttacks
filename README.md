# IDB30102 Group AM Repository 
Secure AI Chatbot Against Prompt Injection Attacks

1.	Group Information

Group Number: AM

Group Members
No	Name	Student ID

1	MUHAMMAD QAYYUM BIN MOHD AMIN	52215226028

2	DANIEL HARRIS BIN MOHD FAZLI	52215226344

3	MUHAMMAD FAKHRUL ARIF BIN MOHD AZMI	52215124460

4	MUHAMMAD SYAZWAN BIN SHAHRIL	52215226129

2.	Assigned Research Area

The assigned research area for this project is AI Security, with a specific focus on securing AI chatbots against prompt injection attacks. AI security involves protecting artificial intelligence systems, training data, models, applications and deployment environments from manipulation, unauthorised access and malicious attacks.

This project focuses on prompt injection because it is an important security threat affecting AI chatbots and applications powered by Large Language Models. A prompt injection attack occurs when a malicious user submits instructions designed to manipulate the chatbot, override its intended rules or cause it to generate unauthorised and harmful responses.

3.	Research Problem

The use of AI chatbots has been widespread in the education sector, business, healthcare and organisational operations. The chatbots may encounter malicious prompts meant to subvert the intended functionality of the chatbots. Prompt injection attacks can make the chatbot generate forbidden content, leak sensitive information and perform unintended functions. These poses risks on the security, privacy and reliability of the organisations using the AI chatbots.

Existing prompt injection defences do not provide complete protection against every attack. The findings from Assignment 1 indicate that attack effectiveness can vary across AI models, prompt structures and deployment environments. Some security mechanisms may also produce false-positive detections, increase processing time or reduce the normal usefulness of the chatbot. Therefore, a practical security mechanism is required to detect and block malicious prompts while allowing legitimate prompts to be processed with minimal interruption.
 
4.	Research Aim

The aim of this research is to develop a secure AI chatbot that can detect and prevent prompt injection attacks while maintaining reliable and efficient responses for legitimate users.

5.	Research Objectives

I.	To analyse prompt injection attacks, their characteristics and existing security approaches used to protect AI chatbots.
II.	Design and develop a secure AI chatbot with a security mechanism for identifying and blocking potential prompt injection attacks.
III.	To evaluate the effectiveness and operational performance of the proposed secure AI chatbot in distinguishing malicious prompts from legitimate prompts.

6.	Brief Description of the Proposed Solution

This project proposes a secure AI chatbot that can identify and block prompt injection attacks. Before a user’s prompt is sent to the AI model, it will first be checked by a security layer to determine whether it is safe or potentially malicious.

If the prompt is considered safe, the chatbot will process it normally and provide a response. If suspicious instructions are detected, the prompt will be blocked and recorded in a security log. The user will then receive a warning explaining that the request cannot be processed due to security concerns.

This solution aims to prevent users from manipulating the chatbot’s original instructions or forcing it to generate unauthorised responses. At the same time, the system should continue responding normally to genuine users without creating unnecessary delays or blocking legitimate questions.

7.	Selected research methodology

**Design Science Research Methodology (DSRM)**

DSRM is selected because the research focuses on designing, developing, demonstrating and evaluating a practical artefact, which is the Secure AI Chatbot with a prompt-injection detection mechanism.

8.	Development model (write "Not applicable" if none)

**Iterative and Incremental Development Model**

The system will be developed incrementally. The first increment will develop the basic chatbot interface, followed by prompt preprocessing and detection, and then prompt blocking, warning messages and security logging. The components will subsequently be integrated and tested as a complete prototype.

9.	Proposed evaluation plan (baseline, dataset or test environment, and metrics)

Baseline:
A baseline chatbot without the proposed prompt-injection security layer will be compared with the secured chatbot.

Dataset/Test Environment:
A controlled test environment using 60 labelled synthetic prompts:

30 legitimate/benign prompts
30 prompt-injection attempts

The same test set will be used for both the baseline and secured chatbot.

Evaluation Metrics:

-Prompt Injection Detection Rate
-Attack Success Rate (ASR)
-False Positive Rate (FPR)
-Benign Prompt Acceptance Rate
-Response Time / Latency Overhead
-Security Log Completion

A confusion matrix will also be used to analyse classification performance.


10.	Proposed system architecture

User → Chatbot Interface → Prompt Preprocessing → Prompt Injection Detector → Security Decision

Safe prompt: → AI Chatbot → Response → User
Malicious prompt: → Block → Warning Message + Security Log

The proposed architecture consists of a user interface, prompt preprocessing component, prompt-injection detector, security decision component, AI chatbot and security logging component.

11.	Technical components

1. Chatbot User Interface
2. Prompt Preprocessing Module
3. Prompt Injection Detection Module
4. Security Decision Mechanism
5. AI Chatbot / LLM
6. Prompt Blocking Mechanism
7. Warning Message System
8. Security Logging Module
9. Baseline Chatbot for comparison
10. Evaluation and performance measurement module

These components are aligned with the implementation scope and proposed system architecture.

12.	Programming languages, frameworks, datasets and tools

Programming Languages: To be determined during system implementation.
Frameworks: To be determined during system implementation.
Dataset: A synthetic dataset consisting of 60 labelled prompts, including 30 benign prompts and 30 prompt-injection prompts.
Tools: Chatbot/LLM platform, development environment, security logging tools and evaluation tools to be selected during implementation.

13.	Preliminary code execution instructions, where applicable

Not applicable at the proposal stage. Preliminary execution instructions will be provided after the prototype implementation is completed. The system will subsequently be tested using the prepared benign and prompt-injection test prompts in a controlled environment.
