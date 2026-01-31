# 🤖 Hybrid AI Palindrome & Sentiment Analyzer

A high-performance Python API that combines **classical algorithmic logic** with **Modern Transformer-based AI**. 

## 🚀 What this project does
This API analyzes text inputs to provide two distinct types of data:
1.  **Palindrome Check:** Determines if the word is the same forward and backward.
2.  **Sentiment Analysis:** Uses Artificial Intelligence to detect if the text is Positive or Negative.

## 🧠 Engineering Highlights

### 1. Optimized Algorithm ($O(n)$)
I implemented the palindrome check using the **Two-Pointer Technique**. 
* **Time Complexity:** $O(n)$ — The algorithm traverses the string only once.
* **Space Complexity:** $O(1)$ — It does not create a copy of the string, making it memory-efficient.

### 2. AI Architecture
The sentiment analysis is powered by **DistilBERT**, a Transformer model. This model uses the **Attention Mechanism** to understand the context of words in a sentence.

## 🛠️ Setup Instructions
1. **Activate the environment:**
   ```powershell
   .\venv\Scripts\activate