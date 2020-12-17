1. DESCRIPTION

The package includes a DOC folder containing the report writeup in PDF format and the final poster also in PDF format.
The CODE folder includes the Jupyter Notebook (team026code.ipynb) that cleaned the data to produce the final dataset. The final dataset (team026finaldataset.csv) along with the original dataset (team026data.zip) and the final Power BI dashboard (team026finaldashboard.pbix) can be downloaded from https://drive.google.com/drive/folders/1SWPaYnj4HAyeM6yN6fqpKC0sAOWj_IfA?usp=sharing.


2. INSTALLATION

	For Data Collection and Cleaning - these steps are unnecessary unless the user desires to process the data themselves since the Power BI file already has the data embedded:
		a) The provided Jupyter notebook requires a Python 3.7.x or 3.8. Other versions have not been tested
		b) The recommend platform to execute the Jupyter notebook is Anaconda Navigator, which can be downloaded, in case it is needed, from: https://www.anaconda.com/
		c) When installing Anaconda, select the option of including Jupyter if prompted
		d) If needed, add the following libraries to the environment: numpy, pandas, scikit-learn, matplotlib
		e) Make sure you have at least 5GB or memory available for the next steps

	For Power BI Visualization Final Project:
		a) Download the Microsoft Power BI Desktop software from the Microsoft website: https://www.microsoft.com/en-us/download/details.aspx?id=58494
		b) Follow the Microsoft download process for your computer
		c) Open the "team026finaldashboard.pbix" Power BI dashboard from the linked Google Drive folder mentioned in the Description.
		d) All done; feel free to explore the dashboard

		OPTIONAL STEPS - if you encounter errors when viewing the Power BI file, follow these additional steps to resolve
		a) Open the "team026finaldashboard.pbix" Power BI dashboard from the Google Drive folder mentioned in the Description.
		b) In the top ribbon, near the middle, there is a "spreadsheet with a pencil" icon. Click on the drop-down caret/arrow next to this icon.
		c) Click on "Data source settings" then click on "Change Source..."
		d) Click "Browse..." to change the data source to the "team026finaldataset.csv" file downloaded from the link provided in the Description.
			- This is helpful to ensure everything runs smoothly by pulling the data from its new location on your computer
		e) Click "Ok" then click "Close"
		f) Wait for the dashboard to refresh and apply the change; this is all the calculated columns/measures automatically re-calculating.
		g) All done; feel free to explore the dashboard.


3. EXECUTION

	For Data Collection, Cleaning, and Processing - these steps are unnecessary unless the user desires to process the data themselves since the Power BI file already has the data embedded:
		a) Download "team026data.zip" from the link provided in the Description and unzip it in a desired folder
		b) Save the included Jupyter notebook where it will be accessible for use
		c) Execute the Anaconda Navigator and launch the Jupyter Notebook application
		d) Navigate to the notebook saved in step b) and open
		e) Update "datasource" to point to the location where the file in step a) was decompressed
		f) Update "datadestination" to point to a location and file name where the clean data should be published.
		g) Run all cells, which should save a .csv file ready to be imported into Power BI

	For Power BI Visualization Final Project
		a) Once the "team026finaldashboard.pbix" dashboard is open, you can begin exploring it.
			- Refer to the "(?) Select for help" button on the near the top right of the dashboard for ways you can use the dashboard.
			- You can click on a bar/dot/text in a graph/table to filter the entire page to get more granular detail
				Ex: Selecting "Trash" in the bottom right bar graph of the "Overview" view will filter the page to only display trash-related service requests.
			- You can ignore the tooltip page; this shows up as a tooltip visual in the map on the left.

4. DEMO VIDEOS

	For Data Collection, Cleaning, and Processing: https://youtu.be/_s-XJjiNEks

	For Power BI Visualization Final Project: https://youtu.be/1bYskPsS8jY
