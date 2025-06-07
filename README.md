# PCA
Project Summary: Perceptual and Preference Mapping of Car Brands Using PCA
This project applies Principal Component Analysis (PCA) to car perception data to uncover underlying dimensions that describe how consumers perceive various car attributes and brands. The dataset contains 15 car models, each evaluated across 10 key features such as Price to dealer, Engine size, Cylinders, Horsepower, City and Highway MPG, Weight, Wheelbase, Length, and Width.

PCA was performed on the perception data to reduce dimensionality while retaining the most important variance in the dataset. The analysis extracted principal components that represent latent factors summarizing complex attribute interrelationships. Attribute loadings on the principal components quantify each feature’s contribution, and singular values indicate the amount of variance explained by each component.

The results were used to create a perceptual map:

Attribute factors show how each feature aligns with the principal components.

Brand scores represent each car model’s position along these components, normalized for easy interpretation.

These maps visually represent brand positioning relative to key attributes, revealing clusters and competitive landscapes that inform strategic marketing and product development decisions.

Additionally, preference mapping integrates consumer preference data by projecting respondent preferences onto the perceptual space. This approach links perception and preference, identifying which brand attributes drive consumer choices and highlighting areas for product improvement or differentiation.

Outputs, including attribute loadings, brand scores, and preference scores, were exported as CSV files for further visualization and analysis, such as in Tableau.

Overall, this project demonstrates how PCA-based perceptual and preference mapping can provide actionable insights into consumer attitudes and market structure, guiding refinement of survey design and targeted marketing strategies.

