## 背景

腾讯云内容分发网络（CDN）预计于2022年1月25日进行技术升级，调整 CNAME，涉及以下变更：

- 中国境内/全球加速域名，在已生效 `.com` 结尾的 CNAME 基础上新增 `.cn` 结尾的 CNAME。
- 加速区域从中国境内/全球切换到中国境外时，CNAME 会从 `.cn` 后缀切换成 `.com` 后缀。

## 注意事项

技术升级后，若您的域名有两条不同的 CNAME，请关注确认新增的 CNAME，并尽快配置新的 CNAME 解析。

1. 新增 CNAME
   CNAME 变更发布后，原来已生效 CNAME 解析可正常使用，但仍建议您尽快配置新的 CNAME 解析，即 `.cn` 后缀的 CNAME。配置成功后，CDN 将不再展示原来的 CNAME。
2. 加速区域变更
   中国境内/全球域名的 CNAME 将统一采用最新的后缀：`cdn.dnsv1.com.cn`；中国境外域名的 CNAME 将统一采用后缀：`.cdn.dnsv1.com`。若您需要进行加速区域变更，相应 CNAME 后缀也会发生变更，请注意确认和修改您的 CNAME 解析。

   

