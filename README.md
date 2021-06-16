# image-captioning
Praca magisterska. Praca zawiera 4 gałęzie:
- `main` - zawiera metodę bazową <br>
- `ds-lstm`- podstawowy model enkoder-dekoder rozszerzony o deep stacked lstm <br>
- `local-attention` - podstawowy model enkoder-dekoder rozszerzony o atencję przyłączeniową <br>
- `attention_transformers` - model enkoder-dekoder wykorzystujący architekturę Transformer <br>

## Struktura folderów
To repozytorium zawiera jedynie niezbędny notebook. Do nauczenia podstawowego
modelu potrzebna będzie następująca struktura plików:
- `.` <br>
- `./Flickr8k_Dataset`  - Flickr Dataset <br>
- `./Flickr8k_text` - Flickr Dataset <br>
- `./image-captioning`- to repozytorium <br>
- `./glove` - containing word embeding <br>
- `./Pickle` - empty <br>
