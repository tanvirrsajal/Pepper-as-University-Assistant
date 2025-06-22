# Pepper-as-University-Assistant

## Overview

This project showcases the use of a social robot, **Pepper**, to assist university students with everyday campus-related tasks. Designed as an interactive and intelligent assistant, Pepper is equipped with several demonstration modules to explore how social robots can support campus life by handling common student needs such as answering questions, offering directions, and facilitating event and club participation, it can be applied in broader range in the future.

The system is built using **Choregraphe**, allowing seamless behavior structuring and module integration. By leveraging natural language processing and a modular design, the robot ensures that interactions are intuitive, responsive, and contextually relevant.

## Problem Statement

University campuses can often be challenging to navigate, especially for new students. Finding accurate information, staying up-to-date with campus events, or joining extracurricular activities can become overwhelming. This project addresses these challenges by deploying Pepper as a central, physical point of interaction. Pepper acts as a bridge between students and campus services, enhancing accessibility and streamlining student engagement.

## Features

This project implements and demonstrates several key interaction modules to explore Pepper's potential role as a university assistant. These features are meant to show what is possible and can be expanded further in the future:

- **FAQ Module**: Demonstrates how Pepper can answer frequently asked questions about university services, processes, or general information using predefined responses.
- **Navigation Module**: Simulates campus navigation by enabling Pepper to provide directional guidance or indicate locations within the university environment.
- **Club Registration Module**: Allows users to interact with Pepper to submit their information for joining clubs. This showcases the robot’s ability to handle basic form-like data collection tasks.
- **Events Module**: Presents a way for Pepper to display information about upcoming events and enables mock registration, highlighting its potential for promoting campus activities.

These modules focus on task-specific interactions that are commonly needed by students. They serve as a foundation to illustrate how social robots like Pepper could be integrated into educational environments to support and enhance daily student experiences.

## Rationale Behind Design Choices

The system was designed with the following principles in mind:

- **Modular Architecture**: Each module handles a specific interaction, which increases system robustness and scalability.
- **Natural Language Interaction**: Students interact with Pepper using natural, conversational language, improving accessibility and user satisfaction.
- **Relevant Features**: Selected functionalities directly address real student needs to ensure practicality and adoption.
- **Choregraphe Integration**: Leveraging Choregraphe allowed seamless orchestration of the robot’s behaviors, making the overall experience smooth and engaging.

These choices were made to ensure that Pepper feels knowledgeable, trustworthy, and genuinely helpful — boosting the perception of the robot’s intelligence and effectiveness.

## Statistical Analysis Results

We carried out a survey based on the **Godspeed Questionnaire** to assess user perceptions and interaction quality. Statistical tests were conducted to study the relationships between different variables. Hypotheses were derived from the context and data (questionnaire), and their validity was tested.

We studied the relationships (or lack thereof) between the following variables:

1. Gender and Conversational perception  
2. Emotional connection and likeability  
3. Engagement and enjoyability  
4. Perceived intelligence and trustability  
5. Trusting and feeling comfortable in interacting with the robot  
6. Feeling secure and comfortable in interacting with the robot  
7. Predictability and competence

Approach:
- Compute correlation between the variables
- For multiple variables per concept, average the scores and compute correlation
- Compute t-statistic from the correlation
- Compute the p-value to accept or reject the null hypothesis

### Results:

- **Gender and Conversational perception**  
  Null Hypothesis: The population average score for both males and females for perceived conversational skills is the same.  
  **Result**: We reject the null hypothesis (with a 5% error probability), confirming that there is statistical significance between gender and the perceived conversational skills of the robot.

- **Emotional connection and likeability**  
  Null Hypothesis: There is no significant relationship between participants' perception of emotional connection (based on specific metrics like gestures, emotions, and responsiveness) and their overall perception of Pepper's likeability.  
  **Result**: p-value is <0.005, we can reject the null hypothesis! Therefore, there exists a relationship between Pepper's emotional connection and overall likeability.

- **Engagement and enjoyability**  
  Null Hypothesis: There is no significant relationship between how engaging Pepper is and how enjoyable users find the interaction.  
  **Result**: p-value: 0.504005123. So we cannot reject the null hypothesis! There is no statistically significant relationship between these two variables.

- **Perceived intelligence and trustability**  
  Null Hypothesis: The perceived intelligence of Pepper does not significantly impact trust in the robot.  
  **Result**: p-value = 0.34 > 0.05, there is no statistical relationship between perceived intelligence and trust in the robot. The null hypothesis holds true.

- **Trusting and feeling comfortable in interacting with the robot**  
  Null Hypothesis: There is no significant correlation between the level of trust and comfort with Pepper.  
  **Result**: p-value = 0.109264398 > 0.05, there is no statistical relationship between trust and comfort.

- **Feeling secure and comfortable in interacting with the robot**  
  Null Hypothesis: There is no significant correlation between the perceived safety and comfort levels during interactions with Pepper.  
  **Result**: p-value = 0.537746365 > 0.05, there is no statistical relationship between perceived security and comfort.

- **Predictability and competence of Pepper**  
  Null Hypothesis: There is no significant correlation between the perceived predictability and competence of Pepper.  
  **Result**: p-value = 0.59 > 0.05, there is no statistical relationship between predictability and competence of Pepper.

The results of the test can be seen in the excel file.

## Conclusion

The project successfully demonstrated the potential of social robots in a university setting. While the correlation analysis shows minimal linkage between perceived intelligence and trust, qualitative feedback indicates that the robot’s ability to interact and assist effectively was highly appreciated by users. Future improvements could focus on enhancing the robot’s emotional engagement, personalization of responses, and adaptability to further strengthen user trust and satisfaction.

## Requirements

- **Hardware**: Pepper robot
- **Software**:
  - Choregraphe
  - Microsoft Excel (for analyzing survey responses and statistical data)

## How to Run

1. **Open Choregraphe**: Ensure you have the Choregraphe suite installed and connected to the Pepper robot.

2. **Load the Project**: Import the project `.crg` or behavior flow files into Choregraphe.

3. **Upload to Pepper**: Connect to your Pepper robot via its IP address and deploy the project.

4. **Initiate Interaction**: Use the green run button, once the behavior is running, interact with Pepper via voice or giving the commang by writing.
