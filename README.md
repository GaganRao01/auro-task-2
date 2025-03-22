# Auro Tutor - Task 2 Submission

Hey everyone! This is my submission for the second task assigned by Auro as part of the hiring process. The goal here is to analyze the existing Auro Tutor, identify key issues, and propose a comprehensive plan to improve it.

## 🔍 Feature Analysis - Improving Auro Tutor
### Selected Feature: **Auro Tutor** (Reading Section)

Auro Tutor is a key feature in Auro.Edu, designed to assist learners in understanding course material. However, the current implementation has major limitations that hinder its effectiveness. My proposed improvements focus on making the tutor more context-aware and interactive, ensuring a smoother and more intuitive learning experience.

### ⚠️ Current Limitations
The current Auro Tutor has several critical issues that negatively impact the user experience:

#### **Reading Module Limitations for each chapters inside the course content:**
1. **Content awareness** – The Tutor has access or processes reading material, but is ineffective of understanding the material. It answers the first question but does'nt answer the follow up questions accurately when the follow-up question is a different topic from the first question.
provides only basic definitions, lacking depth, personalie and real-world examples.                                                                                                                                                                                                                                                                                                                                             
3. **Copy Restriction** – Users cannot copy text, limiting note-taking and research capabilities.
4. **Lack of Contextual Understanding** – Responses are often generic and rule oreiented fail to provide an personalized answer.

#### **Video Module Limitations:**
4. **Lack of Temporal Context** – The Tutor does not understand questions tied to specific video timestamps (e.g., "Explain what was said at 2:30").
5. **Transcript Ignorance** – The Tutor cannot answer questions based on the video's exact wording or concepts, even when directly mentioned.

#### **Flashcard Module Limitations:**
6. **Superficial Understanding** – The Tutor provides only basic definitions, lacking depth and real-world examples.

#### **Revision Plan for Final Exam Tutor Limitations:**
7. **Pre-Answer Help Limitation** – The Tutor only offers 2 options (i). Revise weak concepts. (ii). Revise questions you got wrong. there is no text box for the user to enter question manually instead of searching the pre tabs.
8. **Post-Answer Explanation Absence** – The Tutor only reveals the correct/incorrect answer without providing explanatory reasoning.
9. **Inaccurate "Weak Concepts" Identification** – The "Revision Plan" incorrectly identifies weak areas, leading to a non-personalized and inefficient review process.

#### **General Limitations Across Modules:**
10. **Limited Conversational Memory** – The Tutor does not remember past interactions, making multi-step queries frustrating.
11. **Keyword Reliance** – Answers are based on keyword matching rather than true comprehension.
12. **No Text Input Box in the Revision Plan for Final Exam Tutor** – Users cannot freely type complex or multi-part questions.
13. **Lack of Personalization** – The Tutor does not tailor responses based on user progress or weak areas.

### 🚀 Proposed Improvements
- **Enable Contextual AI Processing** – Implement LLM + RAG for improved reading comprehension and precise responses.
- **Allow Text Highlighting & Copying** – Give users the ability to copy text for better note-taking and research.
- **Improve Context Awareness in Videos** – Link responses to specific timestamps and integrate transcript-based answers.
- **Expand Flashcard Explanations** – Provide deeper insights and real-world examples beyond basic definitions.
- **Enhance Quiz Assistance** – Offer hints before answering and provide detailed post-answer explanations.
- **Refine Weak Concept Identification** – Improve adaptive learning to personalize revision plans more effectively.
- **Introduce Session-Based Memory** – Maintain conversational context for a smoother and more interactive learning experience.
- **Move from Keyword Matching to True Comprehension** – Use AI to understand intent rather than just scanning for keywords.
- **Add a Free-Form Text Input Box** – Allow users to ask complex, multi-part questions freely.
- **Personalized Learning Paths** – Adapt responses based on user history, progress, and weak areas.

  #### RAG (Retrieval-Augmented Generation) and Context Awareness work with Session-Based Memory and Personalized Learning Paths in Auro Tutor.
  ![RAG and Context Awareness](auro.png)
  

### 🖌️ Low-Fidelity Wireframe
To visualize the improved Auro Tutor, I’ve created a wireframe in Figma showcasing the new features and user flow.

[Figma Link: Auro Tutor - Reading Section](https://www.figma.com/design/O8vwJbUUTvXLFwmVlwk8Dj/Gagan-N's-team-library?node-id=3312-2&t=oG0FnrfRwrcZIPWp-1)

---

## 🔄 User Journey - Improved Tutor in Action
1. **User enters the reading module** – They begin engaging with the course content.
2. **Seeking Help (Highlighting Text)**
   - User copies a confusing sentence.
   - A floating "Auro Tutor" icon appears at the right down corner of the screen.
   - User pastes the confusing sentence and clicks the icon to get an instant explanation.
   - Tutor provides an AI-generated, context-aware response.
3. **Copy Functionality**
   - User can copy highlighted text for note-taking.
4. **Conversational Follow-Up**
   - User asks follow-up questions in a chat-like interface.
   - Tutor maintains conversation context for coherent responses.
5. **User Continues Learning**
   - The Tutor remains available for assistance, ensuring a seamless study session.

---

## 🌟 Why This Matters
- ✅ **Fixes Key Learning Barriers** – Enables deeper understanding through context-aware AI.
- ✅ **Enhances Retention** – Personalized, interactive explanations keep learners engaged.
- ✅ **Improves Usability** – Intuitive highlighting, copy options, and conversational AI streamline learning.

---

## 🛠️ Product Analysis (To Be Completed)

As a Product Manager at Auro.Edu, I would also analyze the broader aspects of the app, including UI/UX, user engagement, retention, and monetization. Below, I will list three key improvements for the platform based on user testing.

*(Detailed product analysis and recommendations will be added here.)*

This transformation turns Auro Tutor from a basic, frustrating tool into an **intelligent, AI-powered learning companion**. 🚀

---

That’s it for my second task! Let me know if you have any feedback. Looking forward to the next step. 😊

