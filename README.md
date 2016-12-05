# write-good-docker

Docker wrapper for [btford/write-good](https://github.com/btford/write-good).

## Usage

For linting `README.md` in the current directory, you would run

    docker run --rm --volume $PWD:/app hochzehn/write-good *.md

Just pass parameters as you would to `write-good` [CLI](https://github.com/btford/write-good#cli) while mounting your current directory as `/app` into the container.
