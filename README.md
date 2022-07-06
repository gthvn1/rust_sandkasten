# Rust Kindergarten

![Rust Logo](https://www.rust-lang.org/static/images/rust-logo-blk.svg)

My [Rust](https://www.rust-lang.org/) playground

## bm

- Create a tool to manage directoris as bookmark.
- It will return a string that will be the directory to move on.
  - We will create an alias or function in the shell to *cd* into the directory
  - So we renamed the binary **bmr** to avoid confusion

### TODO

- [X] Create the project
```
cargo new --vcs none bm
```
- [X] Start by following the [Rust CLI tutorial](https://rust-cli.github.io/book/tutorial/setup.html)
- [X] Update CLI to do:
  - `bmr -l`: list all available bookmarks
  - `bmr -d <bookmark name>`: delete the bookmark
  - `bmr -a <bookmark name>`: add the current directory as a bookmark named *named*
- [X] Add a wrapper that will be a shell function to do the **cd**
- [X] Implement functions using a YAML file to keep track of bookmarks
  - For example **.bm.yml**.
- [ ] Fix errors when deleting wrong entry
- [ ] Fix issues when loading empty bookmark
- [ ] Add some coloration

### Usage

- Install the **bmr**
- Install the shell wrapper and update paths
- The path to the bookmarks file is set up in the script
- Create an empty bookmarks: `echo "---" > /path/to/bm.yaml`
- Start adding path.
  - It adds the current path
  - Example: 
```
# bmr -a home
# bmr -l
home: /home/gthvn1
# bmr home
/home/gthvn1#
```
## Codingame

- Created using:
```
cargo new --vcs none codingame
```

- Most of exercices are taken from [coding game](https://www.codingame.com)
- Maybe have a look to [code wars](https://www.codewars.com)

## Monads

- Created using:
```
cargo new --vcs none monads
```
- It is a video found on youtube that explains monads by example but I don't
  remember which one it is.


## Notebook

- Give a try to [evcxr](https://github.com/google/evcxr/blob/main/evcxr_jupyter/README.md) for Jupyter
