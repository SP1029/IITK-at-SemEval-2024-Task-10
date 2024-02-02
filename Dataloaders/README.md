First create a Folder with sent2emb.pickle present in it
Ensure to Pickles-Folder-Path, Training-csv-path and Validation-csv-path
For Task 1, only run ERC_Dataloader.py
For Task 2 and 3, first run ERC_Dataloader.py. Then run EFR_Dataloader.py
In ERC Dataloader ensure to "emos" list on line 61 when using for different tasks accordingly. It contains the list of possible emotions.
Also update the size from 768 to appropriate value