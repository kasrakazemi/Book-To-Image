# Book Summary Analysis and Visualization

## Objective

The objective of this project is to create notebooks that combines Natural Language Processing (NLP), Computer Vision, Machine Learning, and Data Visualization to analyze and understand a dataset of book summaries. This involves cleaning the data, exploring its characteristics through Exploratory Data Analysis (EDA), shortening the summaries, and transforming them into images.

## Project Structure

- **Datasets:**
  - `original_dataset.txt` - The original dataset of book summaries [Google Drive Link](https://drive.google.com/file/d/1SmkaxOkPA8B4NaiiaR-IaJth1mv-UHk5/view?usp=sharing)
  - `dataset_cleaned.csv` - The cleaned dataset after preprocessing [Google Drive Link](https://drive.google.com/file/d/1ykTbHK-T4Ndx9YpLWO90HZpaf83tOvZp/view?usp=sharing)
  - `dataset_summarized.csv` - The dataset after summarization [Google Drive Link](https://drive.google.com/file/d/16IxTykfZ82hkpfRwIXsNILs3O1uO56ZL/view?usp=sharing)

- **Notebooks:**
  - `Data_Pre_&_Eda.ipynb` - Notebook for data preprocessing and exploratory data analysis.
  - `NLP.ipynb` - Notebook for condensing the book summaries using NLP techniques.
  - `Text_To_Image.ipynb` - Notebook for converting the condensed text summaries into images using a Text-to-Image model.

- **Output:**
  - `Generated Images` - Folder containing the images generated from the condensed text summaries.
  - `Articles & Resources.txt` - Text file containing links to articles and resources used in this project.

## Steps

### 1. Data Preprocessing and EDA

- **Notebook:** `Data_Pre_&_Eda.ipynb`
- **Description:**
  - Load the original dataset (`original_dataset.txt`). [Google Drive Link](https://drive.google.com/file/d/1SmkaxOkPA8B4NaiiaR-IaJth1mv-UHk5/view?usp=sharing)
  - Clean the data by handling missing values.
  - Perform exploratory data analysis (EDA) to understand the characteristics of the dataset.
  - Save the cleaned dataset to `dataset_cleaned.csv`. [Google Drive Link](https://drive.google.com/file/d/1ykTbHK-T4Ndx9YpLWO90HZpaf83tOvZp/view?usp=sharing)

### 2. NLP Component

- **Notebook:** `NLP.ipynb`
- **Description:**
  - Load the cleaned dataset (`dataset_cleaned.csv`). [Google Drive Link](https://drive.google.com/file/d/1ykTbHK-T4Ndx9YpLWO90HZpaf83tOvZp/view?usp=sharing)
  - Condense the book summaries to make them shorter using NLP techniques.
  - Save the summarized dataset to `dataset_summarized.csv`. [Google Drive Link](https://drive.google.com/file/d/16IxTykfZ82hkpfRwIXsNILs3O1uO56ZL/view?usp=sharing)

### 3. Computer Vision Component

- **Notebook:** `Text_To_Image.ipynb`
- **Description:**
  - Load the summarized dataset (`dataset_summarized.csv`). [Google Drive Link](https://drive.google.com/file/d/16IxTykfZ82hkpfRwIXsNILs3O1uO56ZL/view?usp=sharing)
  - Convert the condensed text summaries into images using a Text-to-Image model.
  - Save the generated images in the `Generated Images` folder.

## Results

- **Condensed Text Summaries:** Summarized versions of the book summaries, saved in `dataset_summarized.csv`.
- **Converted Images:** Images generated from the condensed text summaries, saved in the `Generated Images` folder.
- **EDA Findings:** Insights and visualizations from the exploratory data analysis, documented in `Data_Pre_&_Eda.ipynb`.

## Requirements

- Python 3.x
- Jupyter Notebook
- NLP libraries (NLTK, SpaCy)
- Computer Vision libraries (OpenCV, PIL)
- Data manipulation libraries (Pandas, NumPy)
- Data visualization libraries (Matplotlib, Seaborn)
