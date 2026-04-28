# Weather-Aware Highway Routing: ML vs Deep Learning Comparison


> Comparative analysis of machine learning architectures for weather-responsive 
> traffic prediction on Indian national highways during monsoon conditions.

##  Key Findings

- **XGBoost outperformed graph neural networks by 115%** (2.19s vs 4.71s MAE)
- **16% time savings** demonstrated in flood scenarios  
- **Statistical significance**: p < 0.001 for all comparisons
- **First rigorous ML vs GNN study** for Indian monsoon context

##  Results Summary

| Model | MAE (seconds) | R² | Performance |
|-------|--------------|-----|-------------|
| **XGBoost**  | **2.19** | **0.971** | **Best** |
| Random Forest | 2.25 | 0.969 | 2nd |
| GCN | 3.21 | 0.940 | 3rd |
| GAT | 4.71 | 0.866 | Worst |

## Data Sources

- Rain data from ERA 5
- Slope data from NASA SRTM
- Wind data from Open-Meteo
- Map from OpenStreetMap (OSM)
- Visibility calculated through Kochmeider's law

