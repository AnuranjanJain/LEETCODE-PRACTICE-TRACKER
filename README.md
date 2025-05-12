
# 🏆 LeetCode Practice Tracker

Welcome to the **LeetCode Practice Tracker**!  
This tool helps you manage your LeetCode journey, track your progress, and maintain a beautifully organized repository of your solutions—complete with auto-generated explanations and statistics.

---

## 🚀 Features

- **Add New Problems Easily:**  
  Add LeetCode problems by URL, interactively, or with manual details. The script fetches problem metadata automatically!

- **Organized by Day:**  
  Solutions are grouped by day, making it easy to track your daily progress and maintain streaks.

- **Auto-Generated Explanations:**  
  Get detailed, well-formatted markdown explanations for your solutions—powered by code analysis or OpenAI (if you have an API key).

- **Progress Dashboard:**  
  The main README and day-specific READMEs show your total problems solved, days completed, and difficulty breakdown.

- **Statistics & Streaks:**  
  View your current streak, longest streak, and a breakdown of problems by difficulty.

- **Header Standardization:**  
  Automatically update and standardize headers in all your solution files.

- **GitHub Integration:**  
  Commit and push your progress to GitHub with a single command.

- **Customizable AI Service:**  
  Choose between local (free) code analysis or OpenAI for generating explanations.

---

## 📦 Directory Structure

```
.
├── update_leetcode.py      # Main script
├── readme.md               # Main progress dashboard (auto-generated)
└── practice/
    ├── day_1/
    │   ├── two_sum.py
    │   ├── two_sum.md
    │   └── README.md
    ├── day_2/
    │   ├── ...
    │   └── README.md
    └── ...
```

- Each `day_X` folder contains your solutions and explanations for that day.
- Each day has its own `README.md` summarizing the problems solved.

---

## 🛠️ How to Use

1. **Run the Script:**
   ```bash
   python update_leetcode.py
   ```
   This launches an interactive menu.

2. **Menu Options:**
   - Add new problems (by URL, interactively, or manually)
   - Update all solution headers
   - Rebuild the main README
   - View statistics
   - Generate or regenerate explanations
   - Generate day-specific READMEs
   - Configure API keys (for OpenAI)
   - Select AI service (local or OpenAI)
   - Upload your progress to GitHub

3. **Adding Problems:**
   - Enter the LeetCode URL or details as prompted.
   - The script fetches the problem name, difficulty, and creates a solution file with a standardized header.

4. **Generating Explanations:**
   - Explanations are generated for each solution, either using local code analysis or OpenAI (if configured).
   - Markdown files are created alongside your solution files.

5. **Uploading to GitHub:**
   - Use the menu to commit and push your changes directly to your repository.

---

## 🤖 AI-Powered Explanations

- **Local (Free):**  
  Uses rule-based code analysis to generate detailed explanations, including approach, steps, complexity, alternatives, and insights.

- **OpenAI (Optional):**  
  If you have an OpenAI API key, you can generate even richer explanations using GPT models.

---

## 📊 Example Statistics Output

```
Total Days: 10
Total Problems: 25
Current Streak: 5 days
Longest Streak: 7 days

Difficulty Breakdown:
  - Easy: 8 (32.0%)
  - Medium: 13 (52.0%)
  - Hard: 4 (16.0%)
```

---

## 🔑 API Key Configuration

- For OpenAI explanations, set your API key as an environment variable:
  - **Windows:** `set OPENAI_API_KEY=your-api-key`
  - **Linux/Mac:** `export OPENAI_API_KEY=your-api-key`
- You can also configure this interactively via the menu.

---

## 💡 Why Use This Tracker?

- **Stay Consistent:**  
  Build and maintain your LeetCode streak with daily tracking.
- **Learn Effectively:**  
  Each solution is paired with a clear, structured explanation.
- **Showcase Your Progress:**  
  Auto-generated READMEs make your repository a great portfolio piece.
- **Automate the Boring Stuff:**  
  Focus on solving problems—let the script handle organization and documentation.

---

## 📝 License

This project is open-source and free to use.  
Created with ❤️ by [AnuranjanJain](github.com/Anuranjanjain).

---

## 🌟 Happy Coding & Keep Crushing LeetCode!

