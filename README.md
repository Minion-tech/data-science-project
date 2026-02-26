# Data Science Projects

Hey! I'm glad you're here. This repo is a collection of data science work I've done over the past while, some of it from Angela Yu's 100 Days of Code bootcamp, and some of it independent projects I took on to solve real-world problems.

I'll be honest, when I started the 100 Days of Code, I had no idea how deep I'd go into data. But somewhere around the analytics projects, it just clicked. So here's everything, laid out as clearly as I can.


## 100 Days of Code: Angela Yu (Data Science Projects)

These three were part of the bootcamp curriculum. They're not fancy, but they taught me how to actually think with data.

###  LEGO Analysis
I looked at LEGO's dataset sets, themes, parts, years and tried to figure out how the product line has evolved over time. Things like which themes dominated certain decades, how the number of pieces per set has changed, and which colors appear most. It was a fun one because, well, it's LEGO.

**Tools used:** Python, Pandas, Matplotlib, Seaborn

###  Google Play Store App Analytics
This one was about understanding what makes an app successful on the Play Store. I cleaned up a pretty messy dataset and explored things like ratings distribution, category performance, free vs paid apps, and install counts. Good practice for dealing with real-world dirty data.

**Tools used:** Python, Pandas, Plotly

###  Google Trends & Data Visualization
Used Google Trends data to explore how search interest correlates with real-world events, things like Bitcoin prices, Tesla stock, and unemployment rates. Mostly a visualization project, but it sharpened my eye for storytelling with charts.

**Tools used:** Python, Pandas, Matplotlib

---

## Independent Projects

These two I built outside the bootcamp because I wanted to work on problems with actual stakes.

###  Paisabazaar Credit Risk Analysis

**The problem:** A financial institution was spending too much time manually evaluating loan applicants, and even then, high-risk borrowers were slipping through the cracks leading to defaults that cost real money.

**What I did:** I built a credit risk assessment model that automates the evaluation of a customer's creditworthiness. The dataset included financial history, repayment behavior, income data, and other personal financial indicators. After cleaning and exploring the data, I engineered relevant features and tested several classification models to identify which customers were likely to default.

The goal wasn't just accuracy  it was about making something a financial team could actually trust and use. So I paid a lot of attention to interpretability alongside performance.

**Tools used:** Python, Pandas, Scikit-learn, Matplotlib, Seaborn

---

###  Retail Analytics: Sales Forecasting

**The problem:** Retail stores struggle to get their inventory and staffing right because predicting weekly sales is genuinely hard. Too much stock costs money. Too little loses customers. The business needed a reliable forecasting system.

**What I did:** I worked with three datasets, historical sales data, store-level features (including economic indicators and promotional markdowns), and store metadata (size and type). After merging and cleaning everything, I built and compared multiple forecasting models.

The winner was **XGBoost**, and it wasn't particularly close. It handled the non-linear relationships between economic conditions, promotions, and sales really well. The final model's MAE and RMSE were low enough to be genuinely useful in dollar terms, meaning the average forecast error was small enough that a business could actually plan around it.

**Tools used:** Python, Pandas, Scikit-learn, XGBoost, Matplotlib, Seaborn

---

## A Note on the Journey

I didn't start knowing any of this. The bootcamp gave me the foundation, and the independent projects gave me the confidence that I could take a messy real-world problem and actually do something useful with it. There's still a lot to learn, there always is — but I'm proud of what's in this repo.

If you have questions or want to talk through any of the projects, feel free to reach out.
