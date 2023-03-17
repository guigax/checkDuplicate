# checkDuplicate

It checks if lines from a file have duplicates, it returns the duplicated text along with the amount of times it was found in the file. It is also very fast.

I got this code from [The Go Programming Language: A Tutorial](https://www.informit.com/articles/article.aspx?p=2453564&seqNum=3), I did not find any repository on the website that I cound fork, so I made my own.

## Requirements

[Go 1.18+](https://go.dev/dl/)

## Build

    go build checkDuplicate

## Usage

    ./checkDuplicate examples.txt

## Output

    2       \"
    2       '
    2       \
    3       super
    4       test