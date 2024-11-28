# Indonesian Food Prices Dataset

## **Dataset Overview**
This dataset contains daily prices of essential food commodities in Indonesia, collected from the [Pusat Informasi Harga Pangan Strategis Nasional](https://www.bi.go.id/hargapangan). The dataset has been preprocessed to ensure consistency and readiness for analysis. Below is a detailed explanation of the structure and content of the dataset.

---

## **Data Fields**

### **1. tanggal**
- **Format**: `dd-mm-yyyy`
- The date when the data was collected.

---

### **2. beras (Rice Prices)**  
- **Definition**: The average price of six categories of rice.
  - Beras Kualitas Bawah I (`beras_kb1`)
  - Beras Kualitas Bawah II (`beras_kb2`)
  - Beras Kualitas Medium I (`beras_km1`)
  - Beras Kualitas Medium II (`beras_km2`)
  - Beras Kualitas Super I (`beras_ks1`)
  - Beras Kualitas Super II (`beras_ks2`)

#### Subfields:
- **beras_kb1**: Price of Beras Kualitas Bawah I.
- **beras_kb2**: Price of Beras Kualitas Bawah II.
- **beras_km1**: Price of Beras Kualitas Medium I.
- **beras_km2**: Price of Beras Kualitas Medium II.
- **beras_ks1**: Price of Beras Kualitas Super I.
- **beras_ks2**: Price of Beras Kualitas Super II.

---

### **3. daging_ayam (Chicken Prices)**  
- **Definition**: The average price of fresh chicken (`daging_ayam_rs`).

#### Subfields:
- **daging_ayam_rs**: Price of fresh chicken.

---

### **4. daging_sapi (Beef Prices)**  
- **Definition**: The average price of two beef quality levels.
  - Daging Sapi Kualitas 1 (`daging_sapi_k1`)
  - Daging Sapi Kualitas 2 (`daging_sapi_k2`)

#### Subfields:
- **daging_sapi_k1**: Price of Beef Quality 1.
- **daging_sapi_k2**: Price of Beef Quality 2.

---

### **5. telur_ayam (Egg Prices)**  
- **Definition**: The average price of fresh chicken eggs (`telur_ayam_rs`).

#### Subfields:
- **telur_ayam_rs**: Price of fresh chicken eggs.

---

### **6. bawang_merah (Shallot Prices)**  
- **Definition**: The average price of medium-sized shallots (`bawang_merah_sedang`).

#### Subfields:
- **bawang_merah_sedang**: Price of medium-sized shallots.

---

### **7. bawang_putih (Garlic Prices)**  
- **Definition**: The average price of medium-sized garlic (`bawang_putih_sedang`).

#### Subfields:
- **bawang_putih_sedang**: Price of medium-sized garlic.

---

### **8. cabai_merah (Red Chili Prices)**  
- **Definition**: The average price of:
  - Large Red Chili (`cabai_merah_besar`)
  - Curly Red Chili (`cabai_merah_keriting`)

#### Subfields:
- **cabai_merah_besar**: Price of large red chili.
- **cabai_merah_keriting**: Price of curly red chili.

---

### **9. cabai_rawit (Bird's Eye Chili Prices)**  
- **Definition**: The average price of:
  - Green Bird's Eye Chili (`cabai_rawit_hijau`)
  - Red Bird's Eye Chili (`cabai_rawit_merah`)

#### Subfields:
- **cabai_rawit_hijau**: Price of green bird's eye chili.
- **cabai_rawit_merah**: Price of red bird's eye chili.

---

### **10. minyak_goreng (Cooking Oil Prices)**  
- **Definition**: The average price of:
  - Bulk Cooking Oil (`minyak_goreng_curah`)
  - Branded Cooking Oil 1 (`minyak_goreng_merk1`)
  - Branded Cooking Oil 2 (`minyak_goreng_merk2`)

#### Subfields:
- **minyak_goreng_curah**: Price of bulk cooking oil.
- **minyak_goreng_merk1**: Price of branded cooking oil (Brand 1).
- **minyak_goreng_merk2**: Price of branded cooking oil (Brand 2).

---

### **11. gula_pasir (Sugar Prices)**  
- **Definition**: The average price of:
  - Premium Sugar (`gula_pasir_premium`)
  - Local Sugar (`gula_pasir_lokal`)

#### Subfields:
- **gula_pasir_premium**: Price of premium sugar.
- **gula_pasir_lokal**: Price of local sugar.

---

## **Preprocessing Steps**
1. **Data Cleaning**:
   - Removed unnecessary columns like "No" to retain only relevant data.
2. **Data Transformation**:
   - Transposed the data for easier column manipulation.
3. **Column Standardization**:
   - Unified column names across all files for consistent analysis.
4. **File Merging**:
   - Combined data from multiple Excel files into a single dataset.

---

## **Usage**
The dataset is highly versatile and can be applied to various fields, including but not limited to:

1. **Analyzing Food Price Trends**  
   - Track daily price movements of essential food commodities in Indonesia.  
   - Identify patterns and anomalies over time.  

2. **Economic Research and Policy-Making**  
   - Assess the impact of food price fluctuations on inflation.  
   - Support the development of policies for food security and affordability.

3. **Forecasting Food Prices**  
   - Build predictive models to forecast future prices of commodities.  
   - Utilize time-series analysis and machine learning techniques for demand and supply planning.  
   - Predict the impact of seasonal trends, economic conditions, or external shocks on food prices.

---

## **Acknowledgment**
- **Source**: [Pusat Informasi Harga Pangan Strategis Nasional](https://www.bi.go.id/hargapangan)  
  - Please credit the original data source for any published work.

- **Reference**: [Bandung Food Prices Dataset](https://github.com/stefkim/bandung_food_prices_dataset)  
  - The preprocessing methodology and inspiration for this dataset were partially guided by this repository. Special thanks to the contributor for their efforts in creating open datasets for food price analysis.  
