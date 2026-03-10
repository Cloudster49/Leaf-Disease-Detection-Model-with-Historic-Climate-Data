# Leaf-Disease-Detection-Model-with-Historic-Climate-Data
This project's main focus is detecting and predicting plant diseases by crossing historic climate data with computer vision. The model uses a convoluted nueral network to analyze images of plant leaves and identify visual patterns associated with plant disease.
The histroic climate data incorperates distinct climate paramaters such geographic location and atmospheric conditions, which work in unison with the model to provide contect for disease prediction.
The end goal with this model is to help pioneer a solution that helps crop scouters identify plant diseases faster, and reduce time spent manually inspecting the crops to help minimize potential crop loss. 
----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
# Model Inputs

The model utilizes two primary data souces:

# Leaf Image Data
- Images of plant leaves
- Used to detect visual symptoms of disease

# Historic Climate Data
- Date and time
- Latitude and longitude
- Temperature measurements (Kelvin mean and atmospheric levels)

# Model Process
- A CNN processes leaf images to extract visual features associated with plant health and disease.
- Environmental data is incorporated to provide context about conditions that influence disease development.
- The model outputs a predicted disease classification for the plant.

# Expected Impact
- Reduce manual crop scouting time
- Improve early disease detection
- Help farmers prevent crop loss through faster intervention
