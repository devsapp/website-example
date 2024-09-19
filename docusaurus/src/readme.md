
> 注：当前项目为 Serverless Devs 应用，由于应用中会存在需要初始化才可运行的变量（例如应用部署地区、函数名等等），所以**不推荐**直接 Clone 本仓库到本地进行部署或直接复制 s.yaml 使用，**强烈推荐**通过 `s init ${模版名称}` 的方法或应用中心进行初始化，详情可参考[部署 & 体验](#部署--体验) 。

# start-docusaurus-cap 帮助文档

<description>

本案例将 Docusaurus ，这一使用者广泛的网站生成器，快速创建并部署到云原生应用开发平台 CAP。

</description>


## 前期准备

使用该项目，您需要有开通以下服务并拥有对应权限：

<service>



| 服务/业务 |  权限  | 相关文档 |
| --- |  --- | --- |
| 函数计算 |  AliyunFCFullAccess | [帮助文档](https://help.aliyun.com/product/2508973.html) [计费文档](https://help.aliyun.com/document_detail/2512928.html) |
| 日志服务 |  AliyunFCServerlessDevsRolePolicy | [帮助文档](https://help.aliyun.com/zh/sls) [计费文档](https://help.aliyun.com/zh/sls/product-overview/billing) |

</service>

<remark>



</remark>

<disclaimers>



</disclaimers>

## 部署 & 体验

<appcenter>
   
- :fire: 通过 [云原生应用开发平台 CAP](https://devs.console.aliyun.com/applications/create?template=start-docusaurus-cap) ，[![Deploy with Severless Devs](https://img.alicdn.com/imgextra/i1/O1CN01w5RFbX1v45s8TIXPz_!!6000000006118-55-tps-95-28.svg)](https://devs.console.aliyun.com/applications/create?template=start-docusaurus-cap) 该应用。
   
</appcenter>
<deploy>
    
   
</deploy>

## 案例介绍

<appdetail id="flushContent">

本案例将 Docusaurus ，这一使用者广泛的网站生成器，快速创建并部署到云原生应用开发平台 CAP 。

Docusaurus 是一个为技术文档和博客推出的现代静态网站生成器。它提供了一种轻量级的方法来创建和托管由 Markdown 驱动的文档网站。Docusaurus 的设计理念是将注意力集中在编写内容上，而非维护复杂的网站架构。它的直观性使得启动和部署项目变得极其简单，而且可以轻松地与版本控制工具（如Git）集成，从而优化文档协作流程。

在 GitHub 上，Docusaurus 因其易用性、扩展性和社区支持而受到了广泛的认可，拥有大量 stars。它被众多知名开源项目采用，如React Native、Jest 和 Redux 等，证明了其在技术文档领域的受欢迎程度和适用性。

Docusaurus 预设了响应式的布局，意味着你的文档网站将会在各种设备上呈现良好的阅读体验。另外，它内置了 Algolia 搜索支持，使得读者能够快速找到关键信息。Docusaurus 的版本控制功能也是一个亮点，它允许开发者轻松管理不同版本的文档，为用户提供多个版本的参考资料。

通过云原生应用开发平台，您只需要几步，就可以体验 Docusaurus ，并享受 Serverless 架构带来的降本提效的技术红利。

</appdetail>

## 使用流程

<usedetail id="flushContent">

### 查看部署的应用
本项目案例是 docusaurus 部署到阿里云 Serverless 平台（函数计算 FC），部署完成之后，您可以看到系统返回给您的案例地址，例如：

![图片alt](https://img.alicdn.com/imgextra/i1/O1CN010c3YHL1a0nGVe2ZyK_!!6000000003268-0-tps-1196-584.jpg)

此时，打开案例地址，就可以进入 docusaurus 默认的首页：

![图片alt](https://img.alicdn.com/imgextra/i3/O1CN01SAgalQ1fW09cM1X7i_!!6000000004013-2-tps-1263-664.png)

</usedetail>

## 注意事项

<matters id="flushContent">
</matters>
