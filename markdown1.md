# 📑 MQ135 Gas Sensor – Datasheet Report  

---
![array](https://tse4.mm.bing.net/th/id/OIP.FGJVLtXlIayY1ejv_UjEkwHaD4?pid=Api&P=0&h=180)
## 1. Overview & Applications  
- **Sensor Type**: Semiconductor gas sensor (SnO₂)  
- **Purpose**: Detects gases and pollutants in the air  
- **Target Gases**: Ammonia (NH₃), Nitrogen oxides (NOₓ), Alcohol, Benzene, Smoke, CO₂, Sulfides  
- **Applications**:  
  - Air quality monitoring  
  - Gas leakage detection systems  
  - Industrial and domestic safety systems  
  - Portable air pollution detectors  
  - HVAC and building ventilation systems  

---

## 2. Features  
- Wide detection range  
- High sensitivity and fast response  
- Long life and low cost  
- Simple drive circuit  
- Dual output: Analog (gas concentration), Digital (threshold alarm via comparator)  

---

## 3. Pin Configuration (Typical Module)  

| Pin | Name  | Function |
|-----|-------|----------|
| 1   | VCC   | Supply voltage (5 V) |
| 2   | GND   | Ground |
| 3   | AOUT  | Analog output (proportional to gas concentration) |
| 4   | DOUT  | Digital output (logic HIGH/LOW based on threshold) |

**Note**: The raw sensor itself has **6 pins** (2 for heater, 4 for sensing electrodes).  

---

## 4. Electrical Specifications  

| Parameter                  | Value |
|----------------------------|-------|
| Circuit Voltage (Vc)       | 5 V ± 0.1 V |
| Heater Voltage (Vh)        | 5 V ± 0.1 V |
| Heater Resistance (Rh)     | 31–33 Ω (at room temperature) |
| Heater Power Consumption   | ≤ 800 mW |
| Load Resistance (RL)       | 10 kΩ – 47 kΩ (20 kΩ typical) |
| Sensor Resistance (Rs)     | 30 kΩ – 200 kΩ (in 100 ppm NH₃) |
| Operating Temperature      | –10 °C to +45 °C |
| Storage Temperature        | –20 °C to +70 °C |
| Humidity Range             | ≤ 95% RH |

---

## 5. Sensitivity & Detection Range  
- **NH₃**: 10 – 300 ppm  
- **Benzene**: 10 – 1000 ppm  
- **Alcohol**: 10 – 300 ppm  
- **Smoke & CO₂**: Detectable but not specific calibration available  
- **Preheat Time**: > 24 hours recommended for stable readings  
 
![array](https://www.researchgate.net/profile/Nariman-Farsad/publication/270821353/figure/fig1/AS:295014681858048@1447348389069/The-sensor-sensitivity-plot-from-the-datasheet-21.png)

**Working Principle**:  
- The sensor’s conductivity increases with the concentration of target gases.  
- Rs (sensor resistance) is measured in clean air to obtain R₀.  
- Concentration (ppm) is calculated using Rs/R₀ ratio and sensitivity curves.  

---

## 6. Usage Notes  
- Preheat sensor > 24 hrs for best accuracy.  
- Requires calibration in clean air for reference resistance (R₀).  
- Output is affected by temperature and humidity → compensation may be needed.  
- Place in a ventilated area for air quality monitoring.  

---

## 7. Dimensions (Sensor Body)  
- Diameter: ~20 mm  
- Height: ~22 mm  
- 6-pin metal-can package  

![array](https://components101.com/sites/default/files/inline-images/MQ135-Dimensions_0.png)

---

## ✅ Summary  
The **MQ135 Gas Sensor** is a low-cost, durable, and widely used semiconductor sensor designed for **air quality detection**. It detects multiple harmful gases including **NH₃, CO₂, benzene, alcohol, and smoke**, with both **analog concentration output** and **digital alarm output**. Requires calibration and preheating for accurate readings.


