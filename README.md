# odaetal2021

## Notice Regarding Editorial Expression of Concern (EoC) (8/22/2025 Updated)
The article Oda et al., 2021, related to this repository, has been issued an Editorial Expression of Concern (EoC) by Science Advances on 13 August 2025.
The content of the EoC is as follows:

>On 17 November 2021, Science Advances published the Research Article “Discovery of anti-inflammatory physiological peptides that promote tissue repair by reinforcing epithelial barrier formation” by Y. Oda et al. (1). The authors informed the journal of an institutional investigation related to the experimental conditions used for Fig. 2B. We are notifying readers while the institution reviews these issues.

The author has informed the journal that the paper is currently under institutional investigation.

The code in this repository uses pre-processed data provided by the first and corresponding author to generate figures in R. It does not include the data for Fig. 2B mentioned in the Erratum and the EoC.

However, since the paper has been issued an EoC, and I have not been able to establish any contact with the corresponding author since around October 2023, please refrain from using any data from the paper.


------------------------------------------------------
## Procedure（8/30/2021）

Environment : Google Colaboratory
https://colab.research.google.com/

1. Once: Create an ipynb file in the `Colab Notebooks` folder in `My Drive` (currently open file).

2. Once: Create an `Oda_etal_R` folder in `My Drive` and place the original data of the Excel file.

3. Mount Google Drive.

4. Run the following code to create the graph. The installed R package will be removed when the runtime is disconnected, so you will need to reinstall it each time you reconnect.

  ・Run the magic commands and install R packages.

  ・Define functions and draw the graph.

  ・Save the graph (comment it out when not in use).
