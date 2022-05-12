
## Core project status

| Projects                                                     | CI status                                                    | Vulnerability                                                | Code scanning                                                |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| [core](https://github.com/wangsongc/core.git)                | [![CI](https://github.com/wangsongc/core-test/actions/workflows/action2.yml/badge.svg)](https://github.com/wangsongc/core-test/actions/workflows/action2.yml) | [![Known Vulnerabilities](https://snyk.io/test/github/wangsongc/core/badge.svg)](https://snyk.io/test/github/wangsongc/core) | [![Security Rating](https://sonarcloud.io/api/project_badges/measure?project=wangsongc_core&metric=security_rating)](https://sonarcloud.io/summary/new_code?id=wangsongc_core) |
| [vue-i18n-next](https://github.com/wangsongc/vue-i18n-next.git) | [![CI](https://github.com/wangsongc/core-test/actions/workflows/action2.yml/badge.svg)](https://github.com/wangsongc/core-test/actions/workflows/action2.yml) | [![Known Vulnerabilities](https://snyk.io/test/github/wangsongc/vue-i18n-next/badge.svg)](https://snyk.io/test/github/wangsongc/vue-i18n-next) | [![Security Rating](https://sonarcloud.io/api/project_badges/measure?project=wangsongc_vue-i18n-next&metric=security_rating)](https://sonarcloud.io/summary/new_code?id=wangsongc_vue-i18n-next) |
| [router](https://github.com/wangsongc/router.git)            | [![CI](https://github.com/wangsongc/core-test/actions/workflows/action2.yml/badge.svg)](https://github.com/wangsongc/core-test/actions/workflows/action2.yml) | [![Known Vulnerabilities](https://snyk.io/test/github/wangsongc/router/badge.svg)](https://snyk.io/test/github/wangsongc/router) | [![Security Rating](https://sonarcloud.io/api/project_badges/measure?project=wangsongc_pinia&metric=security_rating)](https://sonarcloud.io/summary/new_code?id=wangsongc_pinia) |
| [pinia](https://github.com/wangsongc/pinia.git)              | [![CI](https://github.com/wangsongc/core-test/actions/workflows/action2.yml/badge.svg)](https://github.com/wangsongc/core-test/actions/workflows/action2.yml) | [![Known Vulnerabilities](https://snyk.io/test/github/wangsongc/pinia/badge.svg)](https://snyk.io/test/github/wangsongc/pinia) | [![Security Rating](https://sonarcloud.io/api/project_badges/measure?project=wangsongc_router&metric=security_rating)](https://sonarcloud.io/summary/new_code?id=wangsongc_router) |


## Tips
- 支持人工触发流水线执行
- 支持定时运行流水线
- 支持package.json文件发生变更触发流水线
- 自动获取各核心软件的版本
- 自动根据版本同步代码
- 支持安全漏洞扫描（snyk）
- 支持SonarCloud静态扫描
- 执行各核心软件的自动化测试用例
- 运行结果显示到Readme
