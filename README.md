# Fair play? Detecting and monitoring hate speech during the 2022 Qatar World Cup

This repository is an extension of my Master's Thesis, as a part of the Master in Computational Social Science, in which I construct a Machine Learning binary classifier to discern between tweets that are hateful and tweets that aren't, in order to unveil under which conditions hate spreads and to perform data visualizations from it (Sanz, 2023). The work is available here and in order to replicate it there are some points you should consider: 
- Due to privacy and storage reasons, I won't upload the employed dataset. In order to successfully download all of them, I've uploaded the queries that were used to interact with the Twitter API in the "queries_accounts" folder, as well as a .txt file with the IDs of all the tweets used ("tweetsIDS.txt").
- The code follows a linear structure from the first stages (0a and 0b), based on setting up the correct filters and gathering the downloaded data, to the model construction (1) and its application to the whole dataset (2), until the development of the visualizations and statistical analyses performed. It's crutial to correctly place files and documents in the adequate folders so that the code is able to run with no problems.
- The purpose of the data folder is to contain all inputs and outputs for the code. This includes the different parts that end up forming the dataset (not necessary if you download all tweets at once as explained previously), other datasets shared by X and X (not necessary if you don't want to check how they make performances worse), the annotated tweets (which we will upload) and the model, among others.
