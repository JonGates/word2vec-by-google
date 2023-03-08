# word2vec-by-google
谷歌的 word2vec 工具



使用

```shell
time ./word2vec -train ./data/merge.txt -output ./data/597.vec -size 100 -window 5 -sample 1e-4 -negative 5 -hs 0 -binary 1 -cbow 1 -iter 3 -threads 20 -save-vocab ./data/auto.vocab.txt
```

