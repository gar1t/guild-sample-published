[Published runs](../README.md)

# llm.py

| ID                   | Operation           | Started                  | Time                | Status           | Label                |
| --                   | ---------           | ---------                | ----                | ------           | -----                |
| 77bc78a2 | llm.py | 2023&#8209;06&#8209;05 16:29:36 UTC | 0:00:00 | error | max_length=50 prompt='This is the default prompt' skip_special_tokens=yes |

[run.yml](run.yml)

## Contents

- [Flags](#flags)
- [Scalars](#scalars)
- [Run Files](#run-files)
- [Source Code](#source-code)
- [Output](#output)

## Flags

| Name | Value |
| ---- | ----- |
| do_sample |  |
| early_stopping |  |
| max_length | 50 |
| no_repeat_ngram_size |  |
| num_beams |  |
| num_return_sequences |  |
| prompt | This is the default prompt |
| skip_special_tokens | yes |
| temperature |  |
| top_k |  |

[flags.yml](flags.yml)
## Scalars

There are no scalars for this run.
## Run Files

There are no files for this run.
## Source Code

| Path | Size | Modified | MD5 |
| ---- | ---- | -------- | --- |
| [llm.ipynb](sourcecode/llm.ipynb) | 11.6K | 2023-06-05 11:29:36 UTC | 7f99606ad564c866e8a83d0e137df793 |
| [llm.py](sourcecode/llm.py) | 1.5K | 2023-06-05 11:29:36 UTC | 10000342955b86dbba9d570447c40197 |

[sourcecode.csv](sourcecode.csv)
## Output

```
Traceback (most recent call last):
  File "/home/garrett/.guild/runs/77bc78a2e5d94caeba9f2b5a81ad8fba/llm.py", line 1, in <module>
    import transformers
ModuleNotFoundError: No module named 'transformers'
```

[output.txt](output.txt)

