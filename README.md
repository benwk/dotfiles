# Ben's Dotfiles

## chezmoi.toml

```toml
[data.path]
  home = ""

[data.git]
  name = ""
  email = ""
  signingkey = ""

[data.cloudflare]
  clientID = ""
  clientSecret = ""
  accountID = ""
  pagesProject = ""
  apiToken = ""
  apiEmail = ""

[data.bitbucket]
  username = ""
  password = ""

[data.maven]
  username = ""
  password = ""

[data.mysql.dev]
  user = ""
  password = ""

[data.zsh]
  theme = "robbyrussell"

[data.ssh]
  name = ""
  proxy = "false"
  proxyAddress = ""
  orb = "false"

[scriptEnv]
  OP_SUBDOMAIN = ""
  OP_EMAIL = ""
  OP_VAULT = ""
  OP_SSH = ""
```

## How to use

### Install chezmoi

```shell
# macOS
brew install chezmoi
# ubuntu
sudo apt install chezmoi
```

### Install dotfiles

```shell
chezmoi init https://github.com/benwk/dotfiles.git
chezmoi update
chezmoi apply
```