# **Quantum Nexus – AI Voice Assistant**

Quantum Nexus is a smart, gesture-activated voice assistant built using Python and powered by state-of-the-art large language models via the Groq API. This assistant provides intelligent, natural language conversations with voice input and output. It is optimized for performance, minimal latency, and modularity, making it perfect for AI developers, hobbyists, and robotics researchers.

---

##  **Key Highlights**

-  **AI-Powered Intelligence**  
  Integrates with Groq's blazing-fast inference backend to deliver high-quality responses using LLaMA 3.3 70B.

-  **Voice Command Recognition**  
  Automatically listens for commands only after detecting a keyword using `SpeechRecognition`.

-  **Gesture-Based Activation**  
  Assistant is only triggered after detecting a specific user-defined gesture (e.g., hand wave or keyboard shortcut).

-  **Text-to-Speech Output**  
  Replies are spoken aloud using `pyttsx3`, enabling natural, fluid communication.

-  **Low-Latency Design**  
  Optimized for fast AI responses by using Groq's ultra-performant model API.

-  **Modular Codebase**  
  Cleanly separated modules for voice input, gesture handling, AI interfacing, and output.

---

##  Technologies Used

| **Component**           | **Library / Tool**   |
|--------------------|--------------------------|
| Voice Input         | `speechrecognition`, `pyaudio` |
| Voice Output        | `pyttsx3`                |
| AI Engine           | Groq API (LLaMA 3.3 70B) |
| Activation Trigger  | `keyboard` / `cv2` (gesture/key) |
| API Interaction     | `requests`               |
| Language            | Python 3.9+              |
| OS Compatibility    | Windows / Linux          |

---


