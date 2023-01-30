# Gophers, meet Hugo

What if we created a docs site but used Hugo, a static site generator written in Go and distributed in binaries that don't require a small warehouse of crates or more gems than the Manhattan Diamond District or `pip install...` versioning hell. 

We have the technology. We can build a University Libraries IT documentation system that is **accessible, legible, and convenient**. We can do it in a way that creates minimal hurdles for non-techies to use, without relying on third-party services, adding substantial costs, or creating an additional system admin burden. We can make it lightweight and not require megabytes of JavaScript like other publishing systems or third-party documentation tools.

## Source Code

Gopherdoc's public source code is hosted at [github.com/UMNLibraries/gopherdoc](https://github.com/UMNLibraries/gopherdoc).

## Usage

1. Clone the repository from: [https://github.com/UMNLibraries/gopherdoc](https://github.com/UMNLibraries/gopherdoc)
2. Make your changes in the `/content` or `/static` folders.
3. Don't forget to test: `hugo server -D` 
4. Deploy! This could be automated with a cronjob to pull from the git repository and run `hugo` however often. I'm sure there's some fancy Github built-in way to do it as well.

## Miscellany 

This site was originally developed and refered to as 'Goldydoc' as an ode to the University of Minnesota's wonderful mascot, [Goldy](https://twin-cities.umn.edu/gopher-athletics/goldy-gopher). **rah! Go Gophers!**
