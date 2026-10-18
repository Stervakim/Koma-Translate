# Источники, лицензии и благодарности

Koma — независимая реализация. Код и фирменные материалы Torii в поставку не включены. Сходство сценариев чтения не делает Koma официальным форком Torii.

| Компонент | Источник / лицензия |
| :--- | :--- |
| Tesseract.js | [naptha/tesseract.js](https://github.com/naptha/tesseract.js), Apache-2.0 |
| PaddleOCR PP-OCRv6 | [PaddlePaddle](https://huggingface.co/PaddlePaddle/PP-OCRv6_medium_rec_onnx/tree/50c7eacafc52fa7bcf4194e8cd08e46f8558504b), Apache-2.0 |
| PP-OCRv6 Manga | [fumetodev](https://huggingface.co/fumetodev/PP-OCRv6_small_rec_manga_ONNX/tree/1ef01f78c59f6f66389c9722fd2d0ab761680ea9), Apache-2.0; японская модель, около 21 МБ, загружается отдельно |
| ComicTextDetector | [dmMaze/comic-text-detector](https://github.com/dmMaze/comic-text-detector/tree/440b978563c71b758e31aaa315d100faba1efa2f), GPL-3.0; модель загружается отдельно, не включена в CRX |
| Распространение / конверсия моделей | [ShinobuTranslator models-v0.8.3](https://github.com/DonutShinobu/ShinobuTranslator/releases/tag/models-v0.8.3); запись конверсии [efc90be](https://github.com/DonutShinobu/ShinobuTranslator/blob/efc90be822d69daaaffe33760090a21e968f66f8/THIRD_PARTY_NOTICES.md) |
| LaMa | [advimman/lama](https://github.com/advimman/lama), Apache-2.0; [экспорт g-ronimo/lama](https://huggingface.co/g-ronimo/lama/tree/418036c6b541e526cdbb0bead1ec3a87dabede53) |
| ONNX Runtime Web | [microsoft/onnxruntime](https://github.com/microsoft/onnxruntime), MIT |
| OpenCV.js | [opencv/opencv](https://github.com/opencv/opencv), Apache-2.0 |
| Fabric.js, pdf-lib, fflate | [Fabric](https://github.com/fabricjs/fabric.js), [pdf-lib](https://github.com/Hopding/pdf-lib), [fflate](https://github.com/101arrowz/fflate), MIT |
| franc-min | [wooorm/franc](https://github.com/wooorm/franc), MIT; необходимые зависимости сохраняют свои MIT notices |
| Шрифты | [google/fonts](https://github.com/google/fonts) и указанные в пакете источники; OFL и прочие оригинальные notices сохраняются |
| Локальное уточнение OCR | Адаптация идеи из [Libre Manga Translator Beta5](https://github.com/mrdhnto/libre-manga-translator/blob/dc2633b95d5b933cc58fca14c9fa5ced20864a5c/src/lib/ocr/utils.ts), MIT; атрибуция включена |

Исходники разработки Koma не публикуются. Это не отменяет прав и условий сторонних компонентов. Полные включённые лицензии и сведения о версиях находятся в `assets/licenses`, `assets/fonts` и `vendor` установочного пакета. Независимые адаптеры моделей написаны для Koma; GPL TypeScript-код Shinobu не импортировался.

Изображения моделей не встроены в установочный архив; их хеши, происхождение и ссылка на соответствующий upstream source сохранены в notices пакета. Обновления должны сохранять эти сведения.

Иллюстрации документации созданы для Koma; демонстрация интерфейса использует обезличенные данные. Страницы чужой манги и личные скриншоты в оформление не включены.
