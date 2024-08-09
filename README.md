# NeuroHackademy 2024 project directory

## Projects

### TITLE
**Description**: A PARAGRAPH ABOUT THE PROJECT \
**Project url(s)**: GITHUB LINK, OTHER LINKS \
**Contributors**: [NAME](https://github.com/GITHUB HANDLE), [NAME](https://github.com/GITHUB HANDLE), ETC \

### No scientist is an island
**Description**: Scientists often create data derivatives (i.e., transforming, combining, and/or altering raw variables in some way) when cleaning data and preparing for analyses. Unfortunately, these derivatives are often generated within larger scripts, are the result of judgement calls that aren't written down (e.g., deriving a new variable for a subset of the entire sample), can be duplicated when team members aren't aware that the work has already been done by someone else, and can be lost when team members move on to other projects, graduate, and/or leave the group for their next positions. The goal of this project is to develop a workflow for how teams can efficiently and transparently create, document, and share data derivatives with their future selves, their team members, and their collaborators through the creation and maintenance of a **derived data registry**.   \
**Project url**: https://github.com/no-scientist-is-an-island/no-scientist-is-an-island.github.io  \
**Contributors**: [Theresa Cheng](https://github.com/theresacheng) & [Megan Huibregtse](https://github.com/meganhuibregtse)  

### NeuroNest
**Description**: NeuroNest is the brainchild of students, researchers, and enthusiasts who attended Neurohackademy 2024 at the University of Washington in Seattle. Our platform is dedicated to exploring the intersection of data science and brain science, providing a comprehensive resource for anyone interested in these fields. We believe in the power of knowledge sharing and community learning, aiming to demystify complex concepts in neuroimaging and data science, making them accessible to all. Our mission is to create an inclusive space where beginners and experts alike can find valuable resources. We offer a diverse array of content, including tutorials on MRI, EEG, and machine learning, coding snippets, project ideas, and insightful articles on the latest technologies and techniques. At NeuroNest, we understand that learning is a continuous journey, and we're here to support you every step of the way. The NeuroNest community is built on curiosity, innovation, and collaboration. We are passionate about fostering an environment where learning is both fun and rewarding. Whether you're just starting or looking to deepen your expertise, NeuroNest is the place to unlock new insights and explore the wonders of the brain and data. Join us as we delve into this exciting world and become a part of a vibrant community dedicated to advancing knowledge and innovation. Welcome to NeuroNest! \
**Project url**: https://neurohackademy2024.github.io/NeuroNest/ \
**Contributors**: [Cynthia Sopko](https://github.com/sopkoc), [Annachiara Crocetta](https://github.com/annachiaraX), [Arianna Mordy](https://github.com/arianna-mordy), [Sara Wong](https://github.com/smwong4), [Morgan Fitzgerald](https://github.com/morganfitzgerald), [Anne-Marie Leiby](https://github.com/annemarieleiby), [Alan Patrick Davalos-Guzman](https.github.com/alanpdav), [Elena von Perponcher](https://github.com/perponcher), [Mohamed Elsherif](https://github.com/drmohamedelsherif)

### BIDSInspec
**Description**: BIDSInspec is a python library that will help researchers summarize, visualize, and validate their BIDS datasets. With the increasing use of automated tools (e.g., BIDS apps) it is important to always examine your data prior to pre-processing. A problem that arises when curating neuroimaging data is the heterogeneity that exisits in MRI session aquisitions within and across institutions. BIDSInspec is designed to solve these problems by: 1. creating a summary report of the BIDS directory by specific features (e.g., scanner type, magnetic field stength, acquisition time, resolution, etc.) and 2. enabling researchers to validate a BIDS dataset against an acquisition protocol using features within JSON sidecar files and NIFTI image properties (e.g., image shape, resolution, etc.)\
**Project url(s)**: https://github.com/NeuroHackademy2024/BIDSInspec \
**Contributors**: [Ashley Ptinis](https://github.com/aptinis), [Nancy Ortega](https://github.com/neortega25)

### Nipoppy-EffeX
**Description**: Nipoppy-effeX addresses the challenge of underpowered functional magnetic resonance imaging (fMRI) studies, which often rely on limited sample sizes and custom preprocessing pipelines. Our project proposes a portable, user-friendly BIDS application that facilitates the reprocessing of both public and non-public fMRI datasets. Currently, Nipoppy-effeX enables researchers to execute semi-automated, reproducible data processing pipelines solely for resting-state functional connectivity analyses. By leveraging the lightweight Nipoppy framework and robust tools like fMRIPrep, users can perform within-subject and between-group analyses efficiently. Future enhancements include extending the application’s capabilities to support task-based fMRI analyses and enabling users to transmit results to a central server, further enriching the landscape of fMRI research. By democratizing access to comprehensive fMRI analysis, Nipoppy-effeX paves the way for more powerful and statistically sound neuroimaging studies while complementing existing databases like BrainEffeX. \
**Project url**: https://github.com/andreifoldes/nipoppy-effex \
**Contributors**: [Tamas Foldes](https://github.com/andreifoldes), [Hallee Shearer](https://github.com/halleeshearer), [Michelle Wang](https://github.com/michellewang)

### Federated Learning 
**Description**: Federated learning (FL) has become a promising machine learning method for conducting large-scale analyses across multiple institutions without the need to share data. With FL, data privacy and security are maintained, as the data never leave the institution; only encrypted model parameters are exchanged and aggregated. The aim of our project was to explore the use of FL using Flower (open source federated learning framework) and scikit-learn to predict brain age using measures of grey and white matter volume. We first focus on collating FreeSurfer statistical data across multiple subjects, focusing on both cortical and subcortical brain regions from the Healthy Brain Network (HBN). We included 223 participants with demographic information and freesurfer deriviates available. Our script (client_newmodel.py) sets up a client for federated learning using the Flower (see https://flower.ai/docs/framework/tutorial-series-what-is-federated-learning.html for more details). It enables training and evaluation of machine learning models (Logistic Regression, Linear Regression, LassoCV) on different partitions of the HBN sample. The client communicates with a federated learning server to participate in model training and evaluation of tasks over multiple rounds of federated learning, and saves the aggregated model weights after each round. We use 3 to mimic different dataset and compare accuracy in models with different sample distributions. 
**Project url**:https://github.com/mollyolzinski/Federated-Learning.git \
**Contributors**: [Michelle Wang](https://github.com/michellewang), [Emma Corley](https://github.com/emmajanecorley), [Eren Kafadar](https://github.com/kafadare), [Molly Olzinski](https://github.com/mollyolzinski), [Aoife Warren](https://github.com/AoifeWarren), [Audrey Weber](https://github.com/aweber7), [Maya Lakshman](https://github.com/mayalakshman) 

### NeuroNav
**Description**: The NeuroNav dashboard is an interactive tool for visualizing a subset of data from the Human Connectome Project Young Adult dataset. Users of this tool can display and interact with different types of plots in each panel of the tool. One panel shows the age and sex distribution of the sample. Another panel allows users to plot performance on behavioral tasks against one another or against various structural brain measures such as white or gray matter volume. Users have the options to display a line of fit over this data and to display data for a chosen age or sex bucket. In the final panel, users can display plots representing results from tractometry analysis. This project uses Jupyter Widgets to render the elements of each plot, including the interactive components.\
**Project url**: https://github.com/NeuroHackademy2024/neuro-nav \
**Contributors**: [Eyerusalem Abebaw](https://github.com/EyerusalemAbebaw), [Rohini Kumar](https://github.com/kumar-rohini), [Sophia Mehdizadeh](https://github.com/smehdizadeh), [Jonathan Wehnert](https://github.com/jonathanwehnert)

### Using Machine Learning to Explore Emotional States in the Human Connectome Project
**Description**: Psychopathology arising from enhanced negative emotion or from the loss of positive emotional experience affects over 400 million people globally. Such states of disordered emotion cut across multiple diagnostic categories and are compounded by accompanying disruptions in cognitive function. Not surprisingly, therefore, these forms of psychopathology are a leading cause of disability. The Human Connectome Project (HCP) contains multi-modal neuroimaging data of over 1000 people aged 18-35 years who are experiencing varying degrees of acute threat, loss of reward valuation/responsiveness, and difficulties in working memory. This project aims to develop a suite of open-source machine learning predictive and multimodal frameworks for structural and functional neuroimaging data from the HCP to evaluate aspects of emotional self-perception and recognition. \
**Project url**: https://github.com/dbraun31/nh2024-hcp1200-ml \
**Contributors**: Angelina, Da Yea, Dave, Diana, Dickson, Haruka, Jacqueline, Jiayue, Jony, Kristen, Laura, Melissa, Mingcong, Omair, Ruize, Shangcheng, Shuhei, Theresa, Yuxiang. :)
   
