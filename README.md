# Inventory Demand Forecasting and Warehouse Optimization

## Project Overview
This project focuses on improving warehouse efficiency through demand forecasting and optimization. It combines data engineering with predictive analytics to solve complex operational challenges in supply chain management.

### Key Features:
- **ETL Pipeline**: Built using PySpark and SQL to extract, transform, and load large-scale warehouse data.
- **Demand Forecasting Model**: Leveraged Spark MLlib to train a time series forecasting model with 90% accuracy.
- **Warehouse Optimization**: Applied clustering techniques to optimize warehouse layouts and reduce storage costs.
- **Visualization**: Created a Tableau dashboard for real-time demand monitoring and proactive inventory management.

## Dataset
The dataset used for this project contains fields such as `InvoiceNo`, `StockCode`, `Description`, `Quantity`, `InvoiceDate`, `UnitPrice`, `CustomerID`, and `Country`. 

**Download the dataset:** [Dataset Link](https://drive.google.com/file/d/1cWPnBXkR_kGk_t4JUIhjPl-O_p7amWay/view?usp=drive_link)

## Project Workflow
1. **Data Preprocessing**:
   - Handle missing values and incorrect data entries.
   - Parse and clean `InvoiceDate` for time-series modeling.
2. **ETL Pipeline**:
   - Built using PySpark to automate data extraction, transformation, and loading for millions of records.
3. **Model Development**:
   - Trained a demand forecasting model using Spark MLlib.
   - Fine-tuned hyperparameters such as learning rate and regularization for better performance.
4. **Warehouse Optimization**:
   - Clustered products based on demand patterns to improve storage efficiency.
5. **Visualization**:
   - Created an interactive Tableau dashboard to monitor demand trends and send low-stock alerts in real time.

## Tools and Technologies Used
- **Programming Languages**: Python (PySpark, Pandas)
- **Big Data Framework**: Apache Spark
- **Data Visualization**: Tableau
- **Version Control**: Git, GitHub

## How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   ```
2. Open the Jupyter Notebook or Google Colab file provided.
3. Download the dataset from the link above and place it in the project directory.
4. Follow the instructions in the notebook to execute the project step-by-step.

## Results
- Achieved a demand forecasting accuracy of 90%.
- Optimized warehouse layouts, reducing storage costs and retrieval times.
- Developed a Tableau dashboard for real-time inventory tracking.

## Future Work
- Enhance forecasting accuracy with advanced machine learning techniques.
- Integrate automated alerts for stock replenishment.
- Expand the model to support multi-warehouse setups.

## Author
**Anuj Sharma**  
For queries, reach out to [Anuj Sharma](mailto:Anuj.s@zomato.com).

---

Feel free to contribute to this project by raising issues or submitting pull requests.
