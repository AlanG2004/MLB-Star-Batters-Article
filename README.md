# MLB-Star-Batters-Article
### **Description**
This project analyzes the performance of MLB star batters in the postseason compared to the regular season. Using advanced statistics such as SLG (Slugging Percentage), OBP (On-Base Percentage), and pLI (Player Leverage Index), the analysis uncovers trends in postseason performance and investigates whether star players tend to underperform under pressure.

---

### **Features**
- 📊 **Statistical Analysis**: Leverages FanGraphs data to calculate key metrics like SLG and OBP.
- 📈 **Visualization**: Includes plots to compare regular-season and postseason performance, plus OBP by leverage level.
- 🧠 **Bootstrapping**: Uses statistical bootstrapping to compute confidence intervals for the means of various metrics.

---

### **Data**
The dataset includes:
1. **Regular Season Data**: Performance metrics for star players during the regular season.
2. **Postseason Data**: Metrics for the same players during the postseason.

The data files are located in the `data/` directory:
- `data/Regular_Szn/`: Regular season data files.
- `data/Postseason/`: Postseason data files.

---

### **Use**
1. **Clone the repository**:
   ```bash
   git clone git@github.com:AlanG2004/MLB-Star-Batters-Article.git
   cd MLB-Star-Batters-Article
   ```

2. **Run the notebook**:
   Open `StarsArticle.ipynb` in Jupyter Notebook or Google Colab.  
   ```bash
   jupyter notebook StarsArticle.ipynb
   ```

3. **Analyze the results**:
   - View regular season vs. postseason performance comparisons.
   - Explore plots and statistical findings.

---

### **Key Findings**
- **Decline in Postseason Performance**:
  Star batters tend to show significant drops in SLG and OBP during the postseason.
- **Impact of High-Leverage Situations**:
  Postseason games feature more high-leverage situations, correlating with reduced OBP.

---
