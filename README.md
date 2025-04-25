# 🌿 HydroWizard: Intelligent Fuzzy Logic Irrigation

**HydroWizard** is an intelligent decision-making system based on fuzzy logic, designed to optimize irrigation processes in agriculture. It dynamically recommends the appropriate irrigation level using environmental inputs such as soil moisture and weather conditions.

---

## 🧠 About the Project

In traditional irrigation systems, decisions about when and how much to irrigate are often manual or based on preset schedules. **HydroWizard** automates this by using **fuzzy logic** to adapt decisions based on real-world environmental factors.

### Goals:
- Reduce water consumption
- Increase agricultural efficiency
- Prevent water stress in plants

---

## ⚙️ Technologies Used

- Python
- [scikit-fuzzy](https://github.com/scikit-fuzzy/scikit-fuzzy): for fuzzy logic control systems
- NumPy: for numerical operations
- Matplotlib: for visualizing membership functions and results

### Installation

```bash
pip install scikit-fuzzy matplotlib numpy
```

---

## 🧩 Fuzzy System Design

### Inputs (Antecedents):

#### Soil Moisture:
- Dry  
- Medium  
- Wet

#### Weather Condition:
- Sunny  
- Cloudy  
- Rainy

### Output (Consequent):

#### Irrigation Amount:
- None  
- Low  
- Medium  
- High

---

## 📊 Features

- Fuzzy membership functions using **triangular (trimf)** shapes  
- System modeling with `skfuzzy.control`  
- Defined fuzzy rules for decision-making  
- Simulation and output calculation based on user inputs  
- Graphical visualization of fuzzy sets for all variables  

---

## 🧪 How to Run

1. Open the file `HydroWizard_Intelligent_Fuzzy_Logic_Irrigation.ipynb` in **Jupyter Notebook** or **Google Colab**.  
2. Run the cells sequentially.  
3. The irrigation recommendation will be calculated and displayed both **numerically** and **graphically**.  

---

## 🖼️ Visual Examples

- Membership function plots  
- Final irrigation output  
- Fuzzy control system diagrams

---

## 📁 Project Structure
HydroWizard/<br>
├── HydroWizard_Intelligent_Fuzzy_Logic_Irrigation.ipynb<br>
└── README.md
 
---

## 🔧 Future Improvements

- Add more inputs (e.g., temperature, plant type, soil type)
- Integration with real-time sensors and IoT platforms
- Build a user-friendly GUI for farmers
- Field-testing in real agricultural environments

---

## 🧑‍💻 Developer

- **Developer/Student Name**: *Sayyed Hossein Hosseini DolatAbadi & Mohammad Amin Nasiri*
- **Email / GitHub Profile**: *S.Hossein.Hosseini1381@gmail.com*

---

## 📬 Contact

Feel free to reach out with questions, ideas, or suggestions to enhance this project further.

---

## 🔖 License

This project is licensed under the **MIT License** — feel free to use, modify, and distribute it.
