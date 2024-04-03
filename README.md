<h1 align='center'>Steel Plate Defect Prediction</h1>
<h3 align='center'>Orestas Dulinskas</h3>
<h4 align='center'>March 2024</h4>

## Background

The Steel Plates Faults dataset project stems from the need to enhance quality control measures in steel manufacturing processes. With the continuous demand for high-quality steel products across various industries, it becomes imperative to identify and rectify faults in steel plates efficiently. By leveraging machine learning and data science techniques, this project aims to develop predictive models capable of accurately classifying and detecting various types of faults present in steel plates. By doing so, manufacturers can streamline their quality assurance processes, reduce downtime, minimize production costs, and ultimately deliver superior-quality steel products to their customers. This project not only addresses immediate operational challenges but also lays the foundation for implementing proactive fault detection strategies to improve overall productivity and competitiveness in the steel industry.

## Objective

The primary objective of this project is to develop robust predictive models capable of accurately predicting the presence and type of faults in steel plates. By utilizing machine learning algorithms, the project aims to predict the occurrence of various types of faults, including Pastry, Z_Scratch, K_Scatch, Stains, Dirtiness, Bumps, and Other_Faults, based on the features provided in the dataset. These predictive models will enable steel manufacturers to automate and enhance their quality control processes, allowing for timely identification and rectification of faults in steel plates during the manufacturing process.

## Data

The Steel Plates Faults dataset comprises various features related to steel plates and different types of faults associated with them. The dataset includes the following features:

* **id**: Unique identifier for each observation.
* **X_Minimum**: Minimum x-coordinate of the defect.
* **X_Maximum**: Maximum x-coordinate of the defect.
* **Y_Minimum**: Minimum y-coordinate of the defect.
* **Y_Maximum**: Maximum y-coordinate of the defect.
* **Pixels_Areas**: Area of the defect in pixels.
* **X_Perimeter**: Perimeter of the defect in the x-direction.
* **Y_Perimeter**: Perimeter of the defect in the y-direction.
* **Sum_of_Luminosity**: Sum of luminosity values within the defect area.
* **Minimum_of_Luminosity**: Minimum luminosity value within the defect area.
* **Maximum_of_Luminosity**: Maximum luminosity value within the defect area.
* **Length_of_Conveyer**: Length of the conveyer belt during manufacturing.
* **TypeOfSteel_A300**: Indicator variable for type of steel (A300).
* **TypeOfSteel_A400**: Indicator variable for type of steel (A400).
* **Steel_Plate_Thickness**: Thickness of the steel plate.
* **Edges_Index**: Ratio of perimeter to the length of the defect.
* **Empty_Index**: Ratio of empty pixels to the total number of pixels in the defect.
* **Square_Index**: Ratio of area to the square of the perimeter of the defect.
* **Outside_X_Index**: Ratio of pixels outside the defect in the x-direction to the total number of pixels in the defect.
* **Edges_X_Index**: Ratio of horizontal edges to the total number of edges in the defect.
* **Edges_Y_Index**: Ratio of vertical edges to the total number of edges in the defect.
* **Outside_Global_Index**: Ratio of pixels outside the defect to the total number of pixels in the image.
* **LogOfAreas**: Logarithm of the defect area.
* **Log_X_Index**: Logarithm of the maximum length of the defect in the x-direction.
* **Log_Y_Index**: Logarithm of the maximum length of the defect in the y-direction.
* **Orientation_Index**: Index representing the orientation of the defect.
* **Luminosity_Index**: Index representing the luminosity of the defect.
* **SigmoidOfAreas**: Sigmoid function applied to the defect area.
* **Pastry**: Binary indicator variable for the presence of the 'Pastry' fault.
* **Z_Scratch**: Binary indicator variable for the presence of the 'Z_Scratch' fault.
* **K_Scatch**: Binary indicator variable for the presence of the 'K_Scatch' fault.
* **Stains**: Binary indicator variable for the presence of the 'Stains' fault.
* **Dirtiness**: Binary indicator variable for the presence of the 'Dirtiness' fault.
* **Bumps**: Binary indicator variable for the presence of the 'Bumps' fault.
* **Other_Faults**: Binary indicator variable for the presence of other types of faults not specified above.

These features provide comprehensive information about the characteristics of steel plates and the types of faults they may exhibit, facilitating the development of predictive models for fault detection and classification.
