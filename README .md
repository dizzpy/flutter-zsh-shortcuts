# flutter-zsh-shortcuts 🐦⚡

A blazing-fast ⚡️ Zsh plugin with clean aliases for common Flutter commands. Make your CLI workflow smoother than a hot reload.

---

## ⚙️ Installation

### Manual (Oh My Zsh)

Clone the plugin into your custom plugin folder:

```bash
git clone https://github.com/dizzpy/flutter-zsh-shortcuts ~/.oh-my-zsh/custom/plugins/flutter-zsh-shortcuts
```

Edit your `~/.zshrc` and add `flutter-zsh-shortcuts` to the `plugins` array:

```zsh
plugins=(git flutter-zsh-shortcuts)
```

Then apply the changes:

```bash
source ~/.zshrc
```

---

## 🔤 Available Shortcuts

| Alias   | Full Command                  |
|--------:|-------------------------------|
| `f`     | `flutter`                     |
| `fc`    | `flutter clean`               |
| `fpg`   | `flutter pub get`             |
| `fpu`   | `flutter pub upgrade`         |
| `fr`    | `flutter run`                 |
| `fbapk` | `flutter build apk`           |
| `fbab`  | `flutter build appbundle`     |
| `fd`    | `flutter doctor`              |
| `ft`    | `flutter test`                |
| `fan`   | `flutter analyze`             |
| `fdv`   | `flutter devices`             |
| `fem`   | `flutter emulators`           |
| `fio`   | `open ios/Runner.xcworkspace` |
| `fup`   | `flutter upgrade`             |
| `fpl`   | `flutter pub outdated`        |

---

## 📄 License

MIT © [Dizzpy](https://github.com/dizzpy)

---

> ⭐ Star this repo if it saved your keystrokes 💻  
> 👉 [github.com/dizzpy/flutter-zsh-shortcuts](https://github.com/dizzpy/flutter-zsh-shortcuts)
