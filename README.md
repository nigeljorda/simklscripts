# Simkl Scripts

## Scripts to make your life easier on Simkl

This repository provides various Python scripts and userscripts to make your Simkl.com life more funny
## Scripts

### LetterboxdtoSimkl
- **exportLetterboxdHistory**: Export your watched movies from Letterboxd into a .csv file.
- **importLetterboxdtoSimkl**: Import watched movies from Letterboxd into Simkl. **First use exportLetterboxdHistory to get your watched movies from Letterboxd**

### Userscripts
- **LetterboxdReviews**: Imports the most 20 Popular Letterboxd reviews for each movie on Simkl.com. You have to reload a page to see the reviews! (Use it with Tampermonkey)


## Installation

Make sure to create a API applicatio at: https://simkl.com/settings/developer/ to retrieve a Client ID to fill in the config.ini
Also get your own https://www.themoviedb.org/settings/api to fill in # TMDB API Key (replace with your TMDB API key)
TMDB_API_KEY = 'YOURAPIKEY' in the importLetterboxdtoSimkl.py file.

```bash
pip3 install beautifulsoup4 pandas requests

###Forks are fine but credits to my work would be nice!
