This DATSETNAMEreadme.txt file was generated on 2020-4-28 by Yeedong



GENERAL INFORMATION

1. Title of Dataset: Data from Co-occurrence pattern and function prediction of bacterial community in Karst cave

2. Author Information
	A. Principal Investigator Contact Information
		Name: Yeedong
		Institution: Xishuangbanna Tropical Botanical Garden, Chinese Academy of Sciences
		Address: Mengla, Yunnan, China
		Email: dongyee007@126.com

	B. Alternate Contact Information
		Name: Qingbei Weng
		Institution: Guizhou Normal University
		Address: Guiyang, Guizhou, China
		Email: wengqingbei@gznu.edu.cn

3. Date of data collection (single date, range, approximate date) <suggested format YYYY-MM-DD>: 2016-12 

4. Geographic location of data collection <latitude, longiute, or city/region, State, Country, as appropriate>: Zhijin cave is located in Guizhou Province in China (26º38′31″-26º52′35″N, 105º44′42″-106º11′38″E)

5. Information about funding sources that supported the collection of the data: The Joint Fund of the National Natural Science Foundation of China and the Karst Science Research Center of Guizhou Province (U1812401); Provincial Program on Platform and Talent Development of the Department of Science and Technology of Guizhou China (2019-5661, 2019-5617)


DATA & FILE OVERVIEW

1. File List: 
#OTU based on Pyhlum level,row:sampling site, col:phylum
rock otu_table phylum.csv
soil otu_table phylum.csv
stalactite otu_table phylum.csv

#OTU based on Genus level,row:sampling site, col:genus
rock otu_table genus.csv
soil otu_table genus.csv
stalactite otu_table genus.csv

#OTU based on species level,row:sampling site, col:species
rock otu_table species.csv
soil otu_table species.csv
stalactite otu_table species.csv

#OTU level,row:sampling site, col:OTU
rock otu_table.txt
soil otu_table.txt
stalactite otu_table.txt

#raw OTU level,row:sampling site, col:OTU
rock otu.txt
soil otu.txt
stalactite otu.txt

#pathway in different level,row:sampling site, col:pathway
Pathway1.csv
Pathway2.csv

#the genus in Phylum abundance,row:genus, col:Phylum and abundance
otu_pro.csv
soil otu_pro.csv
stalactite otu_pro.csv

2. Relationship between files, if important: compositions of community in different levels

METHODOLOGICAL INFORMATION

1. Description of methods used for collection/generation of data & Methods for processing the data:
Bacterial raw reads were produced by the Illumina MiSeq platform, the raw sequences were assembled for each sample, and low-quality sequences were filtered using QIIME. The OTUs (Operational Taxonomic Units) table for each sample were clustered at the 97 % similarity following the Uparse (http://drive5.com/uparse/), and the OTUs were classified and annotated based on the clustering results using the RDP database (http://rdp.cme.msu.edu) offering aligned and annotated for bacterial 16S rRNA sequences.

3. Instrument- or software-specific information needed to interpret the data: 
R software
