`#100DaysOfCode`

# Day 2
November 26, 2020

## 1
I've added a linter to my jupyter-lab workspace.

There are still troubles with the pyflakes linter, which are related to the inconsistency of line numbering - linter's end-to-end versus pylab's cell-by-cell. But in general, I can at last use the linter right inside of notebook. 

https://github.com/vitalizzare/jupyter_tools/blob/master/nb_linter.py

## 2
As for planning, I found [some interesting advice](https://twitter.com/karpathy/status/1325154823856033793).

**How to become expert at thing:**

1. iteratively take on concrete projects and accomplish them depth wise, learning “on demand” (ie don’t learn bottom up breadth wise)
1. teach/summarize everything you learn in your own words
1. only compare yourself to younger you, never to others

## 3
Applied to myself the advice **"Don't force people to learn RegEx every time they read your code"**.
Hope in a couple of weeks I will understand my code.

    # Expected head line:
    # 'Code Cell 55 that starts with '<...>' has the following errors'
    # ================================================================
    # Regex Fragment             | Meaning
    # ================================================================
    #  [^\d]*                    | Match not digits...
    #      (\d+)                 | Match group 1 of digits...
    #         [\w\s]*            | Match letters or spaces...
    #                '           | ...then a single quotation mark
    #                (.*)        | Match group 2 of anything...
    #                    '       | ...until next single quotation mark
    #                    [\w\s]* | Match any words and spaces
    # ^                        $ | Match every character
    # ================================================================
    # Expected output of substitution:
    # '55,<...>'

## 4
**Still need the plan to organize myself.**
