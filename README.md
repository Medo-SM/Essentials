# Essentials
Essentials suff I use daily in a comptuer  

## Applications  
*IDE:* VSCode or VSCodium with extensions  (Theme: Catppuccin Mocha)  
*Notes:* Obsidian (Theme: Obsidiante, Font: JetBrains Mono)  
*Text editor:* NeoVim (With Lazy Vim)  
*Shell:* Fish  
*Terminal:* Kitty  
*Office:* LibreOffice (Heard *OpenOffice* is good enough)  
Jupyter Notebook  

## Scripts  
*VPN:* OpenVPN.

*Power Consumption on Battery:*   
```sh
# Read current voltage and current amperage
V=$(cat /sys/class/power_supply/BAT0/voltage_now)
I=$(cat /sys/class/power_supply/BAT0/current_now)

# Calculate power draw in Watts
echo "scale=2; ($V * $I) / 1000000000000" | bc
```
## Theme
*Font:* JetBrains Mono, Nord (Whichever)  
*Theme Color:* Rosepine, catppuccin Mocha (Whichever)  
