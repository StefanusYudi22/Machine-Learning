# MACHINE LEARNING PROJECTS

## PROJECT GROUPS
```
    - traditional-model
        - neighbors
        - linear
        - support vector
        - tree
        - ensemble
        - decomposition
        - cluster  
    - recommender-model
        - neural-collaborative-filtering
        - clustered-topic-modeling
        - collaborative-topic-modeling
    - natural-language-processing
        - sentiment-analysis-with-logistic-regresion
        - sentiment-analysis-with-naive-bayes
        - evaluating-word-embedding
        - naive-machine-translation-and-lsh
        - autocorrect
        - part-of-speect-tagging
        - autocomplete
        - create-word-embedding
        - sentiment-analysis-with-neural-networks
        - language-model-with-gru
        - name-entity-recognition-with-lstm
        - question-duplicates-with-siamese-network
        - neural-machine-translation
        - text-summarization
        - question-answering
        - chatbot
```
## FOLDER STRUCTURE
### LOCAL PROJECT
```
- <Project-Group>
    - <Project-Name>
        - data
            - raw
                - v1
                    - *folders
                    - *.csv
                    - *.xlsx
                    - *.txt
                - v2
                    - *folders
                    - *.csv
                    - *.xlsx
                    - *.txt
            - processed
                - v1
                    - *.pkl
                - v2
                    - *.pkl
        - notebook
            - *.ipynb
        - script
            - src
                - *.py
            - main.py
            - requirements.txt
            - Dockerfile
        - venv
            - <venv-1>
            - <venv-2>
            .
            .
        - images
            - *.png
            - *.jpeg
        <PROJECT-NAME>.md
```

### CLOUD PROJECT : KAGGLE
```
- <project-group>
    - <project-name>
        - data [stored in cloud with sampe structure as local]
        - notebook [stored in cloud]
        - images
            - *.png
            - *.jpeg
        - script
            - src
                - *.py
            - requirements.txt
            - main.py
            - Dockerfile
        - <PROJECT-NAME>.md
```

## TERMS & CONDITION
- Always make branch first other than main branch to work on a project
- Always create virtual environment to isolate project
- Script is the API version of the project