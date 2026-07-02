#English → Hindi Translation & Evaluation Pipeline

Translates English sentences to Hindi using Llama 3.2 (1B Instruct, 4-bit quantized) and scores the output against reference translations using BLEU, chrF, and TER.

#Files


Assignment_2_code.ipynb — Jupyter notebook version. Runs cell by cell with no functions, so any error points directly at the exact step and line that failed. Use this for development, debugging, and one-off runs.

#Setup


#Install dependencies:


   pip install pandas torch transformers bitsandbytes accelerate sacrebleu tqdm --break-system-packages


Request access to the gated Llama 3.2 model on Hugging Face:
https://huggingface.co/meta-llama/Llama-3.2-1B-Instruct
Get a Hugging Face access token: https://huggingface.co/settings/tokens (needs read access). You'll be prompted for it when you run the notebook/script — it is never hardcoded or written to disk.

