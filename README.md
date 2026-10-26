**Experimental Results and Validation**
The digital twin was evaluated by comparing the experimentally observed pendulum motion with the model predictions.
Key Results

**Parameter/Result**
Number of samples 6,000
Pendulum length 0.236 m
Gravitational acceleration 9.799 m/s²
Estimated damping rate (β) 0.00886 s⁻¹
Estimated initial amplitude 0.7455 rad
Experimental mean period 1.0178 s
Simulated mean period 0.9980 s
Period error  −1.945%
Coefficient of determination (R²)  0.9982

**Interpretation**

**Parameter estimation:** The damping rate and initial amplitude were estimated to characterize the pendulum's oscillatory behavior.

**Period validation:** The simulated oscillation period was approximately 1.945% lower than the experimental mean period, indicating good agreement in the timing of oscillations.

**Model fit:** An R² value of 0.9982 indicates an excellent fit for the data used in that particular parameter-fitting analysis. This does not, by itself, guarantee equally accurate predictions across the entire time series.

**Engineering significance:** The results demonstrate how experimental measurements and a physics-based model can be combined to construct and validate a digital representation of a dynamic system.

**Conclusion**

The pendulum example demonstrates a practical workflow for digital twin development involving experimental data analysis, physics-based modeling, parameter estimation, and validation. The methodology can be extended to industrial equipment by incorporating real-time sensor measurements, equipment-specific governing equations, and condition-monitoring algorithms.

Note: The reported R², damping rate, and period results come from a particular analysis run. RMSE and MAE values reported in other runs differed, so they have been omitted here rather than combining potentially inconsistent results.
