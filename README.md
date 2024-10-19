## BREAST CANCER CLASSIFICATION
- Breast cancer is the most common cancer among women worldwide accounting for 25% of all cancer cases and infected 2.1 million people in 2015.
- Early diagnosis significantly increases the chance of survival.
- The key challenge in cancer detection is how to classify tumours into malignant or benign machine learning techniques can dramatically improve the accuracy of diagnosis.
- Research indicated that most experienced physicians can diagnose cancer with 79% accuracy.

  FIRST STAGE- any process which is simply extracting some of the cells out of the tumour.
  
When we say benign that means the tumour is kind of not spreading across the body so the patient is safe somehow if it's malignant that means it's cancerous. That means we need to intervene and actually stop cancer growth.

---

What we do here in the machine learning aspect
- We execute all these images and
- We wanted to specify if that cancer out of these images is malignant or benign

# Support vector machine Classifier
Near the max Margin Hyperplane, we don't know whether this cancer is malignant or benign.

That's why the support vector machine classifier is very unique in this sense. It's simply uses the points or the support vectors that are on the boundary to draw the boundary out to classify the classes.

Support vector machines are really powerful techniques. Why? Because it's kind of an extreme algorithm. It just focus on the support of the suppor vectors or the points on the boundary and seperate them somehow

---
---

## BREAST CANCER DETECTION

# Data Set Information
Features are computed from a digitized image of a fine needle aspirate (FNA) of a breast mass. They describe characteristics of the cell nuclei present in the image. 

Separating plane described above was obtained using Multisurface Method-Tree (MSM-T) [K. P. Bennett, "Decision Tree Construction Via Linear Programming." Proceedings of the 4th Midwest Artificial Intelligence and Cognitive Science Society, pp. 97-101, 1992], a classification method which uses linear programming to construct a decision tree. Relevant features were selected using an exhaustive search in the space of 1-4 features and 1-3 separating planes.

# Attribute Information
- ID Number
- Dianosis ( M = Malignant, B = Benign)

Ten real-valued features are computed for each cell nucleus:
- radius (mean of distances from center to points on the perimeter)
- texture (standard deviation of gray-scale values)
- perimeter
- area
- smoothness (local variation in radius lengths)
- compactness (perimeter^2 / area - 1.0)
- concavity (severity of concave portions of the contour)
- concave points (number of concave portions of the contour)
- symmetry
- fractal dimension ("coastline approximation" - 1)
