<div class="Box-sc-g0xbh4-0 bJMeLZ js-snippet-clipboard-copy-unpositioned" data-hpc="true"><article class="markdown-body entry-content container-lg" itemprop="text"><div class="markdown-heading" dir="auto"><h1 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">蓝天社交应用</font></font></h1><a id="user-content-bluesky-social-app" class="anchor" aria-label="永久链接：蓝天社交应用" href="#bluesky-social-app"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">欢迎朋友！</font><font style="vertical-align: inherit;">这是 Bluesky Social 应用程序的代码库。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">获取应用程序本身：</font></font></p>
<ul dir="auto">
<li><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">网址：</font></font><a href="https://bsky.app" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">bsky.app</font></font></a></strong></li>
<li><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">iOS：</font></font><a href="https://apps.apple.com/us/app/bluesky-social/id6444370199" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">应用商店</font></font></a></strong></li>
<li><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">安卓：</font></font><a href="https://play.google.com/store/apps/details?id=xyz.blueskyweb.app" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Play 商店</font></font></a></strong></li>
</ul>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">开发资源</font></font></h2><a id="user-content-development-resources" class="anchor" aria-label="永久链接：开发资源" href="#development-resources"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">这是一个</font></font><a href="https://reactnative.dev/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">React Native</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">应用程序，用 TypeScript 编程语言编写。</font><font style="vertical-align: inherit;">它基于</font></font><code>atproto</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">TypeScript 包（如</font></font><a href="https://www.npmjs.com/package/@atproto/api" rel="nofollow"><code>@atproto/api</code></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">）构建，其代码也是开源的，但位于</font></font><a href="https://github.com/bluesky-social/atproto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">不同的 git 存储库</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">中。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">有少量 Go 语言源代码（在 参考资料中</font></font><code>./bskyweb/</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">），用于返回 React Native Web 应用程序的 Web 服务。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">构建</font></font><a href="/bluesky-social/social-app/blob/main/docs/build.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">说明</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">是开始使用应用程序本身的好地方。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">身份验证传输协议（“AT 协议”或“atproto”）是一种去中心化社交媒体协议。</font><font style="vertical-align: inherit;">您无需</font></font><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">了解</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">AT 协议即可使用此应用程序，但它会有所帮助。</font><font style="vertical-align: inherit;">了解更多信息：</font></font></p>
<ul dir="auto">
<li><a href="https://atproto.com/guides/overview" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">概述和指南</font></font></a></li>
<li><a href="https://github.com/bluesky-social/atproto/discussions"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Github 讨论</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">👈 提问的好地方</font></font></li>
<li><a href="https://atproto.com/specs/atp" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">协议规范</font></font></a></li>
<li><a href="https://bsky.social/about/blog/3-6-2022-a-self-authenticating-social-protocol" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">关于自验证数据结构的博客文章</font></font></a></li>
</ul>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Bluesky Social 应用程序包含一组构建在整个 AT 协议框架中的模式和 API。</font><font style="vertical-align: inherit;">这些“词典”的命名空间是</font></font><code>app.bsky.*</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">贡献</font></font></h2><a id="user-content-contributions" class="anchor" aria-label="永久链接：贡献" href="#contributions"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<blockquote>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">虽然我们确实接受贡献，但我们会优先考虑高质量的问题和拉取请求。</font><font style="vertical-align: inherit;">遵守以下准则将确保更及时的审查。</font></font></p>
</blockquote>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">规则：</font></font></strong></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">我们可能不会回复您的问题或 PR。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">我们可能会在没有太多反馈的情况下关闭问题或 PR。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果我们的注意力受到 DDOS 攻击，我们可能会锁定讨论或贡献。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">我们不会为构建问题提供支持。</font></font></li>
</ul>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">指南：</font></font></strong></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请在提交新问题之前检查现有问题。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在提交 PR 之前提出一个问题并给予一些时间进行讨论。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">远离 PR，例如...
</font></font><ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">将“帖子”更改为“双向飞碟”。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">重构代码库，例如用 redux 等替换 mobx。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">无需事先讨论即可添加全新功能。</font></font></li>
</ul>
</li>
</ul>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请记住，我们为广泛的用户社区提供服务。</font><font style="vertical-align: inherit;">我们每天都会不断地问“哪一个是我们的首要任务”。</font><font style="vertical-align: inherit;">如果您提交的 PR 写得很好，可以简洁地解决问题，那么这就是一个了不起的贡献。</font><font style="vertical-align: inherit;">否则，尽管我们很乐意接受您的想法和贡献，但我们确实没有足够的带宽。</font><font style="vertical-align: inherit;">这就是分叉的目的！</font></font></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">分叉指南</font></font></h2><a id="user-content-forking-guidelines" class="anchor" aria-label="永久链接：分叉指南" href="#forking-guidelines"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">我们祝福您🪄✨ 能够分叉这个应用程序！</font><font style="vertical-align: inherit;">然而，当你给用户一个分叉时，向用户明确说明是非常重要的。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请务必：</font></font></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">更改存储库和 UI 中的所有品牌，以明显区别于 Bluesky。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">将任何支持链接（反馈、电子邮件、服务条款等）更改为您自己的系统。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">将任何分析或错误收集系统替换为您自己的系统，这样我们就不会感到非常困惑。</font></font></li>
</ul>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">安全披露</font></font></h2><a id="user-content-security-disclosures" class="anchor" aria-label="永久链接：安全披露" href="#security-disclosures"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果您发现任何安全问题，请发送电子邮件至</font></font><a href="mailto:security@bsky.app"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">security@bsky.app</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font><font style="vertical-align: inherit;">该电子邮件会自动抄送给整个团队，我们会立即回复。</font></font></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您是一位有兴趣在 atproto 上进行构建的开发人员吗？</font></font></h2><a id="user-content-are-you-a-developer-interested-in-building-on-atproto" class="anchor" aria-label="永久链接：您是一位有兴趣在 atproto 上进行构建的开发人员吗？" href="#are-you-a-developer-interested-in-building-on-atproto"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Bluesky 是一个基于 AT 协议构建的开放社交网络，AT 协议是一种灵活的技术，永远不会将开发人员排除在他们帮助构建的生态系统之外。</font><font style="vertical-align: inherit;">借助 atproto，第三方可以通过自定义源、联合服务、客户端等与第一方一样无缝。</font></font></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">许可证（麻省理工学院）</font></font></h2><a id="user-content-license-mit" class="anchor" aria-label="永久链接：许可证（麻省理工学院）" href="#license-mit"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请参阅</font></font><a href="/bluesky-social/social-app/blob/main/LICENSE"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">./LICENSE</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">以获取完整许可证。</font></font></p>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">聚苯乙烯</font></font></h2><a id="user-content-ps" class="anchor" aria-label="永久链接： PS" href="#ps"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">我们❤️您以及您支持我们的所有方式。</font><font style="vertical-align: inherit;">感谢您让 Bluesky 成为一个美好的地方！</font></font></p>
</article></div>
