# 💻 Laptop Price Analysis

This project is an exploratory data analysis (EDA) of laptop specifications and their corresponding prices. The dataset includes various brands and features such as screen resolution, RAM, processor type, storage, GPU, and operating systems.

## 📁 Dataset

The dataset (`laptop.csv`) contains the following columns:

- `Company`: Laptop brand
- `TypeName`: Type (e.g., Ultrabook, Notebook)
- `Inches`: Screen size
- `ScreenResolution`: Resolution and panel type
- `Cpu`: CPU specifications
- `Ram`: Memory size
- `Memory`: Storage type and size
- `Gpu`: Graphics card
- `OpSys`: Operating system
- `Weight`: Laptop weight
- `Price`: Laptop price (target variable)

## 🧪 Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

## 🔍 Current Status

- ✅ Loaded and displayed the dataset
- ❌ No cleaning or feature engineering yet
- ❌ No visualization or statistical analysis
- ❌ No machine learning/modeling implemented

## 🚀 Next Steps

1. **Data Cleaning**: Remove unnecessary columns like `Unnamed: 0` and convert data types.
2. **EDA**: Visualize the distribution of features (e.g., prices across brands, effect of RAM/storage).
3. **Feature Engineering**: Extract GHz from CPU, unify RAM/storage sizes, etc.
4. **Model Building** *(optional)*: Predict laptop prices using regression models.

## 🧠 Learnings

This project aims to:
- Understand what factors affect laptop pricing.
- Practice data analysis skills using Python libraries.
- Optionally apply regression models to predict prices.

## 📎 How to Run

```bash
# Clone the repository
git clone https://github.com/yourusername/your-repo-name.git
cd your-repo-name

# Run the notebook
Open proj.py (Jupyter Notebook or Colab)
