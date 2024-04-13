# Software Engineering Lifecycle

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

### 1.2 Requirement classification
- Requirement classification refers to the process of categorizing software requirements into different classes or types. Software requirements typically encompass both functional and non-functional requirements. Functional requirements outline the functionalities and behaviors the
software should achieve, while non-functional requirements
cover broader system attributes such as performance, security, reliability, and maintainability. Through requirement
classification, software developers can better organize and
comprehend various types of requirements.
- https://ieeexplore.ieee.org/document/9218141
- https://ieeexplore.ieee.org/document/10181313
- https://ieeexplore.ieee.org/document/10256174
- https://ieeexplore.ieee.org/document/10260874

### 1.2 Software Design
- Involves the process of defining the structure, components, functionalities, interfaces and their relationships within a software system.
Software engineers need to create detailed plans and design blueprints on software requirements and specifications to ensure that the software system can meet the users needs and expectation

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

### 2.3 Code Refinement
Code refinement is the process of altering a specific piece of code, which might contain errors
or be overly complex, with the goal of transforming a flawed
function into one that functions correctly

- CodeT5
- GraphCodeBERT
- SPT-Code

#### 2.4 Examples/Papers
- codeeditor
- 