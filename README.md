# Nyaa - Smoke's index torrent fetcher

## Description
This script parses the local (or online) anime release index (csv format) made by **Big Smoke**.  
And uses it to help users find the best releases on nyaa.  
The script can fuzzy match the name of anime entered, so there's no need to type it exactly or completely, try it!  
You can search in both, english and japanese name of the anime.

### Credits
Credits to JuanjoSalvador's Nyaapy. A python wrapper for scraping nyaa, you can find it [here](https://github.com/JuanjoSalvador/NyaaPy)

Credits to manintel's original nyaabag. It is the basis of my fork + expansion, it doesnt appear to be updated any more, but you can find it [here](https://github.com/manintel/nyaabag)

## Python libraries used
- Pandas  
- fuzzywuzzy  
- requests  
- lxml  

## Usage
If you don't have python3 installed, install [python3]: (https://www.python.org/).  
Run the installer.  
```
./installer
```  
After that, just run the command nyaabag
```
nyaabag
```  
