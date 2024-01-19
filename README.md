# node-template

印客学院 Node 项目模板

包含完整的 Node 项目功能，针对上手 Node 项目的同学可以进行尝试。

> 请自行安装 MongoDB 环境，此处不作赘述

## 技术选型

- **NoSQL 数据库**: [MongoDB](https://www.mongodb.com) 与 [Mongoose](https://mongoosejs.com)
- **认证**: 使用 [passport](http://www.passportjs.org)
- **数据校验**: 请求参数校验使用 [Joi](https://github.com/hapijs/joi)
- **日志**: 使用 [winston](https://github.com/winstonjs/winston) 和 [morgan](https://github.com/expressjs/morgan)
- **依赖管理**: 使用 [Pnpm](https://pnpm.io)
- **环境变量**: 使用 [dotenv](https://github.com/motdotla/dotenv) 和 [cross-env](https://github.com/kentcdodds/cross-env#readme)
- **安全**: 设置 HTTP 头部 [helmet](https://helmetjs.github.io)
- **CORS**: CORS 使用 [cors](https://github.com/expressjs/cors)
- **压缩**: gzip 压缩使用 [compression](https://github.com/expressjs/compression)
- **Git hooks**: 使用 [husky](https://github.com/typicode/husky) 和 [lint-staged](https://github.com/okonet/lint-staged)
