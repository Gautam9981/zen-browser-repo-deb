# Zen Browser APT Repository

Unofficial Ubuntu/Debian apt repository for [Zen Browser](https://zen-browser.app).

## Installation Steps

### 1. Add the repository key
```bash
curl -fsSL [https://raw.githubusercontent.com/gautam9981/zen-browser-repo-deb/main/docs/key.gpg](https://raw.githubusercontent.com/gautam9981/zen-browser-repo-deb/main/docs/key.gpg) | sudo gpg --dearmor -o /etc/apt/keyrings/zen-browser.gpg

echo "deb [arch=amd64 signed-by=/etc/apt/keyrings/zen-browser.gpg] https://raw.githubusercontent.com/gautam9981/zen-browser-repo-deb/main/docs stable main" | sudo tee /etc/apt/sources.list.d/zen-browser.list

```

### 2. Install
```bash
sudo apt update
sudo apt install zen-browser
```
