<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="120" alt="Nest Logo" /></a>
</p>

[circleci-image]: https://img.shields.io/circleci/build/github/nestjs/nest/master?token=abc123def456
[circleci-url]: https://circleci.com/gh/nestjs/nest

  <p align="center">A progressive <a href="http://nodejs.org" target="_blank">Node.js</a> framework for building efficient and scalable server-side applications.</p>
    <p align="center">
<a href="https://www.npmjs.com/~nestjscore" target="_blank"><img src="https://img.shields.io/npm/v/@nestjs/core.svg" alt="NPM Version" /></a>
<a href="https://www.npmjs.com/~nestjscore" target="_blank"><img src="https://img.shields.io/npm/l/@nestjs/core.svg" alt="Package License" /></a>
<a href="https://www.npmjs.com/~nestjscore" target="_blank"><img src="https://img.shields.io/npm/dm/@nestjs/common.svg" alt="NPM Downloads" /></a>
<a href="https://circleci.com/gh/nestjs/nest" target="_blank"><img src="https://img.shields.io/circleci/build/github/nestjs/nest/master" alt="CircleCI" /></a>
<a href="https://discord.gg/G7Qnnhy" target="_blank"><img src="https://img.shields.io/badge/discord-online-brightgreen.svg" alt="Discord"/></a>
<a href="https://opencollective.com/nest#backer" target="_blank"><img src="https://opencollective.com/nest/backers/badge.svg" alt="Backers on Open Collective" /></a>
<a href="https://opencollective.com/nest#sponsor" target="_blank"><img src="https://opencollective.com/nest/sponsors/badge.svg" alt="Sponsors on Open Collective" /></a>
  <a href="https://paypal.me/kamilmysliwiec" target="_blank"><img src="https://img.shields.io/badge/Donate-PayPal-ff3f59.svg" alt="Donate us"/></a>
    <a href="https://opencollective.com/nest#sponsor"  target="_blank"><img src="https://img.shields.io/badge/Support%20us-Open%20Collective-41B883.svg" alt="Support us"></a>
  <a href="https://twitter.com/nestframework" target="_blank"><img src="https://img.shields.io/twitter/follow/nestframework.svg?style=social&label=Follow" alt="Follow us on Twitter"></a>
</p>
  <!--[![Backers on Open Collective](https://opencollective.com/nest/backers/badge.svg)](https://opencollective.com/nest#backer)
  [![Sponsors on Open Collective](https://opencollective.com/nest/sponsors/badge.svg)](https://opencollective.com/nest#sponsor)-->

## Description

[Nest](https://github.com/nestjs/nest) framework TypeScript starter repository.

## Project setup

```bash
$ yarn install
```

## Compile and run the project

```bash
# development
$ yarn run start

# watch mode
$ yarn run start:dev

# production mode
$ yarn run start:prod
```

## Run tests

```bash
# unit tests
$ yarn run test

# e2e tests
$ yarn run test:e2e

# test coverage
$ yarn run test:cov
```

## Deployment

When you're ready to deploy your NestJS application to production, there are some key steps you can take to ensure it runs as efficiently as possible. Check out the [deployment documentation](https://docs.nestjs.com/deployment) for more information.

If you are looking for a cloud-based platform to deploy your NestJS application, check out [Mau](https://mau.nestjs.com), our official platform for deploying NestJS applications on AWS. Mau makes deployment straightforward and fast, requiring just a few simple steps:

```bash
$ yarn install -g @nestjs/mau
$ mau deploy
```

With Mau, you can deploy your application in just a few clicks, allowing you to focus on building features rather than managing infrastructure.

## Resources

Check out a few resources that may come in handy when working with NestJS:

- Visit the [NestJS Documentation](https://docs.nestjs.com) to learn more about the framework.
- For questions and support, please visit our [Discord channel](https://discord.gg/G7Qnnhy).
- To dive deeper and get more hands-on experience, check out our official video [courses](https://courses.nestjs.com/).
- Deploy your application to AWS with the help of [NestJS Mau](https://mau.nestjs.com) in just a few clicks.
- Visualize your application graph and interact with the NestJS application in real-time using [NestJS Devtools](https://devtools.nestjs.com).
- Need help with your project (part-time to full-time)? Check out our official [enterprise support](https://enterprise.nestjs.com).
- To stay in the loop and get updates, follow us on [X](https://x.com/nestframework) and [LinkedIn](https://linkedin.com/company/nestjs).
- Looking for a job, or have a job to offer? Check out our official [Jobs board](https://jobs.nestjs.com).

## Support

Nest is an MIT-licensed open source project. It can grow thanks to the sponsors and support by the amazing backers. If you'd like to join them, please [read more here](https://docs.nestjs.com/support).

## Stay in touch

- Author - [Kamil Myśliwiec](https://twitter.com/kammysliwiec)
- Website - [https://nestjs.com](https://nestjs.com/)
- Twitter - [@nestframework](https://twitter.com/nestframework)

## License

Nest is [MIT licensed](https://github.com/nestjs/nest/blob/master/LICENSE).

## Giới thiệu về Mezon

[Mezon](https://mezon.ai/) là nền tảng hỗ trợ phát triển bot và các ứng dụng tự động hóa cho cộng đồng.

## Thêm bot vào Clan trên Mezon

Để thêm bot vào clan của bạn trên nền tảng Mezon, hãy truy cập đường dẫn sau và làm theo hướng dẫn:

👉 [Cài đặt bot vào Clan trên Mezon](https://mezon.ai/developers/bot/install/1840697773532385280)

## 💡 Features & Commands

### 1. Help
```
*help
```

### 2. Command Management
```
*command save --title="git-stash" --command="git stash apply" --desc="Apply latest stash" --category="git"
*command list --category="git"
*command detail --id=1
*command find --query="git stash"
*command update --id=1 --title="git-stash-new" --desc="New description"
*command delete --id=1
*command restore --id=1
```

### 3. Bug Management
```
*bug create --title="JWT token not refreshed" --desc="Token is not refreshed when expired" --severity="high"
*bug list --status="open"
*bug detail --id=1
*bug update --id=1 --status="in_progress"
```

### 4. Solution Management
```
*solution create --bug-id=1 --title="Fix refresh token" --desc="Add token check" --code="const checkToken = async (req, res, next) => {...}"
*solution list --bug-id=1
*solution detail --id=1
*solution update --id=1 --title="New title" --desc="New description" --code="New code"
```

### 5. Search
```
*search token
*search bugs refresh
*search solutions authentication
```

### 6. Bot Status & Control
```
*bot status
*bot deactivate
*bot activate
*bot reset
```

### 7. Ping
```
*ping
```

---

## 🛡️ Resources

- [NestJS Documentation](https://docs.nestjs.com)
- [Mezon Platform](https://mezon.ai)
- [Discord Support](https://discord.gg/G7Qnnhy)
- [NestJS Courses](https://courses.nestjs.com)
- [NestJS Devtools](https://devtools.nestjs.com)
- [Jobs Board](https://jobs.nestjs.com)

---

## 🤝 Support

Devhelp-mezon is MIT-licensed and open source.  
For support, join our [MEZON](https://mezon.ai/invite/1840697798857592832) or check the [NestJS support page](https://docs.nestjs.com/support).

---

## 👤 Author

- Huu Thien [Facebook](https://www.facebook.com/imhuuthien) | [GitHub](https://github.com/NguyenHuuThien098)
- Trung Tinh [Facebook](https://www.facebook.com/trung.tinh.30323) | [GitHub](https://github.com/tinhne)
- Devhelp-mezon contributors

---

## 📄 License

[MIT](https://github.com/nestjs/nest/blob/master/LICENSE)