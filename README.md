# paper_metadata
这个仓库收录了 bibtex 格式的期刊/会议论文元数据，其中包括标题、作者、时间、发表期刊/会议、摘要等信息。收集这些元数据使用的工具是 [Lraxer/paperinfo_crawler](https://github.com/Lraxer/paperinfo_crawler)。

[论文元数据收集情况表 (notion.site)](https://rigorous-frost-052.notion.site/d5053e59458a47769fd645be500f55ff?v=c97cacf0bdc94d9b965a29f3d5f0d473) 记录了本仓库收录的期刊/会议和包含的时间范围。

如果想添加本仓库没有收录的期刊（卷）或者会议（年份），欢迎提交PR。期刊的文件格式为`[期刊缩写][volume number].bib`，会议的文件格式为 `[会议缩写][year].bib`，其中缩写指的是 [dblp](dblp.org) 的期刊/会议URL中的名称，例如期刊 “IEEE/ACM Transactions on Networking” 的 URL 是 `https://dblp.uni-trier.de/db/journals/ton/ton32.html`，它的缩写就是 `ton`。

除了 bibtex 格式，本仓库也接受 RIS 格式。

