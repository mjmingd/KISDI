# KISDI

## BPE(Bite Pair Encoding)

For single file

```
python3 bpe_kor.py --input 'input_file' --output 'output_file' --vocab 'vocab_file' --symbols 10000 --min_frequency 2
python3 bpe_kor.py -i 'input_file' -o 'output_file' -v 'vocab_file' -s 10000 --minF 2
```


For multiple files

```
python3 bpe_kor.py --input 'input_file_dir' --multiple_inputs True --output 'output_file' --vocab 'vocab_file' --symbols 10000 --min_frequency 2
python3 bpe_kor.py -i 'input_file_dir' -dir True -o 'output_file' -v 'vocab_file' -s 10000 --minF 2
```
