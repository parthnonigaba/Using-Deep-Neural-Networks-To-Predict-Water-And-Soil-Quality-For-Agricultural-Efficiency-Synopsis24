# Using-Deep-Neural-Networks-To-Predict-Water-And-Soil-Quality-For-Agricultural-Efficiency-Synopsis24
Introduction:
Many parts of the world are suffering from acute shortage of fresh water supply especially India which has 18% of the world’s population and only 4% of the freshwater resources. Kanna Nova in her research paper “ An analysis of system components and interdependencies for water conservation “ proposes that AI can help predict water demand more accurately and hence reduce waste. I built on her work further to use a set of machine learning models to accomplish two things farmers can greatly benefit from:
Using the temperature readings at 30-150cm at 30 cm increments I can classify water moisture levels in different regions of a farm and adjust water allocation 
By using pH level, electrical conductivity, and chemical content( Na, K, Mg)  I can grade water quality and determine the best crop and soil type for the water to be used based on the water available at the farm.

Goal:
There are two goals for my project. Use a feedforward neural network:
To reduce water use based on moisture levels across the farm 
To classify & grade water quality for crop selection and soil management


Conclusion:
Neural networks based machine learning can be applied to reduce water use & improve crop selection with reasonable accuracy and help some of the most water stressed parts of India and rest of the world.


Acknowledgements:
Kanna Nova - “AI-Enabled Water Management Systems: AnAnalysis of System Components
 and Interdependencies for Water Conservation.” View of AI-Enabled Water Management Systems: An Analysis of System Components and Interdependencies for Water Conservation,
Mr. Mathias Lema
Rushil Kapadia
MachineLearningMastery.com

Literature Research:
“Addressing India’s Agri-Water Crisis.” Hindustan Times
The Water Diplomat. “Water Security: Issues and Challenges for India.” The Water Diplomat, 22 Feb. 2023
David Blakeslee Assistant Professor of Economics, et al. “Impacts of Water Loss on Low-Income Farmers in India.” 
“Toxic Water, Toxic Crops: India’s Public Health Time Bomb.” New Security Beat
“How Is India Addressing Its Water Needs?” World Bank
View of Machine Learning Approaches to Enhance Water Conservation in Agriculture, publications.dlpress.org/index.php/JSTIP/article/view/50/47

Results:
1. For the water quality feed forward model I had a net accuracy of 82.38%, a loss of 0.31. The model training time is 5 minutes. Training time is the amount of time it takes for the model to be trained for new data.

2. For the soil moisture model I had a loss of 2E-3 and a training time of 29 minutes.
