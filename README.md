# 📊 Interactive Dashboard for Customer Support Data Analysis & Resolution

This interactive dashboard visualizes customer support ticket data to uncover key patterns in ticket volume, channel usage, resolution times, priorities, and customer satisfaction. Designed to support data-driven decision-making in optimizing support operations.

---

## 📷 Dashboard Preview

![Dashboard Preview](./channel_ticket_distribution.png)


---

## 🔍 Key Insights

### 1. **Number of Issues by Channel**
- **Email** is the most used channel (25.3%) while **Chat** is the least (24.48%).
- The difference between channels is minimal (~0.8%), indicating a **well-balanced support system**.
- Slight variations suggest **opportunities for efficiency tuning**, especially in chat support.

---

### 2. **Resolution Time by Priority**
- **Critical and High priority tickets** often exceed **400K ms** in resolution time.
- **Low and Medium priority tickets** are mostly resolved under **300K ms**.
- **Priority level**, rather than ticket type, is the key driver of resolution time.
- There's an opportunity to **optimize high-priority ticket handling**.

---

### 3. **Ticket Volume Over Time & Backlog**
- Ticket volume remained **consistently high (~350–400)** from **2020 to 2022**.
- No downward trend, indicating a **persistent support workload**.
- **Backlog count is high (2,819)** — highlights the need for **resolution efficiency improvements** or **more resources**.

---

### 4. **Ticket Volume by Type**
- All ticket types have similar volumes (~1.6K each).
- **Refund** and **Technical issues** have slightly higher counts.
- Balanced distribution across statuses implies **consistent handling** of each type.

---

### 5. **Ticket Priority Distribution**
- **Medium-priority tickets** dominate (>2200).
- Other priorities (Low, High, Critical) are around **2000 each**.
- Indicates possible **overuse of the 'Medium' label** — priority assignment should be reviewed.

---

### 6. **Customer Satisfaction by Age Group**
- Satisfaction ratings are similar across all age groups (~3).
- The **18–30 group** has the **lowest score (2.99)**, indicating slight dissatisfaction.
- Suggests a need to **enhance support for younger customers**.

---

## 🧰 Tools Used

- **Tableau** – Interactive dashboard creation
- **Google Colab** – Data preprocessing and analysis
- **NumPy** – Numerical operations
- **Matplotlib** – Static data visualizations
- **Seaborn** – Statistical graphing
- **NLTK** – Text and sentiment analysis,Specifically used:
nltk.corpus.stopwords
nltk.tokenize.word_tokenize
nltk.tokenize.TreebankWordTokenizer 

---

