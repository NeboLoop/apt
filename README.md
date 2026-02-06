# Nebo APT Repository

Install Nebo on Debian/Ubuntu:

```bash
# Add GPG key
curl -fsSL https://nebolabs.github.io/apt/key.gpg | sudo gpg --dearmor -o /usr/share/keyrings/nebo.gpg

# Add repository
echo "deb [signed-by=/usr/share/keyrings/nebo.gpg] https://nebolabs.github.io/apt stable main" | sudo tee /etc/apt/sources.list.d/nebo.list

# Install
sudo apt update
sudo apt install nebo
```
