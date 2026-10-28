# dm+ OCR models

A mirror of the OCR models dm+ reads photos with: its camera translation (WO-143). dm+ downloads them from this repo's release `v1` and checks each against the SHA-256 below, which it pins.

- **PaddleOCR's PP-OCRv5 models** (`*PP-OCRv5*`, `PULC_int8.mnn`, `textline_ori_x0_25_wq8.mnn`, the `*_keys.txt` files): [PaddleOCR](https://github.com/PaddlePaddle/PaddleOCR)'s own, Apache-2.0 (`LICENSE`), converted to [MNN](https://github.com/alibaba/MNN) and quantized by [offline-translator](https://github.com/DavidVentura/offline-translator).
- **`ink_color_int8.mnn`**: offline-translator's own ink matte, which states no licence. translator-rs reads nothing without one; mirrored at the owner's choice.

All downloaded from offline-translator's server, `https://offline-translator.davidv.dev/ocr/1/`, on 2026-10-28.

| File | Bytes | SHA-256 |
|---|---|---|
| `arabic_PP-OCRv5_keys.txt` | 2369 | `7f92f7dbb9b75a4787a83bfb4f6d14a8ab515525130c9d40a9036f61cf6999e9` |
| `arabic_PP-OCRv5_mobile_rec_infer_int8.mnn` | 2178136 | `fd451c5a370671be1cd4f8cbbf863c767ad640a36ff174960ad7bd4fcf5c1de3` |
| `cj_PP-OCRv5_keys.txt` | 74012 | `d1979e9f794c464c0d2e0b70a7fe14dd978e9dc644c0e71f14158cdf8342af1b` |
| `cyrillic_PP-OCRv5_keys.txt` | 2781 | `db40aa52ceb112055be80c694afdf655d5d2c4f7873704524cc16a447ca913ba` |
| `cyrillic_PP-OCRv5_mobile_rec_infer_int8.mnn` | 2191732 | `22e79edaedf5f94961d3264b5eda96dc389248436f3f608239e22966f73ea74f` |
| `devanagari_PP-OCRv5_keys.txt` | 1943 | `09c7440bfc5477e5c41052304b6b185aff8c4a5e8b2b4c23c1c706f6fe1ee9fc` |
| `devanagari_PP-OCRv5_mobile_rec_infer_int8.mnn` | 2154508 | `2d96d713df6d1e0799ed3df9d2101e35482124debea3a35fa7198d787536e479` |
| `el_PP-OCRv5_keys.txt` | 1103 | `31defc62c0c3ad3674a82da6192226a2ba98ef4ff014a7045cb88d59f9c3de31` |
| `el_PP-OCRv5_mobile_rec_infer_int8.mnn` | 2126260 | `f7b8eca8baa369afc07ec789ee59242719d3bcc438d00b9eeabb9340bf7df63f` |
| `eslav_PP-OCRv5_keys.txt` | 1663 | `3e95f1581557162870cacdba5af91a4c6be2890710d395b0c3c7578e7ee5e6eb` |
| `eslav_PP-OCRv5_mobile_rec_infer_int8.mnn` | 2147776 | `e28e953d314259b7b7729f7321de42d45bb3e73958080403ba66a28358f9e71f` |
| `ink_color_int8.mnn` | 1980972 | `a720a47def397c00b6c35fc28e21aa22ca2626a6da7d79f0f5f749bdabd3d52f` |
| `korean_PP-OCRv5_keys.txt` | 47451 | `a88071c68c01707489baa79ebe0405b7beb5cca229f4fc94cc3ef992328802d7` |
| `korean_PP-OCRv5_mobile_rec_infer_int8.mnn` | 3656272 | `9312b2d8c5d7e6cde7253e277570b5dbdf95777a5dc4d0f6e4ef1bfa62de051d` |
| `latin_PP-OCRv5_keys.txt` | 2616 | `ccbcc45730b3fbbd9050c5bc74db6a99067141ef1035e3d14889a84a6b9b1aff` |
| `latin_PP-OCRv5_mobile_rec_infer_int8.mnn` | 2189884 | `2ca40d83a486d63704f209f1c896762105a83374269d157658ffb7a98fc3b98e` |
| `PP-OCRv5_mobile_det_int8.mnn` | 1324660 | `bc4179b6d230be6a4c1ef9270266dc35e391635bbbb4f94a5bc7e4f4c77fd9a7` |
| `PP-OCRv5_mobile_rec_int8.mnn` | 4506088 | `1fac1c68e6a19f86db2fa5928e125cb935e150dcadb4a536dc78ed2b134a651d` |
| `PULC_int8.mnn` | 1799836 | `432e70d58713ad05c8abd122f0a0e79571d4cb5991d25d8382c0f8ba73400ec1` |
| `ta_PP-OCRv5_keys.txt` | 1723 | `85b541352ae18dc6ba6d47152d8bf8adff6b0266e605d2eef2990c1bf466117b` |
| `ta_PP-OCRv5_mobile_rec_infer_int8.mnn` | 2147248 | `891ea6100c8b56ad874e63d821f0357ca656a12c9d99729a02323ca5eec75118` |
| `te_PP-OCRv5_keys.txt` | 1831 | `42f83f5d3fdb50778e4fa5b66c58d99a59ab7792151c5e74f34b8ffd7b61c9d6` |
| `te_PP-OCRv5_mobile_rec_infer_int8.mnn` | 2150812 | `8fa21a8ff264df8eafb3d8735e686017ebc4e9d48390ff4f34c6282b781c427c` |
| `textline_ori_x0_25_wq8.mnn` | 309284 | `8db98011bcb081a34feebe3c4b13ea9f1194576984668877eb37320bd45fc4e0` |
| `th_PP-OCRv5_keys.txt` | 1767 | `57f5406f94bb6688fb7077f7be65f08bbd71cecf48c01ea26c522cb5c4836b7a` |
| `th_PP-OCRv5_mobile_rec_infer_int8.mnn` | 2148700 | `763f7bed0f2ab343ca0210ff8aab11dac5faeade7a8d202351512d7b21d746ff` |
