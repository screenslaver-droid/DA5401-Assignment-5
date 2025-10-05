# DA5401 Assignment 5: Visualizing Data Veracity Challenges in Multi-Label Classification

This project explores manifold learning techniques for visualizing high-dimensional multi-label classification data, specifically focusing on the Yeast dataset. The notebook demonstrates various dimensionality reduction techniques including t-SNE and Isomap to understand data structure and class relationships.

## Project Overview

This assignment focuses on understanding data veracity challenges in multi-label classification through advanced visualization techniques. The project processes the Yeast dataset containing 2,417 data points with 103 features and 14 binary class labels, applying manifold learning algorithms to reveal underlying data structures and patterns.

## Objectives

- **Data Preprocessing**: Load and process ARFF format data, handle multi-label classification structure
- **Manifold Learning**: Apply t-SNE and Isomap for dimensionality reduction and visualization
- **Data Veracity Analysis**: Examine how different visualization techniques reveal data quality issues
- **Multi-Label Insights**: Understand relationships between features and multiple class labels
- **Comparative Analysis**: Compare different manifold learning approaches for multi-label data

## Dataset Information

- **Name**: Yeast Dataset
- **Format**: ARFF (Attribute-Relation File Format)
- **Instances**: 2,417 data points
- **Features**: 103 continuous attributes (Att1-Att103)
- **Labels**: 14 binary class labels (Class1-Class14)
- **Type**: Multi-label classification dataset
- **Domain**: Biological/Protein function prediction

##  Key Methods & Techniques

### Data Processing
- ARFF file loading and parsing
- Byte string decoding for categorical labels
- Feature-label separation (X: features, Y: labels)
- Data standardization using StandardScaler

### Manifold Learning Algorithms
- **t-SNE (t-Distributed Stochastic Neighbor Embedding)**
  - Non-linear dimensionality reduction
  - Preserves local neighborhood structures
  - Effective for visualization of complex data patterns

- **Isomap (Isometric Mapping)**
  - Non-linear dimensionality reduction
  - Preserves geodesic distances
  - Reveals intrinsic geometry of data manifolds

### Visualization Techniques
- 2D scatter plots for reduced dimensionality data
- Color-coded visualizations for multi-label analysis
- Comparative plots between different manifold methods


## Key Results & Insights

- **Data Structure**: Successfully processed 2,417 instances with 103 features
- **Multi-Label Distribution**: Analysis of class co-occurrence patterns
- **Manifold Visualization**: Revealed clustering patterns and outliers
- **Algorithm Comparison**: Performance differences between t-SNE and Isomap
- **Data Quality**: Identified potential data veracity issues through visualization

## Visualizations Generated

1. **Feature Distribution Analysis**: Statistical summary of all 103 attributes
2. **t-SNE 2D Embedding**: Non-linear projection preserving local structures
3. **Isomap 2D Embedding**: Geodesic distance-based dimensionality reduction
4. **Multi-Label Analysis**: Class co-occurrence and relationship patterns
5. **Comparative Plots**: Side-by-side algorithm performance visualization

## Academic Context

**Course**: DA5401 - Data Analytics  
**Institution**: IIT Madras  
**Semester**: 2025  
**Assignment**: A5 - Manifold Learning and Visualization  

##  Author

**Siddharth Nair**  
CE22B106
IIT Madras

## References

- Van der Maaten, L., & Hinton, G. (2008). Visualizing data using t-SNE
- Tenenbaum, J. B., et al. (2000). A global geometric framework for nonlinear dimensionality reduction
- Scikit-learn: Machine Learning in Python, Pedregosa et al., JMLR 12, pp. 2825-2830, 2011

## License

This project is developed for academic purposes as part of coursework at IIT Madras. Please cite appropriately if using for research or educational purposes.

---

**Note**: Update file paths and personal information as needed before using this README in your repository.



