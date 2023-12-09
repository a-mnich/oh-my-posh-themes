# oh-my-posh Themes
This is a collection of customised oh my posh themes.  
All available themes can be found in the [themes](./themes) folder.
  
## Custom Font
To ensure that the custom themes display icons correctly it's necessarry to set a custom font in the Windows Terminal and VSCode Terminal.  
These themes have been testet with the `DejaVuSansM Nerd Font Mono` font.

 ### Windows Terminal Configuration
 - set the default terminal font face value for profiles
  ```json
    "profiles": 
    {
        "defaults": 
        {
            "font": 
            {
                "face": "DejaVuSansM Nerd Font Mono"
            }
        }
    }
```
### VSCode Configuration
- open Settings
- search for "Terminal Font" (terminal.integrated.fontFamily)
- set to custom font name (e.g. "DejaVuSansM Nerd Font Mono")
