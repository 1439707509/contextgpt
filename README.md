# contextgpt
Add multi-page context association to chatGPT3.5 to achieve better translation results 

https://github.com/zyddnys/manga-image-translator
"Build upon the manga-image-translator library."



1. Add two new translation options: ocrtext and readfromdatanew
2. Execute the following commands in sequence:
```
python -m manga_translator -v --mode batch --translator=ocrtext -l CHS -i {folder}  --use-cuda
Delete the generated images.
python manga_gptautofanyi_plus2.py
python -m manga_translator -v --mode batch --translator=readfromdatanew -l CHS -i {folder}  --use-cuda

```
