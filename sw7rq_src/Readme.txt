README File for:
Establishing the social licence for COVID-19 tracking technologies in Australia

The original surveys in both Word and Qualtrics .QSF file formats can be found
  in the OSF 'Surveys' folder.

Data, code and functions for this project have been written and saved in R and
  can be found in the 'Data and Analysis' OSF folder.
- Data can be loaded from the 'AustCOVIDdata_public.RData' file
  - This file contains a list variable 'OzData' with four elements:
	W1: Wave 1 of data collection [Telecom & Gov App scenarios]
	W2: Wave 2 of data collection [Telecom, Gov App & Bluetooth scenarios]
	W4: Wave 3 of data collection [COVIDSafe usage]
	W4: Wave 4 of data collection [COVIDSafe usage]
    Each of the above elements contain the following variables:
	Data: Preprocessed (cleaned) data used in the paper's analysis.
	CleaningProcedure: The steps and removals taken to generate the preprocessed
	    'Data'.
	RawData: Anonymized raw data so other researchers can develop their own
	    analyses.
	Start and End dates: Dates for the start and end of data collection.
  - Analyses are contained in the 'AusResults.Rmd' file, however, all 
	custom fuctions are contained in the 'Functions.R' file. This file
	is called in the first code block of the analysis file.
    	Figures are created in the order they apear in the paper and additional
	descriptive statistics are presented at the end of the file.
  - A copy of all of the Figures in the paper are provided in the Figures.zip file.

If you have any issues or questions, please contact Dr Paul Garrett:
paul.garrett@unimelb.edu.au, OR
paulgarrett2016@gmail.com.

And please cite our paper/preprint if you use this data:

Garrett, P. M., White, J. P., Lewandowsky, S., Kashima, Y., Perfors, A., 
Little, D. R., Geard, N., Mitchell, L., Tomko, M., & Dennis, S. (n.d.)
The acceptability of smartphone tracking for COVID-19 in Australia. Preprint.


