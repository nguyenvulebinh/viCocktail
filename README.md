# ViCocktail: Automated Multi-Modal Data Collection for Vietnamese Audio-Visual Speech Recognition

- Paper: https://www.isca-archive.org/interspeech_2025/nguyen25d_interspeech.pdf
- Code: https://github.com/nguyenvulebinh/AVSRCocktail
- Model: https://huggingface.co/nguyenvulebinh/AV-HuBERT-CTC-Attention-VI
  - Replace the [unigram model](https://github.com/nguyenvulebinh/AVSRCocktail/tree/main/src/tokenizer/spm/unigram) from AVSRCocktail with the [unigram2048.model](https://github.com/nguyenvulebinh/viCocktail/blob/main/unigram2048.model) and [unigram2048_units.txt](https://github.com/nguyenvulebinh/viCocktail/blob/main/unigram2048_units.txt) file.
- Dataset: https://huggingface.co/datasets/nguyenvulebinh/ViCocktail

```
@inproceedings{nguyen25d_interspeech,
  title     = {{ViCocktail: Automated Multi-Modal Data Collection for Vietnamese Audio-Visual Speech Recognition}},
  author    = {Thai-Binh Nguyen and Thi Van Nguyen and Quoc Truong Do and Chi Mai Luong},
  year      = {2025},
  booktitle = {{Interspeech 2025}},
  pages     = {166--170},
  doi       = {10.21437/Interspeech.2025-1559},
  issn      = {2958-1796},
}
```
