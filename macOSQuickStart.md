```
# Install Homebrew

/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

```
# Homebrew Commands

brew install --cask firefox
brew install --cask google-chrome
brew install --cask bitwarden
brew install --cask zed
brew install --cask visual-studio-code
brew install --cask alfred
brew install --cask obsidian
brew install --cask standard-notes
brew install --cask affinity
brew install --cask vlc
brew install --cask handbrake-app
brew install --cask obs
brew install --cask imageoptim
brew install --cask utm
brew install --cask tailscale-app
brew install --cask postman
brew install --cask transmit
brew install --cask ghostty
brew install --cask docker-desktop
brew install --cask claude
brew install --cask claude-code
brew install --cask antigravity
brew install --cask opencode-desktop
brew install --cask linear
brew install --cask localsend
brew install --cask cryptomator
brew install --cask moonlight
brew install --cask godot
brew install --cask bambu-studio
brew install --cask balenaetcher

brew install node
brew install git
brew install llama.cpp
brew install pi-coding-agent
brew install herdr
```

```
# Optional

brew install --cask microsoft-office
brew install --cask libreoffice
brew install --cask steam
brew install --cask heroic
brew install --cask audacity
brew install --cask transmit

brew install fastfetch
```

```
# Homebrew Updates

brew outdated
brew update
```

```
# OpenCode Llama.cpp Configuration

{
  "$schema": "https://opencode.ai/config.json",
  "provider": {
    "llamacpp": {
      "npm": "@ai-sdk/openai-compatible",
      "name": "llamaccp-server",
      "options": {
        "baseURL": "http://localhost:9931"
      },
      "models": {
        "ggml-org/Qwen3.8-27B-GGUF:Q8_0": {
          "name": "ggml-org/Qwen3.8-27B-GGUF:Q8_0",
          "limit": {
            "context": 90000,
            "output": 90000
          }
        }
      }
    }
  },
  "mcp": {
  }
}
```

```
# AI Models

llama serve -hf ggml-org/Qwen3.8-27B-GGUF:Q8_0
```

```
# Native Installs

mas install 497799835 (Apple Xcode)
mas install 408981434 (Apple iMovie)
mas install 424389933 (Apple Final Cut Pro)
```
