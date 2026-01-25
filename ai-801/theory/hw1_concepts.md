# Lesson 1: Foundations of AI - Core Concepts

## Chapter 1: Introduction to AI

### 1.1 Definition of Artificial Intelligence
AI is the study of **agents** that receive percepts from the environment and perform actions. The field is categorized into four historical approaches:
* **Thinking Humanly:** The cognitive modeling approach.
* **Acting Humanly:** The Turing Test approach.
* **Thinking Rationally:** The "Laws of Thought" approach.
* **Acting Rationally:** The **Rational Agent** approach (The focus of this course).

### 1.2 The Standard Model
The "Standard Model" of AI focuses on **Rational Action**. A rational agent is one that acts so as to achieve the best outcome or, when there is uncertainty, the best expected outcome.

### 1.3 The Turing Test
Proposed by Alan Turing (1950), it defines intelligence as the ability to achieve human-level performance in all cognitive tasks, sufficient to fool an interrogator. 
**Required Capabilities:**
1. Natural Language Processing (NLP)
2. Knowledge Representation
3. Automated Reasoning
4. Machine Learning

### 1.4 Foundations of AI
* **Philosophy:** Ideas on how the mind works and the formalization of thought.
* **Mathematics:** Logic, Computation (algorithms), and Probability (uncertainty).
* **Economics:** Decision theory and maximizing utility.
* **Neuroscience & Psychology:** Biological models of information processing.
* **Linguistics:** The intersection of language and thought (NLP).

---

## Chapter 2: Intelligent Agents

### 2.1 Agents and Environments
* **Agent:** Anything that can be viewed as perceiving its environment through **sensors** and acting upon that environment through **actuators**.
* **Percept:** The agent's perceptual inputs at any given instant.
* **Agent Function:** Maps any given percept sequence to an action.



### 2.2 The PAGE (PEAS) Construct
To design an agent, we must specify the **Task Environment**:
* **P - Performance Measure:** The success criteria (e.g., safety, profit, speed).
* **A - Actuators:** Tools for acting (e.g., wheels, robotic arms, display screens).
* **G - Sensors:** Tools for perceiving (e.g., cameras, GPS, keyboard).
* **E - Environment:** The world the agent operates in (e.g., a city street, a warehouse).



### 2.3 Environment Categorizations
* **Fully Observable vs. Partially Observable:** Does the agent see the complete state?
* **Deterministic vs. Stochastic:** Is the next state predictable?
* **Static vs. Dynamic:** Does the environment change while the agent is "thinking"?
* **Discrete vs. Continuous:** Are the steps distinct or fluid?
* **Single-agent vs. Multi-agent:** Are there other agents to compete/cooperate with?

### 2.4 Four Basic Agent Architectures
1. **Simple Reflex Agents:** Select actions based only on the current percept (If-Then rules).
2. **Model-Based Reflex Agents:** Maintain an internal "state" to track parts of the environment they cannot currently see.
3. **Goal-Based Agents:** Use goal information to choose actions that achieve a desired state.
4. **Utility-Based Agents:** Use a utility function to choose the "best" path among many to achieve a goal (maximizing "happiness").