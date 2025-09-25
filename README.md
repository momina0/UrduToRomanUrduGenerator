# UrduToRomanUrduGenerator
Urdu to Roman Urdu Transliteration using BiLSTM

This project implements a BiLSTM Encoder–Decoder model for transliteration of text from Urdu script to Roman Urdu. The model is trained on parallel Urdu–Roman Urdu sentence pairs and learns character/word-level mappings between the two writing systems.

✨ Features

BiLSTM Encoder–Decoder architecture for sequence-to-sequence learning

Support for subword tokenization (BPE/SentencePiece) to handle rich Urdu morphology

Custom collate functions for batching with padding

Training loop with teacher forcing, loss logging, and checkpoint saving

BLEU evaluation (sentence-level and corpus-level) for transliteration quality

Sample translations during evaluation for qualitative analysis
