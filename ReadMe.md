# Software Development Lifecycle

## 1. Software Requirements and Design
### 1.1 Software Requirements
- What a system needs to do and how it should work. 
- These requirements are categorized into functional and non-functional requirements.
- Input: unstructured data sources; Output: formal descriptions and requirements
for software systems

### 1.2 Software Specifications Repair
- Software Specifications Repair refers to the process of fixing
errors in software specifications, which are formal declarations of software system requirements or behaviors.
- The process involves identifying and rectifying various types of
errors in software specifications, including logical inconsistencies, type errors, and misuse of programming constructs
- https://arxiv.org/pdf/2310.12425.pdf

### 1.3 Requirement classification
- Requirement classification refers to the process of categorizing software requirements into different classes or types. Software requirements typically encompass both functional and non-functional requirements. Functional requirements outline the functionalities and behaviors the
software should achieve, while non-functional requirements
cover broader system attributes such as performance, security, reliability, and maintainability. Through requirement
classification, software developers can better organize and
comprehend various types of requirements.
- https://ieeexplore.ieee.org/document/9218141
- https://ieeexplore.ieee.org/document/10181313
- https://ieeexplore.ieee.org/document/10256174
- https://ieeexplore.ieee.org/document/10260874

### 1.4 Software Design
- Involves the process of defining the structure, components, functionalities, interfaces and their relationships within a software system.
Software engineers need to create detailed plans and design blueprints on software requirements and specifications to ensure that the software system can meet the users needs and expectation

### 1.5 GUI layout
- https://dl.acm.org/doi/10.1145/3593230

### 1.3 Examples/Papers
-  Impact of Large Language Models on Generating
Software Specifications: https://arxiv.org/pdf/2306.03324.pdf
 - Advancing Requirements Engineering through
Generative AI: https://arxiv.org/pdf/2310.13976.pdf

## 2. Software Development
### 2.1 Code generation
- Generating code according to requirement specification.
- Requirement-guided code generation:
- - natural language description as the input and the correct code snippet as output, which is evaluated by corresponding unit tests.

### 2.2 Examples/Papers
- AceCoder: https://arxiv.org/pdf/2303.17780.pdf
- ClarifyGPT: https://arxiv.org/pdf/2310.10996.pdf
- https://arxiv.org/pdf/2108.12144.pdf
- Frameworks to generate code:
  - TDD: Execution feedback code generation
  - Self Collaboration: three GPT roles: analyst, coder and tester
- CodeT5
- Codex

### 2.3 Code Translation
the process of converting code from one programming language into
another while preserving its functionality. It is often used
for porting applications, cross-platform development, and
legacy system maintenance.

#### 2.4 Examples/Papers
- codeeditor
- 

### 2.5 Code Search

### 2.6 Code Refinement
Code refinement is the process of altering a specific piece of code, which might contain errors
or be overly complex, with the goal of transforming a flawed
function into one that functions correctly

- CodeT5
- GraphCodeBERT
- SPT-Code

#### 2.7 Examples/Papers
- codeeditor
- 

### 2.8 Code Completion

### 2.9 Program Synthesis
Program synthesis refers to the automated process of generating computer programs based on high-level specifications
or requirements. The objective of this process is to automate typically complex and time-consuming manual software
development tasks by allowing machines to generate code based on specifications provided by users.

- https://arxiv.org/pdf/2112.02969.pdf
- Synthesize, Execute, Debug (SED) approach: https://arxiv.org/pdf/2304.10423.pdf

## 3. Software Testing
### 3.1 Fault localization
Fault localization is a critical process in software engineering that involves identifying the specific locations or elements
in a software system where faults or bugs are present.

### 3.2 Code Decompilation
### 3.2 vulnerability Detection
### 3.3 Unit Test Generation
Test generation is the process of creating a set of test data or test cases for testing the adequacy of new or revised software programs.

### Fuzzing 3.4 Fuzzing
Fuzzing is an automated software testing method that injects invalid, malformed, or unexpected inputs into a system
to reveal software defects and vulnerabilities

### GUI Testing
 GUI Testing

