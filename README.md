# 🥊 UFC Fight Predictor 🥊

# 🎯 Project Essence:
Step into the octagon with data! This machine learning model predicts UFC fight outcomes by analyzing fighter statistics and combat metrics. Using Logistic Regression, the predictor evaluates two fighters head-to-head and forecasts the victor with confidence scores.

## Requirements
pip install pandas numpy matplotlib scikit-learn

Not to worry if you are unable to install these libraries, check out the live demo here: https://www.josh-coyle.com/ufc-predictor 


## 📊 The Data:

Fighter profiles packed with combat intelligence:
- **Win/Loss Records**: Historical performance metrics
- **Striking Stats**: Accuracy, defense, and strikes landed per minute
- **Grappling Prowess**: Takedown accuracy and submission attempts
- **Physical Attributes**: Age and experience factors

## 🚀 How It Works:

1. **Feature Engineering**: Combines both fighters' stats with `_A` and `_B` suffixes
2. **Model Training**: Logistic Regression learns patterns from historical matchups
3. **Head-to-Head Comparison**: Visual stat breakdown between fighters
4. **Prediction**: Outputs winner with confidence percentage

## 🥋 Usage:

1. Run the notebook
2. Enter Fighter A's name when prompted
3. Enter Fighter B's name
4. View the stat comparison chart
5. Get your prediction with confidence score!

**Example:**

Fighter A: Conor McGregor
Fighter B: Khabib Nurmagomedov
