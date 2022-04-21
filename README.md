# Cloudflare WAF to AbuseIPDB

## 它可以干嘛

从 Cloudflare Graphql API 获取被 Cloudflare WAF 拦截(阻止/托管质询)的 IP 并提交给 AbuseIPDB

## 它要怎么用

请不要 fork 此仓库！！ 使用模板导入 [Use this template](https://github.com/MHG-LAB/Cloudflare-WAF-to-AbuseIPDB/generate) !! 瞎点fork按钮发送垃圾 PR 将直接提交到 GitHub 黑名单中(

修改 [Actions](https://github.com/MHG-LAB/Cloudflare-WAF-to-AbuseIPDB/blob/main/.github/workflows/report.yml#L11)

Actions 环境变量：
- `CLOUDFLARE_ZONE_ID`: Cloudflare ZONE ID
- `CLOUDFLARE_API_KEY`: Cloudflare API Key
- `CLOUDFLARE_EMAIL`: Cloudflare Email
- `ABUSEIPDB_API_KEY`: AbuseIPDB API Key

## 吐槽

Cloudflare 的 API 不知道什么时候做了更改，找到文档时发现 PAYLOAD 需要使用 Graphql....

## Support

[AbuseIPDB](https://www.abuseipdb.com/) : AbuseIPDB is an IP address blacklist for webmasters and sysadmins to report IP addresses engaging in abusive behavior on their networks

[Cloudflare](https://www.cloudflare.com/)

[Cloudflare Block Bad Bot Ruleset](https://github.com/XMD0718/cloudflare-block-bad-bot-ruleset)

## AbuseIPDB Contributor 

<a href="https://www.abuseipdb.com/user/82131" title="AbuseIPDB is an IP address blacklist for webmasters and sysadmins to report IP addresses engaging in abusive behavior on their networks">
	<img src="https://www.abuseipdb.com/contributor/82131.svg" alt="AbuseIPDB Contributor Badge" style="width: 401px;">
</a>

## License

[MIT](https://github.com/MHG-LAB/Cloudflare-WAF-to-AbuseIPDB/blob/main/LICENSE)