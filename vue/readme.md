
> 注：当前项目为 Serverless Devs 应用，由于应用中会存在需要初始化才可运行的变量（例如应用部署地区、函数名等等），所以**不推荐**直接 Clone 本仓库到本地进行部署或直接复制 s.yaml 使用，**强烈推荐**通过 `s init ${模版名称}` 的方法或应用中心进行初始化，详情可参考[部署 & 体验](#部署--体验) 。

# start-vue-cap 帮助文档

<description>

本案例将 Vue 框架示例快速创建并部署到云原生应用开发平台。其简洁的API、高效的性能和良好的生态系统，在前端开发领域得到了广泛的应用。

</description>


## 资源准备

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
   
- :fire: 通过 [云原生应用开发平台 CAP](https://cap.console.aliyun.com/template-detail?template=start-vue-cap) ，[![Deploy with Severless Devs](https://img.alicdn.com/imgextra/i1/O1CN01w5RFbX1v45s8TIXPz_!!6000000006118-55-tps-95-28.svg)](https://cap.console.aliyun.com/template-detail?template=start-vue-cap) 该应用。
   
</appcenter>
<deploy>
    
   
</deploy>

## 案例介绍

<appdetail id="flushContent">

本案例将 Vue 框架示例快速创建并部署到云原生应用开发平台 CAP 。

</appdetail>







## 使用流程

<usedetail id="flushContent">

### 查看部署的应用
本项目案例是 Vue 部署到云原生应用开发平台 CAP ，部署完成之后，您可以看到系统返回给您的案例地址。

![](https://img.alicdn.com/imgextra/i3/O1CN013LVkct1tRnQXPm2uu_!!6000000005899-0-tps-1292-131.jpg)

此时，打开案例地址，就可以进入 Vue 默认的首页。

</usedetail>

## 二次开发指南

<development id="flushContent">

在初始化项目时，需要绑定代码仓库，CAP平台会自动配置代码仓库的Webhook。当仓库对应的分支有任何提交时，CAP平台会收到Webhook推送，并自动完成构建与部署。

您也可以通过云端控制台 webIDE 的开发功能进行二次开发。

</development>






