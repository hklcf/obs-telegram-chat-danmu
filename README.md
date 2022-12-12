# obs-telegram-chat-danmu
[![GitHub issues](https://img.shields.io/github/issues/hklcf/obs-telegram-chat-danmu.svg)](https://github.com/hklcf/obs-telegram-chat-danmu/issues)
[![GitHub forks](https://img.shields.io/github/forks/hklcf/obs-telegram-chat-danmu.svg)](https://github.com/hklcf/obs-telegram-chat-danmu/network)
[![GitHub stars](https://img.shields.io/github/stars/hklcf/obs-telegram-chat-danmu.svg)](https://github.com/hklcf/obs-telegram-chat-danmu/stargazers)
[![GitHub license](https://img.shields.io/github/license/hklcf/obs-telegram-chat-danmu.svg)](https://github.com/hklcf/obs-telegram-chat-danmu/blob/master/LICENSE)
[![Twitter](https://img.shields.io/twitter/url/https/github.com/hklcf/obs-telegram-chat-danmu.svg?style=social)](https://twitter.com/intent/tweet?text=Wow:&url=https%3A%2F%2Fgithub.com%2Fhklcf%2Fobs-telegram-chat-danmu)

Add Telegram Chat in OBS

Stream your Telegram group messages in OBS without software installation

## Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites
- Telegram BOT [authentication token](https://core.telegram.org/bots/features#botfather)
- Telegram Group ID (You can use [Telegram Bot Raw](https://t.me/rawdatabot) to get the group id)
- [OBS Studio](https://obsproject.com/)

## Usage
1. Create a new bot via [@BotFather](https://t.me/botfather)
2. Disable privacy mode on your bot (https://core.telegram.org/bots/features#privacy-mode)
3. Add the bot to your group
4. Add [Telegram Bot Raw](https://t.me/rawdatabot) to your group to get group id (chat id)

![image](https://user-images.githubusercontent.com/410302/206939432-0c210e8c-4ed7-419e-ae47-78ed356de4d2.png)

5. Clone this project
6. Edit [`edanmu.html`](edanmu.html), update your `API_KEY` `BOT_USERNAME` `GROUP_ID`

![image](https://user-images.githubusercontent.com/410302/206938427-cf1d3a53-bea2-43d7-8eb6-8d7b2a6b7f52.png)

7. Open OBS Studio, add [Browser Source](https://obsproject.com/kb/browser-source), set `Local file` to On
8. Select [`edanmu.html`](edanmu.html) on Local file
9. Enjoy☺️

## Contributing
Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning
We use [SemVer](https://semver.org/) for versioning. For the versions available, see the [tags on this repository](../../tags).

## Authors
* **HKLCF** - *Initial work* - [HKLCF](https://github.com/hklcf)

See also the list of [contributors](../../contributors) who participated in this project.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details
