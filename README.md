# LANraragi_Plugin


## addEtagCNMetadata
根据插件addEhentaiMetadata改写
https://github.com/chu-shen/LANraragi/blob/feat-ratingAndcomment/lib/LANraragi/Plugin/Scripts/addEhentaiMetadata.pm
该插件调用Ehentai插件获取缺失source tag的档案的元数据，可惜默认是英文的，所以我改了一下，调用ETagCN插件直接获取中文的元数据。

插件数据库与ETagCN插件一致，参考https://github.com/zhy201810576/ETagCN

