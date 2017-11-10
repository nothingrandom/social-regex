# social-regex
> Regex patterns for social media profiles

This README file lists regex (regular expressions) to match social media profile / platform URLs. How you use this repo is up to you. Only exact profile urls are matched.

## Linkedin
`^(http(s)?:\/\/)?(www\.)?linkedin\.com\/(in|profile|pub)\/([A-z 0-9 _ -]+)\/?$`

RegEx for public URLs. Prefixed by `/in/`, `/profile/`, or `/pub/`. Alphanumerical chacters, hyphens and underscores.

## GitHub
`^(http(s)?:\/\/)?(www\.)?github\.com\/(?!-)[A-z 0-9 -]{1,39}[^-]\/?$`

RegEx for usernames. 39 alphanumerical characters. Hyphens are allowed, but usernames cannot start or end with one.

## Twitter
`^(http(s)?:\/\/)?(www\.)?twitter\.com\/[A-z 0-9 _]{1,15}\/?$`

RegEx for usernames. 15 alphanumerical characters and underscores but no other special characters.

## Reddit
`^(http(s)?:\/\/)?(www\.)?reddit\.com\/user\/[A-z 0-9 _ -]{3,20}\/?$`

RegEx for usernames. 3-20 alphanumberical characters, dashes, and underscores. Prefix of `/user/`.

TODO:
- Facebook
- Instagram
- Dribbble
- Spotify
- Skype
- SoundCloud
- Google Plus
- Telegram
- Phone numbers
- Email
- Medium
- YouTube
- StackOverflow
- Vimeo
- Reddit
- Keybase
- Pinterest
