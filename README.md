# awesome-pii

Awesome-PII is a tool collection related to detecting, extracting, and removing PII from data.

# Regex

The [regexes.txt](regexes.txt) schema may change. I may change the schema later for future versions.

Regexes are tested with ruby 2.5.9 on [Rubular](https://rubular.com/).

Regexes are downcase sensitive. (meaning downcase text before using them)

Regexes are incomplete. Pull Requests welcome.

## Categories

- Phone
  - US
- Email
- Socials
  - Instagram
  - TikTok
  - Snapchat
  - LinkedIn
  - WhatsApp
  - Telegram
  - Twitter
  - Facebook
- ID card
  - Social Security Number
- Internet
  - IP Address
  - Domain Name
- Personal
  - Date of Birth (US)
  - Race
  - Religion

## Roadmap

- Regexes
    - [ ] Implement regex groups to extract parts of regex
    - [ ] (ongoing) add support for obsfuncation (e.g. "s.c." means snapchat)
    - [ ] regexes with PII
    - [ ] remove PII from text (with ChatGPT)

- Images
    - [ ] Image PII (with OCR)
    - [ ] Image PII removal (with OCR and Stable Diffusion)

[ ] Multi-language support

## Special Thanks
- [Regular Expressions to Match Social Media Profiles](https://github.com/lorey/social-media-profiles-regexs)
- [Spark Start](https://sparkstart.io)
- [Author](https://kcoleman.me)
- Everyone who stars this repo