# GSoC_IA
This repository contains my contributions to the Internet Archive organization as part of the Google Summer of Code (GSoC) program         

*Interactive Analysis of NRC Gov Data*

In the quest for advancing regulatory transparency and promoting public engagement, the aim is to transform the vast repository of Nuclear Regulatory Commission (NRC) government data into an interactive and insightful resource. By leveraging a collection of carefully crafted scripts, this initiative seeks to provide users with the ability to explore, analyze, and gain meaningful insights from the NRC's documents and reports.

*Script Summaries:*

1. *Entity_Extraction.py*
   - This script employs Named Entity Recognition (NER) to extract specific types of entities (such as organizations and persons) from textual data.
   - It preprocesses input data, identifies entities, and tallies their frequency for further analysis.
   - The results are then structured in a format compatible with the Clustergrammer tool.

2. *Task-2.py*
   - A comprehensive script that orchestrates multiple tasks for efficient data extraction and analysis from the Internet Archive.
   - It retrieves text file URLs, downloads files, preprocesses text data, and performs document clustering using TF-IDF and KMeans.
   - The script clusters documents, analyzes clusters, and presents execution time information.

3. *Top_10_Topic_Cluster.py*
   - This script focuses on identifying and extracting the top 10 most frequent topics present within the preprocessed text data.
   - By creating a Clustergrammer-compatible matrix, the script enables a visual representation of topic presence across documents.

4. *Top_50_Orgs_Cluster.py*
   - A script dedicated to extracting and ranking the top 50 most frequently occurring organizations from the preprocessed text data.
   - It generates a Clustergrammer-formatted matrix that showcases the frequency of these organizations across documents.

5. *Top_50_Person_Cluster.py*
   - Similar to the organizations script, this one extracts and ranks the top 50 most frequently occurring persons.
   - By visualizing the frequency of persons across documents, the script enhances the interactivity and insights of the data.

6. *Warc_Reader.py*
   - A script tailored to processing URLs pointing to WARC files containing PDFs.
   - It extracts data from these PDFs using the pdfminer library and compiles the extracted content, along with problematic files, into an output file.
   - This script adds depth to the data pool by making PDF content more accessible.

*Overall Vision:*

Through the coordinated execution of these scripts, the vision is to create an enriched environment for users to explore NRC government data interactively. The scripts facilitate the extraction of meaningful entities, identification of frequent topics, and analysis of document clusters, organizations, and persons. The resulting Clustergrammer-compatible matrices offer users a dynamic interface to navigate and comprehend the NRC's vast repository, fostering better understanding and engagement with regulatory information.
