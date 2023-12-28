# pic_bed
图床
# 将更改提交
git add .
git commit -m "更新图片"
# 推送至github仓库
git push
# jsdelivr加速
默认情况下，使用 GitHub 的域名访问图片加载速度较慢，有时甚至无法加载。这时我们可以使用 jsDelivr 进行免费加速。jsDelivr 是一个可靠且强大的免费加速服务，用于在网站上加载外部资源，如图片、JavaScript 库、CSS 文件和字体等。它是一个全球性的开源 CDN（内容分发网络），旨在提供高可用性和高性能的资源传送。
配置 jsDelivr 加速图床访问也非常简单。只需将“设定自定义域名”中的 URL 替换为 jsDelivr 的 URL，即可开始使用它的加速服务。例如：

https://cdn.jsdelivr.net/gh/你的GitHub仓库名
// 示例: https://cdn.jsdelivr.net/gh/PanAndy/image-resources
