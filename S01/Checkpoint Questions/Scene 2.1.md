#### **Scene 2.1**

1. **Which of these is the most "targeted" analytical query about a delivery app's cancellation data?**  
   a) "Tell me about this data."  
   b) "Which city has the highest cancellation rate, and how much higher is it than the city average?"  
   c) "Any interesting patterns here?"  
   d) "Analyze this and give me insights."  

   **Answer:** b) "Which city has the highest cancellation rate, and how much higher is it than the city average?"  

   **Explanation:** A targeted query names a specific comparison and asks for a measurable gap. The other three are open-ended requests that tend to produce a vague, hard-to-act-on essay.

2. **What best describes a prompt chain?**  
   a) A single very long prompt that lists every possible question at once  
   b) A prompt that must be repeated word-for-word three times to work  
   c) A method for encrypting a prompt so competitors cannot read it  
   d) A sequence of connected prompts, where each one builds on the answer to the one before it  

   **Answer:** d) A sequence of connected prompts, where each one builds on the answer to the one before it  

   **Explanation:** Prompt chaining means asking a first question, reading the answer, and then asking a sharper follow-up based on what came back — mirroring how a human analyst explores data one step at a time.

3. **A student asks an AI tool: "Which quarter had the highest revenue?" The AI answers, then the student asks: "Now break that quarter down by region — which region drove most of that growth?" What technique is this student practising?**  
   a) A guided exploratory follow-up (EDA-style prompt chain)  
   b) Zero-shot prompting with no context at all  
   c) Asking the AI to hallucinate a plausible-sounding region  
   d) Tokenization of the revenue figures  

   **Answer:** a) A guided exploratory follow-up (EDA-style prompt chain)  

   **Explanation:** Asking a first question, then a sharper follow-up that reacts to the answer, is exactly the guided exploratory pattern this lesson teaches — look at the data from more than one angle before concluding anything.

4. **A comparison shows Region X converting at 60% (built from 500 customers) and Region Y converting at 65% (built from only 12 customers). Why should Region Y's number be treated with more caution?**  
   a) It should not — a higher percentage is always more trustworthy  
   b) Region Y's number is impossible to calculate at all  
   c) Region Y's percentage is built on a much smaller sample size and could swing wildly by chance  
   d) Percentages built on fewer customers are always exactly accurate  

   **Answer:** c) Region Y's percentage is built on a much smaller sample size and could swing wildly by chance  

   **Explanation:** A percentage built on very few data points is far less reliable than one built on a large sample — a small sample size is one of the clearest warning signs that a "finding" might just be noise.

5. **Four variables are tested against a conversion outcome: Variable A spans 15%–95% across its groups; Variables B, C, and D each span less than 8 points across their groups. Which is the most reasonable next step?**  
   a) Treat all four variables as equally important and act on all of them at once  
   b) Investigate Variable A further; treat B, C, and D as likely flat and set them aside for now  
   c) Ignore Variable A because a wide spread always means the data is broken  
   d) Discard all four variables because any spread under 100 points is meaningless  

   **Answer:** b) Investigate Variable A further; treat B, C, and D as likely flat and set them aside for now  

   **Explanation:** A wide, consistent spread (like Variable A's) is the signal worth chasing. Variables with only a few points of spread are close to flat and are a valid, useful "nothing here" finding, not a reason to manufacture a story.
