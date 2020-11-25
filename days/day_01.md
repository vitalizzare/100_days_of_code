`#100DaysOfCode`

# Day 1
November 25, 2020

## 1
I've simplified the code for visual recognizing of the character encoding for the Russian text. Actually, I've discovered the posibility to use built-in methods `str.encode` and `bytes.decode` instead of corresponding functions in the `encodings` module.

https://github.com/vitalizzare/Sandbox/blob/main/snippets/decode_russian.py

<div class="alert alert-block alert-warning">
    <b>Warning:</b> for utf-16 and utf-32 be careful with '\n' at the end of line. This causes an error while decoding
</div>

## 2
Learned about `try: ... except` how to catch in one place several exceptions:
```python
try:
    parameter = int(sys.argv[2])
    assert parameter > 0
except (IndexError, ValueError, AssertionError):
    parameter = 1
```

## 3
Made a terminal progress bar for iterations, namely for the `pandas.DataFrame.apply` method. Actually, I could have done this earlier, but I forgot about the existence of the `\r` character, and instead of rewriting info in one place I piled up information on the screen. Now it looks like:

    Started at 23:42:46 with update every 1 seconds
    [▮▮▮▮▮▮▮▮▮▮▮▮▮▮▮▮▮▮▮▮▮▮▮▮▮▮▮▮▮▮▮▮▮▮▮▮▮▮▮▮▮▮▮▮▮▮▮▮▮▮▮▮▮▮▮▮▮▮▮▮▮]100%
    Done at 23:43:07

https://github.com/vitalizzare/jupyter_tools/blob/master/pandas_apply_progress.py

## 4

<div class='alert alert-block alert-danger'>
    <b>I need the plan for the next 99 days</b>
    </div>
