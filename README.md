# AwesomeBlogs

MJJs' awesome blogs.

这里汇总了MJJ的博客、米表、探针
## 如何加入

在`./raw`目录里新建 一个文件名为`www.yourdomain.com.json`

`www.yourdomain.com`为你的博客、米表、探针的域名，文件内容格式如下

```json
{
    "blogName": "你的站点名称", //必填
    "blogLink": "https://www.yourdomain.com",//必填，必须加https / http前缀
    "type": "tech", //必填 ["tech", "host", "life", "domain", "probe"] 中的类型
    "description": "", //站点描述可选
    "owner":"", //可选，你的Loc用户名
    "locURL":"" //可选，这里是你的Hostloc空间地址 格式为https://www.hostloc.com/space-uid-xxx.html
}
```

注，type格式为["tech", "host", "life", "domain", "probe"]中的任意一个。

tech为技术博客，host为主机博客，life为生活博客，domain为米表，probe为探针

如果你熟悉Git/GitHub操作，可以自己新建一个分支（如果你在本组织里）/或Fork修改后提交PR。

如果你不熟悉，可以打开`./raw`目录，右上角有一个Add file，你可以上传你的域名.json文件或在线编辑。提交后会自动创建分支也可以自动创建PR
也可以在[Issue](https://github.com/MJJ-Studio/AwesomeBlogs/issues/2)发送相关信息我手动添加。
