I have first downloaded the dataset from the cbioportal file.
Then by using untar function, the files were extracted. 
personalised file path was created for placing the file location.
RNA seq file, Patient data file and CNA file was loaded and read using read.delim() function.
RNA Seq id's were matched with patient ids and cna id's.
a metadata was created based on CNA level of ERBB2+.
The data was normalized using the DESeq2  package. 
The differentially expressed genes were observed using results() function.
In the next step, a pathway enrichment analysis was performed. 
here Gene ontology enrichment analysis was used along with the clusterprofiler package.
Different plots were created for visualising overexpressed and underexpressed genes.
By using Variance stabilized transformation(VST) values, PCA plot was plotted to capture variance in the data.
Also, a heatmap was produced along with hierarrchical clustering of 20 genes. 
