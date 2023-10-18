# Submission for the unit 2 of Machine Learning (Bioinformatics and Biostatistics course): k-NN algorithm implementation

## USAGE:
To generate the output pdf and html documents, save the dataset (has to be .csv file) in the same folder as the Rmd code, open the .R file titled "dynamic_report_generator", and modify the parameters with your desired ones (namely, the dataset file and the variable of interest. Variable of interest has to be factor-like).

Once you've done that, generate the reports using the following code from the command-line. Tested on MacOS. I don't know how it works in Windows (PowerShell).

```bash
Rscript dynamic_report_generator.r
```

Requires Rscript, markdown, R, knitr and all the usual packages for knitting RMarkdown reports.