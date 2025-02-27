
Collection of short scripts and shell customizations for new environments

enable by adding `. ~/workspace/shellconfig` to `~/.bashrc` or equivalent



Short referenced command collection:

- `git -c core.sshCommand="ssh -i ~/.ssh/<your_key>" clone git@github.com:<user>/<repo>.git`
- `git config core.sshCommand 'ssh -i ~/.ssh/<your_key>'`



Host git_eriklamp5
    Hostname github.com
    IdentityFile ~/.ssh/eriklamp5_legion
    IdentitiesOnly yes

Host git_rdjrjqouqcu
    Hostname github.com
    IdentityFile ~/.ssh/rdjrjqoucu_legion
    IdentitiesOnly yes

origin  git@git_eriklamp5:eriklamp5/workspace.git (fetch)
origin  git@git_eriklamp5:eriklamp5/workspace.git (push)


