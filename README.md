# 📈 YouTube Trending Video Analysis

This repository contains a **data analysis and visualization project** focused on exploring **YouTube trending videos’ metadata**. The goal is to identify patterns and insights into what makes content go viral by analyzing **views, likes, tags, titles, publish time, and categories**.



## 📑 Table of Contents

* [Introduction](#introduction)
* [Dataset](#dataset)
* [Objectives](#objectives)
* [Technologies Used](#technologies-used)
* [Installation](#installation)
* [Usage](#usage)
* [Analysis Overview](#analysis-overview)
* [Visualizations](#visualizations)
* [Key Insights](#key-insights)
* [Project Structure](#project-structure)
* [Future Work](#future-work)
* [Contributing](#contributing)
* [License](#license)
* [Contact](#contact)



## 📝 Introduction

YouTube is the world’s largest video platform, and understanding what makes videos trend can inform **content strategy, SEO optimization, and marketing decisions**. This project analyzes **trending videos' metadata** to uncover:

✅ Popular video categories

✅ Optimal publish times

✅ Correlation between tags, likes, and views

✅ Title and tag patterns in viral content



## 📚 Dataset

* **Source:** [Kaggle - YouTube Trending Video Dataset]()
* **Data Includes:**

  * `video_id`, `title`, `channel_title`, `category_id`, `publish_time`, `tags`, `views`, `likes`, `dislikes`, `comment_count`, `thumbnail_link`, `trending_date`, `description`



## 🎯 Objectives

✔️ Analyze views, likes, and comment counts distributions

✔️ Identify the most popular video categories and channels

✔️ Explore title and tag word clouds for trending content

✔️ Analyze publish times for optimal trending

✔️ Find correlation patterns between likes, views, and comments



## ✨ Features

* Load and preprocess YouTube trending dataset
* Data cleaning for missing and duplicate values
* Visualizations:

  * Bar charts for top categories and channels
  * Word clouds for titles and tags
  * Heatmaps for feature correlations
  * Time series plots for publish times vs. views
* Generate actionable insights for content strategies



## 🛠️ Technologies Used

* **Python 3**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Seaborn**
* **WordCloud**
* **Jupyter Notebook**



## ⚙️ Installation

1. **Clone the repository**

```bash
git clone https://github.com/yourusername/YouTube_Trending_Video_Analysis.git
cd YouTube_Trending_Video_Analysis
```

2. **Create a virtual environment (optional)**

```bash
python -m venv venv
source venv/bin/activate  # macOS/Linux
venv\Scripts\activate     # Windows
```

3. **Install dependencies**

```bash
pip install -r requirements.txt
```

4. **Launch Jupyter Notebook**

```bash
jupyter notebook
```



## ▶️ Usage

1. Open `YouTube_Trending_Video_Analysis.ipynb` in Jupyter Notebook.
2. Run cells sequentially to:

   * Load and clean the data
   * Perform exploratory data analysis (EDA)
   * Visualize insights and trends



## 📊 Analysis Overview

* **Top Trending Categories:** Which categories appear most frequently
* **Channel Analysis:** Most featured channels in trending videos
* **Publish Time Analysis:** Best times for publishing trending content
* **Likes vs Views Correlation:** Do likes strongly correlate with views?
* **Title and Tag Analysis:** Common keywords and their impact on virality



## 📸 Visualizations

* 📈 **Bar Charts:** Top video categories and channels by number of trending videos
* 🔥 **Word Clouds:** Titles and tags from trending videos
* 🗓️ **Time Series:** Views vs. publish time trends
* 🔍 **Heatmap:** Feature correlations (views, likes, comments)

> *(Screenshots coming soon)*



## 🔍 Key Insights

* 🎬 **Entertainment, Music, and Comedy** are top trending categories.
* 🕒 Videos published during **evenings (local time)** tend to gain more traction.
* 💬 Titles with **emotional or actionable words** perform better.
* 🔖 Tags improve searchability but have diminishing returns beyond a certain count.
* 👍 Likes and views are **positively correlated**, indicating that higher engagement often leads to better ranking.



## 📁 Project Structure

```
YouTube_Trending_Video_Analysis/
 ┣ data/
 ┃ ┗ USvideos.csv
 ┣ YouTube_Trending_Video_Analysis.ipynb
 ┣ requirements.txt
 ┗ README.md
```



## 💡 Future Work

* Extend analysis to **multiple countries** for global trends
* Build **predictive models** for views or trending likelihood
* Integrate **sentiment analysis** on video titles and descriptions
* Create a **dashboard with Streamlit or Plotly Dash** for interactive exploration



## 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/YourFeature`)
3. Commit your changes (`git commit -m 'Add YourFeature'`)
4. Push to your branch (`git push origin feature/YourFeature`)
5. Open a pull request



## 📄 License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.



## 📬 Contact

**Ugama Benedicta Kelechi**
[LinkedIn](www.linkedin.com/in/ugama-benedicta-kelechi-codergirl-103041300) | [Email](mailto:ugamakelechi501@gmail.com) | [Portfolio](#)



### ⭐️ If you find this project insightful, please give it a star and share with data science and digital marketing learners!

