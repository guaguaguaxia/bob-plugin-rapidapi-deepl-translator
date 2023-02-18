RapidAPI DeepL Translator Bob Plugin
------------------------------------

# 简介

众所周知，DeepL 是当下翻译效果最好的（不要跟我讲 ChatGPT，它太太太慢了），同时众所周知，作为身在中国大陆的中国人是很难使用 DeepL API 的，
因为 DeepL 不支持中国的信用卡，在淘宝买的话，¥40 只能买一个月的 DeepL API Free 方案，而且每个月只能翻译 500,000 个字符，而且每个月都要记得去淘宝买一次，性价比太低了！


当然 OpenL 也是可以用的，但是它的 DeepL API 太贵了，首先 400,000 字符需要 ¥39.19，同时 DeepL API 要 1.4x 的计费倍率，换算下来 500,000 字符的 DeepL 翻译每个月需要 ¥68.58，的确是有点恐怖了。


功夫不负有心人，我终于在 RapidAPI 找到了一个封装了 DeepL 的 API —— [DeepL Translator](https://rapidapi.com/splintPRO/api/deepl-translator)，速度很不错，价格也很实惠（免费版每个月 500,000 个字符，月费 $3.99 的版本每个月 15,000,000 个字符），
重点是可以用中国信用卡注册！！！


所以我专门开发了此插件，我甚至还实现了指定多 API KEY (用英文逗号分割) 来实现多个账号的字符数额度相加和负载均衡避免触发速率限制（免费版 30 requests per minute，月费 $3.99 版本 35 requests per minute），理论上你可以准备多个信用卡注册多个账号薅免费版的羊毛组成一个免费的大字符额度高速率限制的 DeepL API，但是极其不建议！！！**尊重开发者的劳动成果是每一个文明人的责任！！！**

# 安装

1. 安装 [Bob](https://bobtranslate.com/guide/#%E5%AE%89%E8%A3%85)() (版本 >= 0.50)
2. 下载此 Bob 插件: [rapidapi-deepl-translator.bobplugin](https://github.com/yetone/bob-plugin-rapidapi-deepl-translator/releases)
3. 插件安装: [Bob 插件安装文档说明](https://bobtranslate.com/guide/advance/plugin.html#%E5%AE%89%E8%A3%85%E6%8F%92%E4%BB%B6)

# 使用截图

![](https://user-images.githubusercontent.com/1206493/219876934-e0ed170e-faed-4fc5-801b-e16660ffbc84.gif)
