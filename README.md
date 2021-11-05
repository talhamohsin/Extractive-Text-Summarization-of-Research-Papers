# Extractive Text Summarization of Research Papers (SummaBot)
A simple extractive summary generator




![Overview of Summa Bot](https://github.com/talhamohsin/Extractive-Text-Summarization-of-Research-Papers/blob/main/figures/Summa_bot_work_flow.png)

## Running SummaBot
- Download the glove, w2vec, and fasttext pre-trained models from here.
  1. https://drive.google.com/file/d/13YnWUHCCinuf-cegK97Xdi8SwtC5Fidg/view?usp=sharing
  2. https://drive.google.com/file/d/17h1fATE3ylb6JbxPQ4Gsfu-iZFxfOCVx/view?usp=sharing
  3. https://drive.google.com/file/d/1Gk7Ac552nDmPlMfCicfF8unDPjZdrjG_/view?usp=sharing
- Place the models in the `src` folder
- Install all the requirements via `pip3 install -r requirements.txt` in the `src` folder
- Run the SummaBot jupyter notebook in the `src` folder


To summarize a different paper, ensure that the paper follows IEEE format, then invoke `SummaBotDriver(file_path)`. Make sure all the previous classes have been loaded and executed.
