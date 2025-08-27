# netflix_dashboard
dashboard for netflix data
# 📊 Netflix Insights Dashboard

An interactive dashboard that provides insights into Netflix's catalogue of Movies and TV Shows.  
The dashboard allows filtering by **Type, Rating, and Country**, and visualizes various aspects such as genres, release years, ratings distribution, and more.

---

## 🚀 Features
- Filter by **Type** (Movies / TV Shows)
- Filter by **Rating**
- Search by **Country**
- Visualizations include:
  - Type Mix
  - Content by Country
  - Ratings Distribution
  - Titles Added by Year
  - Release Year Trends
  - Popular Genres
  - Movie Durations
  - TV Show Seasons

---

## 📂 Project Structure
```
Netflix-Dashboard/
│
├── data/
│   └── netflix1.csv              # Dataset
│
├── dashboard/
│   └── netflix_dashboard.html    # Interactive dashboard
│
├── README.md                     # Project documentation
└── requirements.txt              # Dependencies (optional if using Python)
```

---

## 🛠️ Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/Netflix-Dashboard.git
   cd Netflix-Dashboard
   ```
2. Open the dashboard:
   - Simply open `dashboard/netflix_dashboard.html` in your browser.
3. (Optional) If you want to regenerate the dashboard with Python + Plotly:
   - Install dependencies:
     ```bash
     pip install pandas plotly
     ```
   - Run your script to generate/update the HTML.

---

## 📊 Dataset
The dataset `netflix1.csv` contains information about Netflix titles, including:
- **Type** (Movie/TV Show)  
- **Title**  
- **Director**  
- **Country**  
- **Date Added**  
- **Release Year**  
- **Rating**  
- **Duration**  
- **Genres**

---

## 📸 Preview
![Dashboard Preview](https://via.placeholder.com/800x400.png?text=Netflix+Dashboard)

---

## 🤝 Contributing
Contributions are welcome! Feel free to fork this repository and submit a pull request.

---

## 📜 License
This project is licensed under the **MIT License**.
