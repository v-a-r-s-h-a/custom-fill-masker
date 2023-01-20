# custom-fill-masker is all you need!

This repository contains the code and models for filling missing vibhaktis in a sentence.

Proceed according to the following steps 👇🏻:

✅1. Clone this repository
✅2. Download the requirements:
-pip3 install -r requirements.txt
✅3. Run this python program:
-python3 pred_vibhakti.py "sentence_with_mask_token"

    - For example:python3 pred_vibhakti.py "एक समय <mask> बात है।"

✅4. Please Use this mask token syntax:<mask>
✅5. Program raises an exception if:
-If this mask(<mask>) token syntax is not used
-If no mask token in a sentence
-If more than one mask token in a sentence.

This repo also has ipython notebook for mask predictions when the input is a file containing a bulk of sentences.

- Just run the cells in the sequence and it should work.
