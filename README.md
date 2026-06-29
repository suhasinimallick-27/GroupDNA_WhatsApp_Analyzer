
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
- Final GroupDNA Report

---

## Author

**Suhasini Mallick**
