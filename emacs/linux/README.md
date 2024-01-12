# Emacs config (Linux)

Do not copy anything before the melpa comment (`;; melpa`)

## This was a copy of the windows config

So, this was a copy of the windows config I had. Except, I moved to Spacemacs for Linux.

## MELPA

Melpa needs to be added before anything else. This starts at `;; mepla` and ends at the first `(package-initialize)`

## Dependencies

`[RET]` implies a return (hit your return key)

1. Solaire Mode
```sh
M-x package-install [RET] solaire-mode
```

2. Doom Themes
```sh
M-x package-install [RET] doom-themes
```

3. dashboard
Makes emacs a bit more modern

```sh
M-x package-install [RET] treemacs
```

4. Vertico
This makes the UI just a bit nicer and adds completition for stuff like `M-x`

```sh
M-x package-install [RET] vertico
```

5. Vertico Posframe

```sh
M-x package-install [RET] vertico-posframe
```

6. All The Icons

```sh
M-x package-install [RET] all-the-icons
```

7. Doom Modeline

```sh
M-x package-install [RET] doom-modeline
```

8. Spacious Padding

```sh
M-x package-install [RET] spacious-padding
```

### Golang dependencies

1. Company

```sh
M-x package-install [RET] company
```

2. Yasnippet

```sh
M-x package-install [RET] yasnippet
```

3. go-mode

```sh
M-x package-install [RET] go-mode
```
