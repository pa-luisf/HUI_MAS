Urban walkability is a critical determinant of health, safety, sustainability, and city life in general, yet most existing indices remain limited to amenity proximity and neglect the perceptual and morphological qualities that shape the walking experience. This workflow proposes a Graph Machine Learning-centered multi-agent framework that integrates Large Language Models (LLMs), computational analysis, and human feedback to design and evaluate urban interventions. The framework positions Graph Machine Learning (GML) as the central predictive engine, capable of modeling network relationships and testing hypothetical scenarios, while LLMs act as perception interpreters that translate visual and textual information into experiential insights. Human agents validate and contextualize these results, ensuring alignment with policy and lived experience A new Street Walkability Index (SWI) is introduced, combining traditional Walkscore metrics based on land-use and perception-derived data, to provide a multidimensional measure of walkability, applied to Mexico City’s historic center as testing ground. 

This repository includes all working files:
- Multi-agent System in Grasshopper
- LLM street walkability perception script utilizing Google Street View and ChatGPT
  
...as well as the resultant analysis: 
- GSV image samples at https://drive.google.com/drive/folders/1hRJiDRepGATvxYMEShrXvJMr571OfzYJ?usp=sharing
- Spreadsheets with corresponding scores

INSTRUCTIONS TO INSTALL PYTHON LIBRARIES WITHIN GRASSHOPPER
1. Close Rhino
2. Open command prompt: cdm in windows
3. Go to the python environment: cd C:\Users\<username>\.rhinocode\py39-rh8\Scripts
4. type the following to install all needed libraries:  pip install numpy pandas matplotlib shapely geopandas scikit-learn torch==2.1.1 networkx dgl==2.2.0
	a. Note: it is important to install the correct versions of torch and dgl to ensure compatibility
5. Open Rhino
6. Open Grasshopper
7. Open components

TROUBLESHOOTING
• Go to the following address to check installed libraries' version: cd C:\Users\<username>\.rhinocode\py39-rh8\Scripts
	○ Use pip command to troubleshoot: pip list
• If there is still an error, delete contents of C:\Users\<username>\.rhinocode and try again
• If python.exe is not inside the .rhinocode folder, open Rhino, open Grasshopper, and add a python component…
	○ Close rhino after that and try again
