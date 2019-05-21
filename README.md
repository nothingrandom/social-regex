# social-regex
> Regex patterns for social media profiles

This README file lists regex (regular expressions) to match social media profile / platform URLs.

## GitHub
### Usernames
`^(http(s)?:\/\/)?(www\.)?github\.com\/(?!-)(?:[A-z0-9-]){1,39}[^-]\/?$`

Rules:
- Max 39 alphanumerical characters
- Hyphens are allowed, but usernames cannot start or end with one

[regex101 example](https://regex101.com/r/cjlmSt/1)

## Reddit
### Usernames
`^(http(s)?:\/\/)?(www\.)?reddit\.com\/user\/(?:[A-Za-z0-9_-]{3,20})\/?$`

Rules:
- Prefixed by `/user/`
- 3-20 alphanumberical characters
- Hyphens
- Underscores

[regex101 example](https://regex101.com/r/9DERwM/1)

## Instagram
### Usernames
`^((http(s)?)?:\/\/?(www\.)?)?instagram\.com\/([A-Za-z0-9_](?:(?:[A-Za-z0-9_]|(?:\.(?!\.))){0,28}(?:[A-Za-z0-9_]))?)\/?$`

Rules:
- Max 30 alphanumerical characters
- Underscores
- Periods are allowed in singles (. not ..), username cannot start or end with one

[regex101 example](https://regex101.com/r/GaJdb9/5)

## Linkedin
### Public URLS
`^(http(s)?:\/\/)?(www\.)?linkedin\.com\/(in|profile|pub)\/([A-z 0-9 _ -]+)\/?$`

Rules:
- Prefixed by `/in/`, `/profile/`, or `/pub/`
- Alphanumerical
- Hyphens
- Underscores

## Twitter
### Usernames
`^(http(s)?:\/\/)?(www\.)?twitter\.com\/[A-z 0-9 _]{1,15}\/?$`

Rules:
- 15 alphanumerical characters
- Underscores

TODO:
- Facebook
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
