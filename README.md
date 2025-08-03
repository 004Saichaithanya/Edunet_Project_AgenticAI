# Fitness Buddy

**An AI-powered virtual fitness assistant leveraging IBM Watsonx and Agentic AI for personalized, accessible, and motivational health coaching.**

## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [System Architecture](#system-architecture)
- [How It Works](#how-it-works)
- [Demo Prompts](#demo-prompts)
- [Future Scope](#future-scope)
- [Certificates](#certificates)
- [References](#references)
- [Contact](#contact)

## Project Overview

**Fitness Buddy** addresses the challenge of making healthy living simple, personalized, and accessible. Many struggle with time constraints, motivation, or expensive fitness solutions. Fitness Buddy aims to bridge this gap by providing a friendly AI assistant for on-demand fitness, nutrition, and motivational support—all tailored to individual needs and available any time[1].

## Features

- Personalized fitness advice and workout plans.
- Nutrition guidance, including post-workout snack suggestions.
- Motivation and habit-building support.
- Conversational, natural language interface powered by Agentic AI.
- Maintains user session memory for adaptive coaching[1].

## Technologies Used

- **IBM Watsonx**: For building the conversational AI assistant (Granite 3-3-8b Instruct model).
- **LangGraph**: Orchestrates agent behavior, memory, and dynamic dialogue flow.
- **ReAct Architecture**: Enables reasoning and interactive planning.
- **Cloud Object Storage**: For user session data, preferences, and logs.
- **LLM**: IBM Granite or Meta LLaMA for generating responses[1].

## System Architecture

- **Frontend**: User interacts via chat interface.
- **Backend**: IBM Watsonx Assistant (Granite model), coordinated with LangGraph and ReAct.
- **Database**: Cloud Object Storage for persistent user data.
- **Evaluation**: Tracks session engagement and collects feedback for iterative improvement.

## How It Works

1. **User Interaction & Personalization**: Users input their fitness goals, routines, and preferences.
2. **Agentic AI Response**: The system plans, reasons, and responds, adapting advice in real time.
3. **Continuous Improvement**: Collects usage data and feedback to refine coaching and responses.

## Demo Prompts

- **Workout Planning**:  
  - “I want to build muscle at home and I only have a pair of dumbbells. Can you create a weekly workout plan for me?”  
- **Nutrition Guidance**:  
  - “Suggest a healthy post-workout snack.”  
- **Motivational Support**:  
  - “I skipped workouts for 3 days. I feel guilty.”  
- **Habit Building**:  
  - “Build me a simple morning routine for better energy.”[1]

## Future Scope

- Mobile app integration with reminders and offline support.
- Voice and image input for interactive experiences.
- Advanced personalization using user progress data.
- Integration with wearables for real-time data.
- Multilingual support.
- Calendar integration for scheduling.
- Gamification for increased engagement[1].

## Certificates

- **Getting Started with Artificial Intelligence** *(IBM SkillsBuild, 16 Jul 2025)*
- **Journey to Cloud: Envisioning Your Solution** *(IBM SkillsBuild, 19 Jul 2025)*
- **Completion Certificate: Lab - Retrieval Augmented Generation with LangChain** *(24 Jul 2025)*[1]

## References

- [IBM Watsonx Documentation](https://www.ibm.com/docs/en/watsonx)
- [Agentic AI Overview – IBM Blog](https://www.ibm.com/blog/what-is-agentic-ai)
- [LangGraph Documentation](https://langgraph.dev/)
- [ReAct Prompting – Yao et al., 2022](https://arxiv.org/abs/2210.03629)
- [LLaMA Language Models – Meta AI](https://ai.meta.com/research/publications/llama-open-and-efficient-foundation-language-models/)[1]

## Contact

**Developer:** Poloju Sai Chaithanya  
**Edunet Foundation / AICTE IBM SkillsBuild**

*This project was developed under the IBM SkillBuild AICTE Edunet Internship program.*[1]
