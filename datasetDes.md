### **Dataset Overview**
- **Rows / Samples:** 2,200 (each row is an observed soil/environment sample)
- **Columns / Features:** 8
  - **N**: Nitrogen content in soil (numeric)
  - **P**: Phosphorus content in soil (numeric)
  - **K**: Potassium content in soil (numeric)
  - **temperature**: In Celsius (numeric)
  - **humidity**: Relative humidity (%) (numeric)
  - **ph**: Soil pH value (numeric)
  - **rainfall**: Measured in mm (numeric)
  - **label**: The recommended crop for these conditions (category – e.g., rice, maize, apple, etc.)

### **Crops Included**
- 22 unique crop categories: rice, maize, chickpea, kidneybeans, pigeonpeas, mothbeans, mungbean, blackgram, lentil, pomegranate, banana, mango, grapes, watermelon, muskmelon, apple, orange, papaya, coconut, cotton, jute, coffee

### **Class Distribution**
- Every crop type appears **exactly 100 times**; data is perfectly balanced for classification.

### **Summary Statistics**
- **N** (Nitrogen): min=0, max=140, mean≈51
- **P** (Phosphorus): min=5, max=145, mean≈53
- **K** (Potassium): min=5, max=205, mean≈48
- **temperature**: 8.8°C to 43.7°C, mean≈25.6°C
- **humidity**: 14.3% to 99.9%, mean≈71.5%
- **ph**: 3.5 to 9.9, mean≈6.47
- **rainfall**: 20.2mm to 298.6mm, mean≈103.5mm

### **Sample Data (first 5 rows):**
| N  | P  | K  | temperature | humidity | ph    | rainfall   | label |
|----|----|----|-------------|----------|-------|------------|-------|
| 90 | 42 | 43 | 20.88       | 82.00    | 6.50  | 202.94     | rice  |
| 85 | 58 | 41 | 21.77       | 80.32    | 7.04  | 226.66     | rice  |
| 60 | 55 | 44 | 23.00       | 82.32    | 7.84  | 263.96     | rice  |
| 74 | 35 | 40 | 26.49       | 80.16    | 6.98  | 242.86     | rice  |
| 78 | 42 | 42 | 20.13       | 81.60    | 7.63  | 262.72     | rice  |


**Summary:**  
This dataset provides soil and climate measurements with a corresponding recommended crop. It is well-structured, fully numeric (except the label), and balanced—making it ideal for the classification workflows demonstrated in your notebook, including training, tuning, and user prediction functions.
