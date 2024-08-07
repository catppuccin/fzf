<h3 align="center">
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/logos/exports/1544x1544_circle.png" width="100" alt="Logo"/><br/>
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/misc/transparent.png" height="30" width="0px"/>
	Catppuccin for <a href="https://github.com/junegunn/fzf">fzf</a>
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/misc/transparent.png" height="30" width="0px"/>
</h3>

<p align="center">
    <a href="https://github.com/catppuccin/fzf/stargazers"><img src="https://img.shields.io/github/stars/catppuccin/fzf?colorA=363a4f&colorB=b7bdf8&style=for-the-badge"></a>
    <a href="https://github.com/catppuccin/fzf/issues"><img src="https://img.shields.io/github/issues/catppuccin/fzf?colorA=363a4f&colorB=f5a97f&style=for-the-badge"></a>
    <a href="https://github.com/catppuccin/fzf/contributors"><img src="https://img.shields.io/github/contributors/catppuccin/fzf?colorA=363a4f&colorB=a6da95&style=for-the-badge"></a>
</p>

<p align="center">
		<img src="./assets/preview.webp" />
</p>

## Previews
<details>
<summary>🌻 Latte</summary>
<img src="./assets/latte.webp" />
</details>
<details>
<summary>🪴 Frappé</summary>
<img src="./assets/frappe.webp" />
</details>
<details>
<summary>🌺 Macchiato</summary>
<img src="./assets/macchiato.webp" />
</details>
<details>
<summary>🌿 Mocha</summary>
<img src="./assets/mocha.webp" />
</details>

## Usage

1. Choose your flavour below.
2. Run a snippet based on your shell:
    - **Bash/Zsh**: add the Bash/Zsh snippet to your `~/.bashrc`, `~/.zshrc` or custom file loaded on shell startup.
    - **Fish**: run the Fish snippet once.
    - **Nushell**: add the Nushell snippet to your `$nu.env-path`.
    - **PowerShell**: add the PowerShell snippet to your `~/Documents/PowerShell/Microsoft.PowerShell_profile.ps1`.

> [!TIP]
> If you are using a transparent terminal background, remove the `bg` option in
> the following list of snippets.

<details>
<summary>🌻 Latte</summary>

**Bash/Zsh**:
```sh
export FZF_DEFAULT_OPTS=" \
--color=bg+:#ccd0da,bg:#eff1f5,spinner:#dc8a78,hl:#d20f39 \
--color=fg:#4c4f69,header:#d20f39,info:#8839ef,pointer:#dc8a78 \
--color=marker:#7287fd,fg+:#4c4f69,prompt:#8839ef,hl+:#d20f39 \
--color=selected-bg:#bcc0cc \
--multi"
```

**Fish**:
```sh
set -Ux FZF_DEFAULT_OPTS "\
--color=bg+:#ccd0da,bg:#eff1f5,spinner:#dc8a78,hl:#d20f39 \
--color=fg:#4c4f69,header:#d20f39,info:#8839ef,pointer:#dc8a78 \
--color=marker:#7287fd,fg+:#4c4f69,prompt:#8839ef,hl+:#d20f39 \
--color=selected-bg:#bcc0cc \
--multi"
```

**Nushell**:
```nu
$env.FZF_DEFAULT_OPTS = "
--color=bg+:#ccd0da,bg:#eff1f5,spinner:#dc8a78,hl:#d20f39
--color=fg:#4c4f69,header:#d20f39,info:#8839ef,pointer:#dc8a78
--color=marker:#dc8a78,fg+:#4c4f69,prompt:#8839ef,hl+:#d20f39"
```

**PowerShell**:
```powershell
$ENV:FZF_DEFAULT_OPTS=@"
--color=bg+:#ccd0da,bg:#eff1f5,spinner:#dc8a78,hl:#d20f39
--color=fg:#4c4f69,header:#d20f39,info:#8839ef,pointer:#dc8a78
--color=marker:#7287fd,fg+:#4c4f69,prompt:#8839ef,hl+:#d20f39
--color=selected-bg:#bcc0cc
--multi
"@
```

</details>

<details>
<summary>🪴 Frappé</summary>

**Bash/Zsh**:
```sh
export FZF_DEFAULT_OPTS=" \
--color=bg+:#414559,bg:#303446,spinner:#f2d5cf,hl:#e78284 \
--color=fg:#c6d0f5,header:#e78284,info:#ca9ee6,pointer:#f2d5cf \
--color=marker:#babbf1,fg+:#c6d0f5,prompt:#ca9ee6,hl+:#e78284 \
--color=selected-bg:#51576d \
--multi"
```

**Fish**:
```sh
set -Ux FZF_DEFAULT_OPTS "\
--color=bg+:#414559,bg:#303446,spinner:#f2d5cf,hl:#e78284 \
--color=fg:#c6d0f5,header:#e78284,info:#ca9ee6,pointer:#f2d5cf \
--color=marker:#babbf1,fg+:#c6d0f5,prompt:#ca9ee6,hl+:#e78284 \
--color=selected-bg:#51576d \
--multi"
```

**Nushell**:
```nu
$env.FZF_DEFAULT_OPTS = "
--color=bg+:#414559,bg:#303446,spinner:#f2d5cf,hl:#e78284
--color=fg:#c6d0f5,header:#e78284,info:#ca9ee6,pointer:#f2d5cf
--color=marker:#f2d5cf,fg+:#c6d0f5,prompt:#ca9ee6,hl+:#e78284"
```

**PowerShell**:
```powershell
$ENV:FZF_DEFAULT_OPTS=@"
--color=bg+:#414559,bg:#303446,spinner:#f2d5cf,hl:#e78284
--color=fg:#c6d0f5,header:#e78284,info:#ca9ee6,pointer:#f2d5cf
--color=marker:#babbf1,fg+:#c6d0f5,prompt:#ca9ee6,hl+:#e78284
--color=selected-bg:#51576d
--multi
"@
```

</details>

<details>
<summary>🌺 Macchiato</summary>

**Bash/Zsh**:
```sh
export FZF_DEFAULT_OPTS=" \
--color=bg+:#363a4f,bg:#24273a,spinner:#f4dbd6,hl:#ed8796 \
--color=fg:#cad3f5,header:#ed8796,info:#c6a0f6,pointer:#f4dbd6 \
--color=marker:#b7bdf8,fg+:#cad3f5,prompt:#c6a0f6,hl+:#ed8796 \
--color=selected-bg:#494d64 \
--multi"
```

**Fish**:
```sh
set -Ux FZF_DEFAULT_OPTS "\
--color=bg+:#363a4f,bg:#24273a,spinner:#f4dbd6,hl:#ed8796 \
--color=fg:#cad3f5,header:#ed8796,info:#c6a0f6,pointer:#f4dbd6 \
--color=marker:#b7bdf8,fg+:#cad3f5,prompt:#c6a0f6,hl+:#ed8796 \
--color=selected-bg:#494d64 \
--multi"
```

**Nushell**:
```nu
$env.FZF_DEFAULT_OPTS = "
--color=bg+:#363a4f,bg:#24273a,spinner:#f4dbd6,hl:#ed8796
--color=fg:#cad3f5,header:#ed8796,info:#c6a0f6,pointer:#f4dbd6
--color=marker:#f4dbd6,fg+:#cad3f5,prompt:#c6a0f6,hl+:#ed8796"
```

**PowerShell**:
```powershell
$ENV:FZF_DEFAULT_OPTS=@"
--color=bg+:#363a4f,bg:#24273a,spinner:#f4dbd6,hl:#ed8796
--color=fg:#cad3f5,header:#ed8796,info:#c6a0f6,pointer:#f4dbd6
--color=marker:#b7bdf8,fg+:#cad3f5,prompt:#c6a0f6,hl+:#ed8796
--color=selected-bg:#494d64
--multi
"@
```

</details>

<details>
<summary>🌿 Mocha</summary>

**Bash/Zsh**:
```sh
export FZF_DEFAULT_OPTS=" \
--color=bg+:#313244,bg:#1e1e2e,spinner:#f5e0dc,hl:#f38ba8 \
--color=fg:#cdd6f4,header:#f38ba8,info:#cba6f7,pointer:#f5e0dc \
--color=marker:#b4befe,fg+:#cdd6f4,prompt:#cba6f7,hl+:#f38ba8 \
--color=selected-bg:#45475a \
--multi"
```

**Fish**:
```sh
set -Ux FZF_DEFAULT_OPTS "\
--color=bg+:#313244,bg:#1e1e2e,spinner:#f5e0dc,hl:#f38ba8 \
--color=fg:#cdd6f4,header:#f38ba8,info:#cba6f7,pointer:#f5e0dc \
--color=marker:#b4befe,fg+:#cdd6f4,prompt:#cba6f7,hl+:#f38ba8 \
--color=selected-bg:#45475a \
--multi"
```

**Nushell**:
```nu
$env.FZF_DEFAULT_OPTS = "
--color=bg+:#313244,bg:#1e1e2e,spinner:#f5e0dc,hl:#f38ba8
--color=fg:#cdd6f4,header:#f38ba8,info:#cba6f7,pointer:#f5e0dc
--color=marker:#f5e0dc,fg+:#cdd6f4,prompt:#cba6f7,hl+:#f38ba8"
```

**PowerShell**:
```powershell
$ENV:FZF_DEFAULT_OPTS=@"
--color=bg+:#313244,bg:#1e1e2e,spinner:#f5e0dc,hl:#f38ba8
--color=fg:#cdd6f4,header:#f38ba8,info:#cba6f7,pointer:#f5e0dc
--color=marker:#b4befe,fg+:#cdd6f4,prompt:#cba6f7,hl+:#f38ba8
--color=selected-bg:#45475a
--multi
"@
```

</details>

3. Enjoy!

## 💝 Thanks to

- [Sanjay Pavan](https://github.com/WitherCubes)

&nbsp;

<p align="center"><img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/footers/gray0_ctp_on_line.svg?sanitize=true" /></p>
<p align="center">Copyright &copy; 2021-present <a href="https://github.com/catppuccin" target="_blank">Catppuccin Org</a>
<p align="center"><a href="https://github.com/catppuccin/catppuccin/blob/main/LICENSE"><img src="https://img.shields.io/static/v1.svg?style=for-the-badge&label=License&message=MIT&logoColor=d9e0ee&colorA=363a4f&colorB=b7bdf8"/></a></p>
