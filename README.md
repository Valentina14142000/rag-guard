# RAG Guard Sandbox

RAG Guard Sandbox is a diagnostic tool designed to test the robustness of Large Language Model (LLM) applications against adversarial attacks and prompt injection. It simulates a Red-Teaming environment where an attacker attempts to extract confidential information from a target RAG system.

## Features

*   **Adversarial Simulation:** Automates multi-turn attack strategies to probe system vulnerabilities.
*   **Safety Evaluation Engine:** Automatically scores the victim system's responses for data leakage and jailbreak success.
*   **Real-time Streaming:** Uses Server-Sent Events (SSE) to visualize the attack-defense loop in real-time.
*   **Sandbox Isolation:** Easily configure target system instructions and knowledge base documents for testing.


### Prerequisites

*   Python 3.10+
*   Node.js (for the frontend)
*   An API Key (Gemini API Key)


## Project Structure

*   `backend/`: Contains the FastAPI application, RAG simulation logic, and the safety evaluation engine.
*   `assets/`: Contains project screenshots and architectural diagrams.

## License

This project is licensed under the MIT License.
