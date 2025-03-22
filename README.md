# Auro Tutor - Task 2 Submission

Hey everyone! This is my submission for the second task assigned by Auro as part of the hiring process. The goal here is to analyze the existing Auro Tutor, identify key issues, and propose a comprehensive plan to improve it.

## 🔍 Feature Analysis - Improving Auro Tutor
### Selected Feature: **Auro Tutor** (Reading Section)

Auro Tutor is a key feature in Auro.Edu, designed to assist learners in understanding course material. However, the current implementation has major limitations that hinder its effectiveness. My proposed improvements focus on making the tutor more context-aware and interactive, ensuring a smoother and more intuitive learning experience.

### ⚠️ Current Limitations
The current Auro Tutor has several critical issues that negatively impact the user experience:

#### **Reading Module Limitations:**
1. **Content Unawareness** – The Tutor cannot access or process reading material, making it ineffective for content-specific questions.
2. **Copy Restriction** – Users cannot copy text, limiting note-taking and research capabilities.
3. **Lack of Contextual Understanding** – Responses are often generic and fail to consider highlighted text.

#### **Video Module Limitations:**
4. **Lack of Temporal Context** – The Tutor does not understand questions tied to specific video timestamps (e.g., "Explain what was said at 2:30").
5. **Transcript Ignorance** – The Tutor cannot answer questions based on the video's exact wording or concepts, even when directly mentioned.

#### **Flashcard Module Limitations:**
6. **Superficial Understanding** – The Tutor provides only basic definitions, lacking depth and real-world examples.

#### **Quiz Module Limitations:**
7. **Pre-Answer Help Limitation** – The Tutor offers no assistance or clarification before answer submission.
8. **Post-Answer Explanation Absence** – The Tutor only reveals the correct/incorrect answer without providing explanatory reasoning.
9. **Inaccurate "Weak Concepts" Identification** – The "Revision Plan" incorrectly identifies weak areas, leading to a non-personalized and inefficient review process.

#### **General Limitations Across Modules:**
10. **Limited Conversational Memory** – The Tutor does not remember past interactions, making multi-step queries frustrating.
11. **Keyword Reliance** – Answers are based on keyword matching rather than true comprehension.
12. **No Text Input Box** – Users cannot freely type complex or multi-part questions.
13. **Lack of Personalization** – The Tutor does not tailor responses based on user progress or weak areas.

### 🚀 Proposed Improvements
1. **Persistent Tutor Access** – The Auro Tutor should be available at all times within the reading module, accessible via a floating icon.
2. **Deep Content Understanding** – The Tutor should leverage Generative AI (LLM + RAG) to process and understand the full reading material.
3. **Text Highlight & Copy** – Users should be able to highlight text for instant explanations and have the option to copy content for better note-taking.
4. **Smart Contextual Responses** – Instead of generic answers, the Tutor should generate detailed responses based on highlighted text and previous interactions.
5. **Conversational Memory** – The Tutor should remember past queries within a session, allowing for a natural, multi-turn conversation.

### 🖌️ Low-Fidelity Wireframe
To visualize the improved Auro Tutor, I’ve created a wireframe in Figma showcasing the new features and user flow.

[Figma Link: Auro Tutor - Reading Section](https://www.figma.com/design/O8vwJbUUTvXLFwmVlwk8Dj/Gagan-N's-team-library?node-id=3312-2&t=oG0FnrfRwrcZIPWp-1)

---

## 🔄 User Journey - Improved Tutor in Action
1. **User enters the reading module** – They begin engaging with the course content.
2. **Seeking Help (Highlighting Text)**
   - User highlights a confusing sentence.
   - A floating "Auro Tutor" icon appears next to the highlighted text.
   - User clicks the icon to get an instant explanation.
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

