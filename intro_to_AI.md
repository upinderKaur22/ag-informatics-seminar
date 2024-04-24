# Introduction to Artificial Intelligence

Artificial Intelligence refers to the field of computer science concerned with creating intelligent agents – systems that can reason, learn, and act autonomously in their environments [1]. These agents mimic human cognitive abilities such as problem-solving, decision-making, and perception to achieve specific goals.

Here's a relevant quote from Stuart Russell and Peter Norvig, authors of a widely used AI textbook: "AI is the study of intelligent agents: any device that perceives its environment and takes actions that maximize its chance of successfully achieving its goals" [1].

Some core characteristics of intelligent agents include:

- Learning: The ability to acquire knowledge and skills from experience. This can involve various techniques like supervised learning, unsupervised learning, and reinforcement learning. 
- Reasoning: The ability to use knowledge to draw inferences and make decisions. This involves processing information, evaluating options, and selecting the most appropriate course of action. 
- Problem-solving: The ability to find solutions to complex problems. This requires the agent to define the problem, explore possible solutions, and evaluate their effectiveness. 

## AI vs. Machine Learning (ML)

Machine learning (ML) is a subfield of AI that focuses on algorithms that can learn from data without being explicitly programmed. ML algorithms can identify patterns and relationships in data, which allows them to make predictions or decisions on new data.

Here's how AI and ML differ:
- Scope: AI is the broader concept encompassing various techniques to achieve machine intelligence. Machine learning is a specific approach to AI that relies on algorithms that can learn from data.
- Focus: AI is concerned with building intelligent agents that can reason, learn, and act autonomously. ML focuses on developing algorithms that can learn from data and make predictions or decisions.

## PEAS and Intelligent Agents

The PEAS framework is a conceptual model used to describe the essential components of an intelligent agent. PEAS stands for:
- Performance: The measure of success for the agent in its environment. This could be winning a game, maximizing efficiency, or completing a task accurately. (https://www.geeksforgeeks.org/understanding-peas-in-artificial-intelligence/)
- Environment: The surroundings in which the agent operates. This includes all the physical and informational aspects that can influence the agent's actions.
- Actuators: The mechanisms through which the agent interacts with the environment. These allow the agent to take actions that affect the environment.
- Sensors: The components that enable the agent to perceive its environment. Sensors gather information about the environment, which the agent processes to make decisions.

### 4. Examples of AI and PEAS in Action

Here are some real-world examples illustrating AI and the PEAS framework:
1. Self-driving car:
        - Performance: Maximize safety and arrive at the destination efficiently.
        - Environment: Roads, traffic, pedestrians, weather conditions.
        - Actuators: Steering wheel, brakes, accelerator.
        - Sensors: Cameras, LiDAR, radar, GPS.
2.  Spam filter:
        - Performance: Minimize spam emails reaching the inbox.
        - Environment: Incoming emails with text and attachments.
        - Actuators: None (acts by classifying emails as spam or not spam).
        - Sensors: Analyzes email content and sender information.
3. Recommendation system:
        - Performance: Recommend products or content relevant to the user's interests.
        - Environment: User browsing history, purchase history, and product information.
        - Actuators: Displays recommendations on a website or app.
        - Sensors: Analyzes user data and product information.

These examples demonstrate how AI systems are designed with specific goals (performance) in mind, operate within defined environments, and interact with the environment through actuators and sensors.

## Rationality in AI Agents

According to Russell and Norvig (2021), a cornerstone of AI research is the concept of a rational agent: an entity that acts with the aim of achieving its goals in a way that is optimal within its environment.
Imagine your friend playing chess. They consider the board, their opponent's moves, and possible strategies before making their next move. This is a form of rationality – making informed decisions to achieve a goal. In AI, we strive to create rational agents that do the same.
- What it means: An AI agent is rational if it consistently chooses actions that maximize its chances of achieving its goals, given its current perception of the environment.
- Example: A self-driving car should choose the safest route based on traffic conditions, weather, and its destination. A bad decision could be running a red light to save a few seconds, potentially causing an accident.

### A breakdown of rationality in AI:
- Decision-making: A rational agent strives to make decisions that maximize its chances of achieving its goals based on its current understanding of the environment.
- Logical reasoning: Rational agents employ logical reasoning to analyze situations and determine the best course of action.
- Bounded rationality: In real-world scenarios, agents may exhibit "bounded rationality" due to limitations in processing power, knowledge, or time. This can lead to suboptimal but still effective decisions.

## Components of AI Systems
AI systems are complex entities composed of various interacting components that mirror the capabilities of an intelligent agent:
- Agent: The AI system itself, acting as an intelligent entity within the environment.
- Reasoning: The capability to use logic, knowledge, and perception to draw conclusions and make decisions.
- Environment: The surroundings in which the agent operates, including all the factors that can influence its actions and perception.
- Actions: The set of possible actions the agent can take to manipulate the environment or achieve its goals.
- Perception: The ability to sense and interpret the environment through sensors or other means of information gathering.

Here are some additional details on the core components:
- Knowledge representation and reasoning (KR&R): This refers to how the AI system stores and manipulates knowledge about the world. Techniques include logic statements, semantic networks, and probability distributions. (Source: Brachman and Levesque, 1985)
- Learning: AI systems can learn from data through various techniques like supervised learning, unsupervised learning, and reinforcement learning.
- Problem-solving: The system employs search algorithms, heuristics, and optimization techniques to tackle complex problems and find solutions.
- Planning and decision-making: AI systems can plan future actions and make decisions based on their knowledge, goals, and perceived environment.

