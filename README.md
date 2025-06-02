
# 🏠 House Rent Prediction Data Analysis Project 🇮🇳

## 📖 Overview

This project explores and visualizes a comprehensive dataset of houses, apartments, and flats available for rent across India. The dataset features diverse parameters, from size and price to furnishing status and tenant preferences, reflecting India’s vibrant housing market.

The analysis leverages **Python**, **Pandas**, **Matplotlib**, and **Seaborn** to uncover patterns in rent prices, size distributions, city-wise availability, and more.

---

## 📂 Dataset Overview

The dataset contains information on **4,746** listings, including:

* **BHK** – Number of Bedrooms, Hall, Kitchen
* **Rent** – Monthly Rent (INR)
* **Size** – Area in Square Feet
* **Floor** – Which Floor & Total Floors
* **Area Type** – Measurement Standard
* **Area Locality** – Neighborhood/Locality
* **City** – City of the Property
* **Furnishing Status** – Furnished / Semi-Furnished / Unfurnished
* **Tenant Preferred** – Bachelors / Family / Both
* **Bathroom** – Number of Bathrooms
* **Point of Contact** – Contact Person or Agent

---

## 🛠️ Technologies Used

* **Python 3**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Seaborn**
* **WordCloud**

---

## 🏗️ Key Steps and Insights

* 📈 **Data Exploration**

  * Checked dataset shape, column info, null values, and duplicates
  * Calculated statistical summaries (mean, median, max, min rents)

* 🏙️ **Visualizations**

  * **Bar Plots** for city-wise house counts, furnishing status, and tenant preferences
  * **Pie Chart** to visualize city-wise rent availability
  * **Scatter & Bubble Plots** to explore rent vs. size relationships
  * **Histogram** for house size distributions
  * **Heatmap** to show BHK vs. area type relationships
  * **WordCloud** to showcase prominent localities

* 🏠 **Highlights**

  * Mean House Rent: ₹34,993
  * Highest Rent: ₹35,00,000; Lowest Rent: ₹1,200
  * Rich diversity across Indian cities with varying furnishing statuses and tenant preferences

---

## 📸 Sample Visualizations

| ![City-wise House Count](path/to/city_count_plot.png)    | ![Furnishing Status](path/to/furnishing_status_plot.png) |
| -------------------------------------------------------- | -------------------------------------------------------- |
| ![Tenant Preference](path/to/tenant_preference_plot.png) | ![Rent vs. Size Scatter](path/to/rent_size_scatter.png)  |

---

## 🚀 How to Run

1. Clone this repository:

   ```bash
   git clone https://github.com/yourusername/housing-rent-analysis.git
   cd housing-rent-analysis
   ```

2. Install required libraries:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the Jupyter Notebook or Python script:

   ```bash
   jupyter notebook House_Rent_Analysis.ipynb
   ```

---

## 💡 Future Enhancements

* Build a **machine learning model** to predict house rents
* Add **interactive dashboards** with Plotly or Power BI
* Extend analysis to include **time series trends**

---

## 👏 Acknowledgements

* **Dataset Source**: [Kaggle - House Rent Prediction Dataset](https://www.kaggle.com/datasets)
* **Human Rights Measurement Initiative**: Insights on India’s housing sector
* Visualizations inspired by **Matplotlib** and **Seaborn** documentation

---

## 🤝 Contributing

Pull requests are welcome! For significant changes, please open an issue first to discuss your ideas.

---

## 📜 License

This project is licensed under the MIT License.

Let me know! 🚀
