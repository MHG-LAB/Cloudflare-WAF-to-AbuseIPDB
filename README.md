# Cloudflare WAF to AbuseIPDB

## 它可以干嘛

从 Cloudflare Graphql API 获取被 Cloudflare WAF 拦截(阻止/托管质询)的 IP 并提交给 AbuseIPDB

## 它要怎么用

请不要 fork 此仓库！！ 使用模板导入 [Use this template](https://github.com/MHG-LAB/Cloudflare-WAF-to-AbuseIPDB/generate) !! 瞎点fork按钮发送垃圾 PR 将直接提交到 GitHub 黑名单中(

修改 [Actions]

Actions 环境变量：
- `CLOUDFLARE_ZONE_ID`: Cloudflare ZONE ID
- `CLOUDFLARE_API_KEY`: Cloudflare API Key
- `CLOUDFLARE_EMAIL`: Cloudflare Email
- `ABUSEIPDB_API_KEY`: AbuseIPDB API Key

