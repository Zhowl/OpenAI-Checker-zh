# OpenAI-Checker
用于检查您的IP是否可以访问OpenAI服务。

## Notice 注意事项 
**I have only created this script, and any other websites and programs for OpenAI service availability checking are not my responsibility, so please judge the accuracy by yourself. Theoretically, it is not possible to make accurate judgments through the web side, so it is recommended that you do so through a shell.**
**我只创建了这个脚本，其他用于检查OpenAI服务可用性的网站和程序不是我的责任，请自行判断准确性。理论上，通过网页端无法做出准确的判断，因此建议您通过shell进行检查。**

## Detection method 检测方法 
Our detection results come from **Cloudflare** and the accuracy is independent of this script.   
我们的检测结果来自Cloudflare，准确性与此脚本无关。

At present, there are 163 countries supported, and I will continue to update the countries and regions newly supported by OpenAI. (April 5, 2023)
目前支持163个国家和地区，我将继续更新OpenAI新支持的国家和地区。（截至2023年4月5日）

## Usage 用法

```shell
bash <(curl -Ls https://raw.githubusercontent.com/Zhowl/OpenAI-Checker-zh/main/openai.sh)
```
## Result 结果
```
> bash <(curl -Ls https://cpp.li/openai)
OpenAI Access Checker. Made by Vincent
https://github.com/missuo/OpenAI-Checker
-------------------------------------
[IPv4]
Your IPv4: 205.185.1.1 - FranTech Solutions
Your IP supports access to OpenAI. Region: US
-------------------------------------
[IPv6]
Your IPv6: 2401:95c0:f001::1 - Vincent Yang
Your IP supports access to OpenAI. Region: TW
-------------------------------------
```
## Thanks 致谢
- [Hill-98](https://github.com/Hill-98): Improved the Loc Code that can support access to OpenAI. [#1](https://github.com/missuo/OpenAI-Checker/issues/1)

## Author 作者
**OpenAI-Checker** © [Vincent Young](https://github.com/missuo), Released under the [MIT](./LICENSE) License.<br>
