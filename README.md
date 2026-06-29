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

<img width="258" height="221" alt="Screenshot 2026-06-29 133546" src="https://github.com/user-attachments/assets/f70707da-34d3-4dd5-862e-fc1f9a56f969" />
<img width="291" height="155" alt="Screenshot 2026-06-29 133528" src="https://github.com/user-attachments/assets/c99384cb-00ae-455a-80f9-c11a5f04336f" />
<img width="411" height="531" alt="Screenshot 2026-06-29 133453" src="https://github.com/user-attachments/assets/193c1b4c-afc9-417d-97ef-43447dec799f" />
<img width="317" height="523" alt="Screenshot 2026-06-29 133436" src="https://github.com/user-attachments/assets/e053a21f-bca3-427f-a4bd-985468bdf67d" />



