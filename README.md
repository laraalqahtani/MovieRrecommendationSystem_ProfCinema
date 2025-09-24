
<p align="center">
  <img width="357" height="202" alt="Screenshot 2025-09-24 at 5 50 22 PM" src="https://github.com/user-attachments/assets/878637ad-0005-4277-8b74-e0ce1cadb24e"/>
</p>

# 👨🏻‍🏫 Prof Cinema – AI Movie Recommendation App  

Prof Cinema is a **rule-based AI system** designed to help users **find movies** based on their preferences.  
The app suggests one or multiple movies depending on **Category, Language, Rating, and Seasons of the Year**.  

---

## ✨ Features  
- 🎬 **Movie Suggestions** – Get movie recommendations based on your choices  
- 🏷️ **Category Selection** – Filter movies by genre (Action, Comedy, Drama, etc.)  
- 🌐 **Language Options** – Choose movies in your preferred language  
- ⭐ **Rating Filter** – Find movies that match your desired rating  
- 🌦️ **Seasonal Recommendations** – Movies suggested according to the season of the year  

---

## 🧠 Knowledge Acquisition  

Prof Cinema is an **expert system** that uses a **knowledge base** to provide movie recommendations based on specific user preferences.  
The process of collecting and organizing information is called **Knowledge Acquisition (KA)**.  

### Objectives of Knowledge Acquisition  
- Gather the necessary knowledge about movies  
- Validate newly acquired information  
- Ensure the correctness and reliability of the collected data  

### Sources of Knowledge  
Our system's knowledge was collected from **trusted movie sources**:  
- [Rotten Tomatoes](https://www.rottentomatoes.com/)  
- [IMDb](https://www.imdb.com/)  

We collected data such as:  
- Movie Name  
- Genre  
- Language  
- Age Restriction  
- Season of Release  

### Knowledge Base Details  
- **Rules:** 13  
- **Facts (Movies):** 154  
- **Attributes:** Name, Genre, Language, Age Restriction, Season of Release  

This knowledge base enables Prof Cinema to **accurately recommend movies** based on user preferences.

---

## 🎯 Data & Recommendations  

Our database covers **film characteristics** such as:  
- Age restrictions  
- Genre  
- Industry  
- Season of release  

This ensures a **varied and diverse movie selection**.  

Prof Cinema considers factors like **language, rating, and season** to provide an **enjoyable movie-watching experience**.  
The system includes **global film industries** and a **'No Preference'** category, making it adaptable to **diverse audience preferences**.

---

## 🛠️ Tools  

| Tool        | Purpose                                                   |
|------------|-----------------------------------------------------------|
| SWI Prolog | To consult facts and rules and to employ logical methods |

---

## 🛠️ Tech Stack  
- **Language:** SWI Prolog  
- **Framework / Environment:** Rule-based Expert System  
- **Database:** Facts and Rules stored within Prolog  

---

# 📸 App Screenshots  

### Some of the Rules:

<img width="452" height="357" alt="image" src="https://github.com/user-attachments/assets/639ac912-862f-49a4-81e5-a1e060983cb3" />

## The Interface:

<img width="485" height="445" alt="image" src="https://github.com/user-attachments/assets/3bcd80a7-5ea1-4465-94f6-3b2799b339ed" />



---

## 🚀 Getting Started  

### Prerequisites  
- SWI Prolog installed  
- IDE or code editor (Optional, e.g., VS Code, Atom)  

### Installation

1. **Download the ZIP file** of the Prof Cinema project from the repository.
2. **Extract the ZIP file** to a folder on your computer.
   - On Windows: Right-click → Extract All  
   - On Mac: Double-click the ZIP file  
   - On Linux: Use `unzip filename.zip` in terminal
3. **Open SWI Prolog** or your preferred IDE.
4. Load the main Prolog file (`main.pl` or equivalent) using the `consult` command:
   ```prolog
   ?- consult('main.pl').
