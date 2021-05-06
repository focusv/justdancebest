# justdancebest (JDCS)
Just Dance Custom Server API, used for Just Dance Best.

**JDCS (Just Dance Custom Service)** is a mock-up of Just Dance Unlimited (JMCS) servers by Ubisoft.

**Just Dance Unlimited** is a online-subscription service created by Ubisoft back in 2015 for Just Dance 2016-2021 and on for Xbox One, Xbox Series, PS4, PS5, Wii U, Nintendo Switch, PC and Google Stadia.

## Requirements
- [Node.js](https://nodejs.org/)
- A server to host (duh)
## How to install

- Use `git clone https://github.com/heyimyunyl/justdancebest.git` or download the repo as a ZIP file directly.
- Once you are done, go into `justdancebest` folder and run `npm i` to install all packages that are required.
- After that, you can run the server by `node jdcs.js`.

### Configuration
There are 3 types of configuration in Just Dance Best. 
- **Local Settings**, where all local JSONs are being returned
- **Settings**, where all server/game configurations are stored
- **Environment file** where the server's main config such as maps folder, server port are in
- **JDCS object** in jdcs.js, where all UbiServices and official JMCS server urls are in.

## License
There is no license for this project currently.

#### Discord server
[Join our Discord server!](https://discord.gg/FkSpSmXrwT)
