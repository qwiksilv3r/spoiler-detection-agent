\# Book Spoiler Detection Agent



NLP agent that detects and highlights spoilers in book reviews using sentence-level classification.



\## Dataset

UCSD Goodreads spoiler subset (~1.3M reviews, sentence-level labels)



\## Tech Stack

\- \*\*Model\*\*: DistilRoBERTa (Hugging Face Transformers)

\- \*\*Baseline\*\*: TF-IDF + Logistic Regression

\- \*\*Demo\*\*: Gradio UI on Hugging Face Spaces

\- \*\*Training\*\*: Google Colab (GPU)



\## Project Structure
spoiler-detection-agent/
├── data/ # Dataset (not committed)
├── notebooks/ # Colab experiments
├── src/ # Data processing + model code
├── app/ # Gradio demo
└── README.md


## Quick Start
1. Download dataset to `data/raw/`
2. Run `notebooks/01_load_and_explore.ipynb` 
3. Train baseline → transformer
4. Launch Gradio demo

## Status
🚧 In progress - building MVP



