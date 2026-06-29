# GroupDNA - WhatsApp Chat Analyzer

## Project Description

GroupDNA is a WhatsApp Chat Analyzer developed using Python and NumPy. It reads an exported WhatsApp chat file and generates a detailed text-based report about group activity, messaging patterns, and participant behaviour.

This project is built using only Python fundamentals and NumPy without using Pandas, Matplotlib, or Regular Expressions.

---

## Features

### Feature 1 – Chat Parser
- Reads the WhatsApp chat file.
- Separates date, time, sender and message.
- Counts system messages, media messages and deleted messages.

### Feature 2 – Group Overview
- Total messages
- Total participants
- Chat period
- Messages sent by each participant

### Feature 3 – Most Active Day and Hour
- Finds the busiest day.
- Finds the busiest hour in the chat.

### Feature 4 – Activity Heatmap
- Displays participant activity by hour using a text-based heatmap.

### Feature 5 – Favourite Words
- Finds the most frequently used words after removing common stop words.

### Feature 6 – Response Patterns
- Finds the fastest and slowest replier.
- Calculates average response time.

### Feature 7 – Longest Silent Streak & Personality Archetypes
- Calculates consecutive silent days.
- Classifies users into personality archetypes such as:
  - The Spammer
  - The Storyteller
  - The Night Owl
  - The Group Mom
  - The Drama Queen
  - The Ghost

### Feature 8 – Conversation Starter Detection
- Detects who starts the most conversations after long inactive periods.

### Final Report
- Generates a complete GroupDNA report containing all analysis in a clean text format.

---

## Technologies Used

- Python 3
- NumPy
- Google Colab

---

## Constraints Followed

- No Pandas
- No Matplotlib
- No Regular Expressions (Regex)
- No external visualization libraries

---

## Files

- GroupDNA_Suhasini_<RollNumber>.ipynb
- hostel_bois.txt
- README.md

---

## How to Run

1. Open the notebook in Google Colab.
2. Upload the `hostel_bois.txt` file.
3. Run all notebook cells from top to bottom.
4. The final GroupDNA report will be displayed.

---

## Output

The notebook generates a report containing:

- Group Overview
- Messages Per Person
- Activity Heatmap
- Favourite Words
- Response Patterns
- Longest Silent Streaks
- Personality Archetypes
- Conversation Starter Detection


# NoteBook Link 
https://colab.research.google.com/drive/1eWm9I34O51tlcO6UkDVW6Y3VqYM6f_I6?usp=sharing

- Final GroupDNA Report

---

## Author

**Suhasini Mallick**


## Sample output

<img width="502" height="220" alt="Screenshot 2026-06-29 135404" src="https://github.com/user-attachments/assets/91c5eb64-75fc-47f6-9923-a2138124f630" />
<img width="459" height="228" alt="Screenshot 2026-06-29 135354" src="https://github.com/user-attachments/assets/809c69c7-e1b7-4156-9c33-20b96bc326f2" />
<img width="258" height="221" alt="Screenshot 2026-06-29 133546" src="https://github.com/user-attachments/assets/4ac829b4-2fe1-4ef7-b59a-d6abfd058232" />
<img width="291" height="155" alt="Screenshot 2026-06-29 133528" src="https://github.com/user-attachments/assets/e6377f39-c46b-40d0-90bb-ea9884998cc2" />


