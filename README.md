# RepoFlux

a simple tool to flatten any github repository into a single html page

## what it does

takes any github repo and converts it into one static html file with all the code. useful when you want to quickly browse through a codebase or search across all files at once.

## installation

```bash
uv tool install git+https://github.com/ilakiancs/repoflux
repoflux https://github.com/some-user/some-repo
```

or install manually:

```bash
git clone https://github.com/ilakiancs/repoflux
cd repoflux
pip install -e .
repoflux https://github.com/some-user/some-repo
```

## features

- converts entire repos to single html files
- syntax highlighting for code files
- markdown rendering for documentation
- two view modes: human-readable and llm-friendly
- responsive sidebar navigation
- directory tree overview
- skips binary files and large files automatically
- works offline once generated

## usage

the tool will clone the repo, process all files, generate an html page and open it in your browser. you can switch between human view (nice formatting) and llm view (plain text format for copying to ai tools).

## options

- `--max-bytes`: set file size limit (default 50kb)
- `--out`: specify output file location
- `--no-open`: dont open browser automatically

## license

bsd0
# RepoFlux
