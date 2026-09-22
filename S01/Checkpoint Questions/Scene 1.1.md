#### **Scene 1.1**

1. **What does AI-assisted data summarization actually produce, in the strict sense?**  
   a) A verified, audited report that a compliance team has already signed off on  
   b) A live connection to your company's database that refreshes every second  
   c) A plain-language description of what a dataset shows, generated from the table it was given  
   d) A guarantee that every number quoted is statistically significant  

   **Answer:** c) A plain-language description of what a dataset shows, generated from the table it was given  

   **Explanation:** AI-assisted summarization turns structured data into a plain-language description. It is not an audit, not a live database connection, and it carries no built-in guarantee of statistical significance.

2. **A teammate is about to paste an entire 20,000-row raw export into a chat tool and ask "summarize this." What should they do first?**  
   a) Shrink the data to the question first: group, count, or average down to a small, clean table  
   b) Nothing — more raw rows always make the AI's summary more accurate  
   c) Ask the AI to invent a plausible-sounding summary without seeing any data at all  
   d) Delete the column headers so the AI is not biased by their labels  

   **Answer:** a) Shrink the data to the question first: group, count, or average down to a small, clean table  

   **Explanation:** A good analyst shrinks data to the question before prompting — a small, clean, aggregated table produces a more useful and checkable summary than a raw dump of thousands of rows.

3. **Which three elements must a complete data summary report, according to this lesson?**  
   a) The file size, the column count, and the name of the person who exported it  
   b) A prediction of next month's numbers, a risk score, and a marketing slogan  
   c) The AI model's name, its training date, and its token limit  
   d) Overall performance, the macro pattern, and any anomalous data points  

   **Answer:** d) Overall performance, the macro pattern, and any anomalous data points  

   **Explanation:** A strong summary states the headline number, describes whether the overall trend is flat/rising/falling, and flags anything that breaks that pattern. The other options are not summary content at all.

4. **A canteen's daily footfall averages 120 people, typically ranging between 100 and 140. One Friday it hits 250. The next Monday it hits 128. Which of these is the real anomaly worth flagging to the AI as unusual?**  
   a) Both the Friday and the Monday numbers are equally unusual  
   b) Only the Friday number (250), because it sits far outside the normal 100–140 range  
   c) Only the Monday number (128), because it is a round-ish figure  
   d) Neither — footfall figures are never worth flagging  

   **Answer:** b) Only the Friday number (250), because it sits far outside the normal 100–140 range  

   **Explanation:** 128 is well within the normal day-to-day range and is not a real anomaly. 250 sits far outside the typical band and is the point worth a second look — exactly the same reasoning used to catch a real spike day in a signup trend.

5. **An AI is given a table showing Product A at 70% customer satisfaction and Product B at 40%. It replies: "Product A clearly satisfies customers, and Product B should be discontinued immediately." Which part of that reply goes beyond what the table can support?**  
   a) Recommending Product B be discontinued immediately, based on satisfaction alone  
   b) Stating that Product A's satisfaction score is 70%  
   c) Stating that Product B's satisfaction score is 40%  
   d) Nothing — the whole reply is fully supported by the table  

   **Answer:** a) Recommending Product B be discontinued immediately, based on satisfaction alone  

   **Explanation:** The two percentages are accurate restatements of the table. A discontinue-the-product decision needs more than one satisfaction number — cost, revenue, and sample size are not in this table, so that recommendation goes beyond what the data can prove.
