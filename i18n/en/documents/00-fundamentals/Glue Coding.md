# 🧬 Glue Coding

> **The holy grail and silver bullet of software engineering – it's finally here.**

---

## 🚀 Disruptive Manifesto

**Glue Coding is not a technology, but a revolution.**

It might perfectly solve the three fatal flaws of Vibe Coding:

| Pain Points of Traditional Vibe Coding | Glue Coding's Solution |
|:---|:---|
| 🎭 **AI Hallucinations** - Generating non-existent APIs, incorrect logic | ✅ **Zero Hallucinations** - Only using validated, mature code |
| 🧩 **Complexity Explosion** - The larger the project, the more out of control it becomes | ✅ **Zero Complexity** - Every module is a time-tested wheel |
| 🎓 **High Barrier to Entry** - Requires deep programming skills to master AI | ✅ **Barrier Disappears** - You only need to describe "how to connect" |

---

## 💡 Core Concept

```
Traditional Programming: Humans write code
Vibe Coding: AI writes code, humans review code
Glue Coding: AI connects code, humans review connections
```

### Paradigm Shift

**A fundamental shift from "generation" to "connection":**

- ❌ No longer letting AI generate code from scratch (the source of hallucinations)
- ❌ No longer reinventing the wheel (the source of complexity)
- ❌ No longer requiring you to understand every line of code (the source of high barriers)

- ✅ Only reusing mature, production-validated open-source projects
- ✅ AI's sole responsibility: understanding your intent and connecting modules
- ✅ Your sole responsibility: clearly describing "what is the input, what is the desired output"

---

## 🏗️ Architectural Philosophy

```
┌─────────────────────────────────────────────────────────┐
│                   Your Business Needs                   │
└─────────────────────────────────────────────────────────┘
                           │
                           ▼
┌─────────────────────────────────────────────────────────┐
│                   AI Glue Layer                        │
│                                                         │
│   "I understand what you want to do, let me connect these blocks" │
│                                                         │
└─────────────────────────────────────────────────────────┘
                           │
          ┌────────────────┼────────────────┐
          ▼                ▼                ▼
   ┌─────────────┐  ┌─────────────┐  ┌─────────────┐
   │ Mature Module A │  │ Mature Module B │  │ Mature Module C │
   │  (100K+ ⭐)  │  │  (Production Validated)  │  │  (Official SDK)  │
   └─────────────┘  └─────────────┘  └─────────────┘
```

**Entity**: Mature open-source projects, official SDKs, time-tested libraries
**Link**: AI-generated glue code, responsible for data flow and interface adaptation
**Function**: Your described business objective

---

## 🎯 Why is this the Silver Bullet?

### 1. Hallucination Problem → Completely Disappears

AI no longer needs to "invent" anything. It only needs to:
- Read Module A's documentation
- Read Module B's documentation
- Write the data transformation from A to B

**This is what AI excels at, and what is least prone to errors.**

### 2. Complexity Problem → Transferred to the Community

Behind each module are:
- Thousands of Issue discussions
- Hundreds of contributors' wisdom
- Years of production environment refinement

**You are not managing complexity, you are standing on the shoulders of giants.**

### 3. Barrier to Entry Problem → Reduced to a Minimum

You don't need to understand:
- Underlying implementation principles
- Best practice details
- Edge case handling

You just need to speak human language:
> "I want to process Telegram messages with GPT and save them to PostgreSQL"

**AI will help you find the most suitable wheels and then glue them together.**

---

## 📋 Practical Workflow

```
1. Clarify Goal
   └─→ "I want to implement XXX function"

2. Find Wheels
   └─→ "Are there any mature libraries/projects that have done something similar?"
   └─→ Let AI help you search, evaluate, and recommend

3. Understand Interfaces
   └─→ Feed the official documentation to AI
   └─→ AI summarizes: what is the input, what is the output

4. Describe Connection
   └─→ "The output of A should become the input of B"
   └─→ AI generates glue code

5. Verify Run
   └─→ Runs successfully → Done
   └─→ Error → Give the error to AI, continue gluing
```

---

## 🔥 Classic Case Study

### Case: Polymarket Data Analysis Bot

**Requirement**: Real-time acquisition of Polymarket data, analysis, and pushing to Telegram

**Traditional Approach**: Write a crawler from scratch, write analysis logic, write a Bot → 3000 lines of code, 2 weeks

**Glue Approach**:
```
Wheel 1: polymarket-py (Official SDK)
Wheel 2: pandas (Data Analysis)
Wheel 3: python-telegram-bot (Message Push)

Glue Code: 50 lines
Development Time: 2 hours
```

---

## 📚 Further Reading

- [语言层要素](./语言层要素.md) - 8 Levels of Understanding 100% Code
- [胶水开发提示词](../../prompts/coding_prompts/胶水开发.md)
- [项目实战：polymarket-dev](../项目实战经验/polymarket-dev/)

---

## 🎖️ Summary

> **If you can copy, don't write; if you can connect, don't build; if you can reuse, don't originate.**

Glue Coding is the ultimate evolution of Vibe Coding.

It's not laziness, but **the highest manifestation of engineering wisdom** –

Using the least amount of original code to leverage the greatest productivity.

**This is the silver bullet software engineering has been waiting for for 50 years.**

---

*"The best code is no code at all. The second best is glue code."*

# Glue Coding Methodology

## **1. Definition of Glue Coding**

**Glue coding** is a new software construction method, whose core idea is:

> **Almost entirely reusing mature open-source components, combining them into a complete system with a minimal amount of "glue code".**

It emphasizes "connection" rather than "creation", especially efficient in the AI era.

## **2. Background**

Traditional software engineering often requires developers to:

* Design architecture
* Write logic themselves
* Manually handle various details
* Reinvent the wheel

This leads to high development costs, long cycles, and low success rates.

However, the current ecosystem has fundamentally changed:

* Thousands of mature open-source libraries on GitHub
* Frameworks covering various scenarios (Web, AI, Distributed, Model Inference...)
* GPT / Grok can help search, analyze, and combine these projects

In this environment, writing code from scratch is no longer the most efficient way.

Thus, "glue coding" has emerged as a new paradigm.

## **3. Core Principles of Glue Coding**

### **3.1 Don't write what can be avoided, write as little as possible**

Any functionality with a mature existing implementation should not be reinvented.

### **3.2 Copy-paste whenever possible**

Directly copying and using community-validated code is a normal engineering process, not laziness.

### **3.3 Stand on the shoulders of giants, don't try to be a giant**

Utilize existing frameworks instead of trying to write a "better wheel" yourself.

### **3.4 Do not modify original repository code**

All open-source libraries should ideally remain immutable, used as black boxes.

### **3.5 The less custom code, the better**

Your written code only serves to:

* Combine
* Call
* Encapsulate
* Adapt

Which is the so-called **glue layer**.

## **4. Standard Workflow of Glue Coding**

### **4.1 Clarify Requirements**

Break down the system's functionality into individual requirements.

### **4.2 Use GPT/Grok to Deconstruct Requirements**

Let AI refine requirements into reusable modules, capabilities, and corresponding subtasks.

### **4.3 Search for Existing Open-Source Implementations**

Leverage GPT's internet capabilities (e.g., Grok):

* Search for corresponding GitHub repositories for each sub-requirement.
* Check for reusable components.
* Compare quality, implementation methods, licenses, etc.

### **4.4 Download and Organize Repositories**

Pull the selected repositories locally and organize them by category.

### **4.5 Organize According to Architectural System**

Place these repositories into the project structure, for example:

```
/services
/libs
/third_party
/glue
```

And emphasize: **Open-source repositories are third-party dependencies and must never be modified.**

### **4.6 Write Glue Layer Code**

The role of glue code includes:

* Encapsulating interfaces
* Unifying input/output
* Connecting different components
* Implementing minimal business logic

The final system is composed of multiple mature modules.

## **5. Value of Glue Coding**

### **5.1 Extremely High Success Rate**

Because it uses community-validated mature code.

### **5.2 Extremely Fast Development Speed**

A large amount of functionality can be directly reused.

### **5.3 Reduced Costs**

Time cost, maintenance cost, and learning cost are all significantly reduced.

### **5.4 More Stable System**

Relies on mature frameworks rather than individual implementations.

### **5.5 Easy to Extend**

Capabilities can be easily upgraded by replacing components.

### **5.6 Strong Synergy with AI**

GPT can assist in searching, deconstructing, and integrating, making it a natural enhancer for glue engineering.

## **6. Glue Coding vs. Traditional Development**

| Project     | Traditional Development  | Glue Coding   |
| ----------- | ------------------------ | ------------- |
| Feature Implementation | Write yourself           | Reuse open-source |
| Workload    | Large                    | Much smaller  |
| Success Rate | Uncertain                | High          |
| Speed       | Slow                     | Extremely fast |
| Error Rate  | Prone to pitfalls        | Uses mature solutions |
| Focus       | "Building wheels"        | "Combining wheels" |

## **7. Typical Application Scenarios for Glue Coding**

* Rapid prototype development
* Small teams building large systems
* AI application/model inference platforms
* Data processing pipelines
* Internal tool development
* System Integration

## **8. Future: Glue Engineering will become the new mainstream programming method**

As AI capabilities continue to strengthen, future developers will no longer need to write a lot of code themselves, but rather:

* Find wheels
* Combine wheels
* Intelligently connect components
* Build complex systems at extremely low cost

Glue coding will become the new standard for software productivity.
