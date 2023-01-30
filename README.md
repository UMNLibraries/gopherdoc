# Goldy, meet Hugo

What if we created a docs site but used Hugo, a static site generator written in Go and distributed in binaries that don't require a small warehouse of gems or crates or `pip install...`.

## goldydoc and goldydoc-hugo

Goldydoc the site is served from [github.umn.edu/goldydoc](https://github.umn.edu/akierig/goldydoc) which is a submodule of this repository. If you don't use the `--recursive` flag when cloning this repo, you'll have problems.

Using the provided `hugo-build.sh` script will ask you for a summary (git commit message) of what you've done, build the site, then push both this repository and the generated site to github.umn.edu.

## Usage

1. Clone the repository: `git clone --recursive git@github.umn.edu:akierig/goldydoc-hugo.git && cd goldydoc-hugo` or using HTTP: `git clone --recursive https://github.umn.edu/akierig/goldydoc-hugo.git && cd goldydoc-hugo`
2. Make your changes
3. Don't forget to test: `hugo server -D` 
4. Deploy! Assuming you already have `hugo` in your path, you can run `./hugo-build.sh` from the folder root. If you don't, you can either install from your package manager of choice or grab it from [`github.com/gohugoio/hugo`](https://github.com/gohugoio/hugo/releases).

### `hugo-build.sh` notes

hugo-build.sh is a tool that mostly works. And that's the finest thing I have to say about it.

a couple of things that would strike Linux users as weird are because of the need to work-around MacOS packaging old versions of Bash and other common tools that are now under GPL-3 or use non-POSIX GNU extensions.


