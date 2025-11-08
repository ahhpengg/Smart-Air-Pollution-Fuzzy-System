# Fuzzy Logic-Based Air Quality Index (AQI) Evaluation

This project implements a fuzzy logic system to estimate the Air Quality Index (AQI) based on multiple pollutant inputs such as PM₂.₅, PM₁₀, and CO.  
It demonstrates how fuzzy inference can handle uncertainty in environmental data and provide interpretable AQI classifications.

- Calculates membership degrees for each pollutant input
- Displays fuzzy membership function plots with annotated input intersections
- Provides numerical AQI result and category label
- Generates a 3D surface visualization for AQI output

## 📈 Membership Function Visualizations
### AQI Membership Graph (Without Output)
Displays the defined linguistic categories (e.g., Good, Moderate, Unhealthy) for the AQI variable.
<img width="694" height="429" alt="image" src="https://github.com/user-attachments/assets/8c1f1736-5242-4c95-99cd-fd42aaead4ee" />

### PM₂.₅ Membership Graph
Shows how PM₂.₅ concentrations are fuzzified across linguistic terms (Low, Moderate, High).
<img width="719" height="460" alt="image" src="https://github.com/user-attachments/assets/b2ad27ef-abcd-4c77-b167-f6ddc6f05acd" />

### PM₁₀ Membership Graph
Depicts PM₁₀ fuzzy membership functions, representing its contribution to air quality evaluation.
<img width="691" height="457" alt="image" src="https://github.com/user-attachments/assets/6e2fd0db-3f3a-417d-9e03-59f7de74eccb" />

### NO₂ Membership Graph
Illustrates the membership curve for nitrogen dioxide (NO₂), used to model pollution intensity and health impact.
<img width="732" height="463" alt="image" src="https://github.com/user-attachments/assets/b829e6a2-e9c9-4252-a121-7ca82862bbcf" />

### CO Membership Graph
Displays the fuzzy sets for carbon monoxide (CO), showing smooth transitions between low and high levels.
<img width="680" height="455" alt="image" src="https://github.com/user-attachments/assets/1513bd16-6ad4-40c9-ad2e-413be09ca878" />

### O3 Membership Graph
Represents the ozone (O₃) fuzzy membership functions, reflecting its influence on overall AQI.
<img width="738" height="461" alt="image" src="https://github.com/user-attachments/assets/746f268b-4f09-4148-9fb4-57f4b770423b" />

### AQI Membership Graph (With Output Highlighted)
Shows the aggregated fuzzy output and defuzzified AQI result (shaded region and vertical line indicate the computed crisp value).
<img width="680" height="438" alt="image" src="https://github.com/user-attachments/assets/ccc44a15-5b35-4ead-bb13-d0016dead567" />

### 3D AQI Surface Plot
Visualizes how AQI changes with varying pollutant levels, demonstrating nonlinear interactions between key variables.
<img width="539" height="421" alt="image" src="https://github.com/user-attachments/assets/76b9d86a-4b7b-4abf-ae63-0c1611258513" />
