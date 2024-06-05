# Activity Identification through Screen Text Experimentation

This project focuses on extracting and combining features from images and text using the CLIP model, performing clustering, and evaluating the results with various metrics. 
The goal is to analyze UI logs and process them to group different activities from processes. Experiments have been executed with Python 3.10.11.

## Features

- Extract features from images and text using the CLIP model or image hashing techniques.
- Perform clustering on the extracted features.
- Evaluate clustering results using metrics such as silhouette score, Davies-Bouldin score, and Calinski-Harabasz score.
- Save and load execution results for further analysis.

## Project Structure
- `executions`: directory where executions will be saved.
- `logs`: contains UI logs and OCR files for each problem..
- `resources`: contains all screenshots for each problem
- `core_experiments.ipynb`: main notebook to run the project.
- `requirements.txt`: list of dependencies required for the project.

## Dependencies
To install the required dependencies, run:
```
pip install -r requirements.txt
```
## Data and results

The detailed and organized execution results of the presented problems, along with the data, can be found on Zenodo. You can download them from the following link: [Zenodo Project Data](https://zenodo.org/records/11368319)

## Acknowledgments
- The [CLIP model](https://openai.com/index/clip/) used in this project is from OpenAI.
- Special thanks to the contributors and maintainers of the open-source libraries used in this project.

