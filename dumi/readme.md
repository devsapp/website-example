
> 注：当前项目为 Serverless Devs 应用，由于应用中会存在需要初始化才可运行的变量（例如应用部署地区、函数名等等），所以**不推荐**直接 Clone 本仓库到本地进行部署或直接复制 s.yaml 使用，**强烈推荐**通过 `s init ${模版名称}` 的方法或应用中心进行初始化，详情可参考[部署 & 体验](#部署--体验) 。

# start-dumi-cap 帮助文档

<description>

本案例将 Dumi ，这一为 React 组件和库的开发者量身打造的文档生成器，快速创建并部署到云原生应用开发平台 CAP 。

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
   
- :fire: 通过 [云原生应用开发平台 CAP](https://devs.console.aliyun.com/applications/create?template=start-dumi-cap) ，[![Deploy with Severless Devs](https://img.alicdn.com/imgextra/i1/O1CN01w5RFbX1v45s8TIXPz_!!6000000006118-55-tps-95-28.svg)](https://devs.console.aliyun.com/applications/create?template=start-dumi-cap) 该应用。
   
</appcenter>
<deploy>
    
   
</deploy>

## 案例介绍

<appdetail id="flushContent">

本案例将 Dumi ，这一为 React 组件和库的开发者量身打造的文档生成器，快速创建并部署到云原生应用开发平台 CAP 。

Dumi 与传统的文档工具不同，Dumi 不仅仅关注于文档内容的呈现，还提供了一套完善的开发环境，让开发者能够在编写文档的同时进行组件的开发和测试。它的设计理念是“在文档中开发，在开发中写文档”，通过这种方式融合了代码和文档的撰写流程。

在 GitHub 上，Dumi 受到了许多使用 React 的中文开发者的喜爱，并且拥有一定数量的 stars。它的易用性、灵活性以及优秀的本地化支持，使其成为中文社区中非常受欢迎的组件文档工具。

Dumi 的灵活性表现在它支持多种文档格式，包括 Markdown 和 JSX，开发者可以在 Markdown 中直接使用 React 组件，实现文档和演示的即时预览。此外，Dumi 提供了丰富的主题配置选项，可以帮助开发者快速构建符合自己品牌风格的文档网站。

作为一个开箱即用的工具，Dumi 支持自动生成导航和菜单，能够根据文件结构智能生成文档网站的布局。它还内置了代码高亮、实时编辑器等功能，让文档的呈现更加直观和互动。

通过云原生应用开发平台，您只需要几步，就可以体验 Dumi ，并享受 Serverless 架构带来的降本提效的技术红利。

</appdetail>

## 使用流程

<usedetail id="flushContent">

### 查看部署的应用
本项目案例是 dumi 部署到阿里云 Serverless 平台（函数计算 FC），部署完成之后，您可以看到系统返回给您的案例地址，例如：

![图片alt](https://img.alicdn.com/imgextra/i3/O1CN01Jy0N4Z21BmOGYjobX_!!6000000006947-0-tps-1382-766.jpg)

此时，打开案例地址，就可以进入 dumi 默认的首页：

![图片alt](https://img.alicdn.com/imgextra/i3/O1CN01TxWTvM1cUDwi4CjKn_!!6000000003603-0-tps-2730-1306.jpg)


### 二次开发

您可以通过云端控制台的开发功能进行二次开发。如果您之前是在本地创建的项目案例，也可以在本地项目目录`website-dumi-v3`文件夹下，对项目进行二次开发。开发完成后，可以通过`s deploy`进行快速部署。

</usedetail>

## 注意事项

<matters id="flushContent">
</matters>
