# Advent of Code

Execute the files with the following command:
```
for AOC_FILE in $(find . -name "aoc-*.py")
do
  docker container run --rm -it -v $(pwd):/app -w /app python:3.13-alpine python "${AOC_FILE}"
done
```
