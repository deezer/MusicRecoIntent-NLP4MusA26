# MusicRecoIntent-NLP4MusA26
This repository contains the dataset presented in the paper: **"[Beyond Musical Descriptors: Extracting Preference-Bearing Intent in Music Queries](https://arxiv.org/pdf/2602.12301)"**, accepted for publication at [**NLP4MusA 2026**](https://sites.google.com/view/nlp4musa-2026/home).

---

## MusicRecoIntent Dataset
**MusicRecoIntent** is a manually annotated dataset of music-related user queries designed to capture not only *musical descriptors* but also the **preference-bearing intent** associated with each descriptor.

Built on top of [MusicRecoNER](https://github.com/deezer/music-ner-eacl2023/tree/main) ([Epure and Hennequin, 2023](https://aclanthology.org/2023.eacl-main.92/)), the dataset contains:
- **2,291** English-language Reddit music recommendation requests
- **3,935** annotated musical descriptors (Genre, Mood, Instrument, Listening Context, Decade, Country and Musical Named Entities).

Each descriptor is annotated with a **preference-bearing intent**:
- `+` : positive (explicitly desired)
- `-` : negative (explicitly rejected)
- `~` : referential (similarity / inspiration)

---

## Citation

If you use the **MusicRecoIntent** dataset in your work, please cite:
```
@InProceedings{Baranes2026MusicRecoIntent,
 	title={Beyond Musical Descriptors: Extracting Preference-Bearing Intent in Music Queries},
  	author={Baranes, Marion and Hennequin, Romain and Epure, Elena V.},
  	booktitle={Proceedings of the 4rd Workshop on NLP for Music and Audio (NLP4MusA2026)},
  	month={March},
  	year={2026},
  	publisher = {Association for Computational Linguistics},
}
```
