# bgit_clone_sample
Sample repo to demonstrate bgit clone posthook in action

### To start

```bash
cargo install --git https://github.com/rootCircle/bgit.git
```

### Usage

Then run bgit in some folder:
```bash
bgit
```

It will prompt you to Initialze/Clone a Repository, click on Clone, and then enter repository link as `https://github.com/rootCircle/bgit_clone_sample` and let `bgit` autosetup rust for you using post_git_clone hook.


