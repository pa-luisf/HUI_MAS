INSTRUCTIONS TO INSTALL PYTHON LIBRARIES WITHIN GRASSHOPPER
	1. Close Rhino
	2. Open command prompt: cdm in windows
	3. Go to the python environment: cd C:\Users\<username>\.rhinocode\py39-rh8\Scripts
	4. type de following to install all needed libraries:  pip install numpy pandas matplotlib shapely geopandas scikit-learn torch==2.1.1 networkx dgl==2.2.0
		a. Note: it is important to install the correct versions of torch and dgl to ensure compatibility
	5. Open Rhino
	6. Open Grasshopper
	7. Open components

TROUBLESHOOTING
	• Go to the following address to check installed libraries' version: cd C:\Users\<username>\.rhinocode\py39-rh8\Scripts
		○ Use pip command to troubleshoot: pip list
	• If there is still an error, delete contents of C:\Users\<username>\.rhinocode and try again
	• If phython.exe is not inside the .rhinocode folder, open Rhino, open Grasshopper, and add a python component…
		○ Close rhino after that and try again
