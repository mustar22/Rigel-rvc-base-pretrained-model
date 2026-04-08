# Rigel — RVC Base Pretrained Model

Multilingual RVC pretrained model trained on 1921 hours of speech and vocals across 14 languages.

---

## Dataset

**Total:** 1921 hours

| Language | Hours |
|---|---|
| English | ~800 |
| Singing (all languages) | ~190 |
| Russian | ~188 |
| Spanish | ~200 |
| Japanese | ~140 |
| Korean | ~80 |
| Indonesian | ~53 |
| Arabic | ~70 |
| Chinese (Mandarin) | ~70 |
| French | ~42 |
| Portuguese | ~40 |
| German | ~35 |
| Hindi | ~30 |
| Tagalog | ~30 |

---

## Models

### Base Model
- Data: 1921 hours mixed quality
- Steps: 3,890,220
- Batch: 40
- Precision: FP32
- Sample rate: 32kHz

### Fine-Tuned Model
- Data: 102 hours high quality
- Steps: 2,854,856
- Batch: 20
- Precision: FP32
- Sample rate: 32kHz

---

## Hardware

- CPU: AMD EPYC 9754
- RAM: 256GB
- GPUs: 1× H100, 4× L40s, 1× RTX 4080, 1× RTX 4070 Ti

---

## Status

- 32kHz ✅
- 40kHz ✅


## Download

| Version | Link |
|---|---|
| 32kHz Base + Fine-Tuned | [HuggingFace ↗️](https://huggingface.co/MUSTAR/Rigel-rvc-base-pretrained-model/tree/main/Rigel_32k_Base_and_FineTuned) |
| 40kHz Base + Fine-Tuned | [HuggingFace ↗️](https://huggingface.co/MUSTAR/Rigel-rvc-base-pretrained-model/tree/main/Rigel_40k_Base_and_FineTuned) |
