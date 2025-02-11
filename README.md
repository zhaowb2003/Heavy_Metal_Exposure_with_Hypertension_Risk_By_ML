# Heavy_Metal_Exposure_with_Hypertension_Risk_By_ML
The source Code of paper: Comprehensive Assessment of Heavy Metal Exposure and Its Association with Hypertension Risk: Insights from Contaminated Areas(This paper has not been made public yet)

## Getting Started

To get started, follow the instructions below:

1. download the R 4.2.1 and download the following packages:

  - parsnip
	- tidyverse
	- tidymodels
	- vip
	- parsnip
	- dplyr
	- ggisoband
	- DALEXtra
	- kernelshap
	- shapviz
	- kknn
	- LiblineaR
	- xgboost
	- ranger
	- dbarts
	- discrim
	- earth
	- patchwork
	- ggpubr
	- doParallel

2. Clone the repository (By the way, please submit an application to the corresponding author of this article in order to obtain the raw data required for analysis. )
3. Open the RStudio and create the project file
4. Run the code in the "./main_ML_model_training_and_prediction.Rmd"
5. Run the code in the "./ROC_PDP2D_SHAP_draw.Rmd"

success!

## Other instructions



Due to ethical review and other factors, raw data is precious and subject to privacy protection. Therefore, only the source code is provided here. But you can still request the original data through the corresponding author of this article. We will thank you for your letter.

In addition, some of the source code here is reused and not written as a function, so the code provided for drawing or calculation can only reproduce one of several repeated small images in a set of large images. Please make free modifications to the code as needed. Or provide suggestions in the issue column. my thank!

By the way, it can be foreseen that some people who read a part of my code think I wrote very foolishly. I admit this without hesitation, but there are still some defenses that can be argue. For example, using kernelshap to calculate the part of the shap. This is because some of the code was written on a computer that was run down, tortured by deep learning, and had Windows 11 Insider Preview installed, so I had to save the program in segments to prevent the blue screen:( from destroying everything.

