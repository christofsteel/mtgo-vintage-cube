# MTGO Vintage Cube as a git Repository

Cards are stored in `cards.txt` and sorted by their english name. Each revision of the cube is 
represented as a tagged commit, named by the date in ISO-8601 (YYYY-MM-DD). You can compare two
configurations of the cube using `git diff`.
