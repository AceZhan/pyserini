# mrtydi-v1.1-thai

Lucene index for Mr.TyDi v1.1 (Thai).

This index was generated on 2022/01/08 at Anserini commit [`6fcb896`](https://github.com/castorini/anserini/commit/6fcb896c61e2b8cf2f235def3e95dda5fe4cd2fc) on `orca` with the following command:

```
target/appassembler/bin/IndexCollection -collection MrTyDiCollection \
  -generator DefaultLuceneDocumentGenerator -threads 1 \
  -input /store/collections/mr-tydi-corpus/mrtydi-v1.1-thai/ \
  -index indexes/lucene-index.mrtydi-v1.1-thai.20220108.6fcb89/ \
  -storePositions -storeDocvectors -storeRaw -optimize -language th
```