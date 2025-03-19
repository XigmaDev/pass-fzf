## pass-fzf

It's a script that enhances the pass with fzf.

## Usage

- Copy to clipboard:

  ```bash
  pass-fzf

  ```

- Type password directly:

  ```bash
  pass-fzf --type

  ```

- Copy OTP to clipboard:

  ```bash
  pass-fzf --otp

  ```

- Add key binding (Ctrl + p) in .zshrc file

  ```bash
  bindkey -s ^p "pass-fzf\n"

  bindkey -s ^o "pass-fzf --otp\n"
  ```

  ```

  ```

## Installation

```bash
 sudo curl -SfL0 https://raw.githubusercontent.com/xigmadev/pass-fzf/main/pass-fzf -o /usr/local/bin/pass-fzf && sudo chmod +x /usr/local/bin/pass-fzf

```
