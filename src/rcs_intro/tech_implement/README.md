# RCS技术要求和实现

* 为了实现
  * 5G消息
    * 总体
      * 技术要求
        * 图表
          * ![5g_message_tech_requirement](../../assets/img/5g_message_tech_requirement.png)
        * 文字
          * 终端
            * 支持`GSMA RCS Universal Profile v2.4`版本
              * 同时具备根据后续标准演进进行升级的能力
          * 运营商=网络要求
            * 支持`GSMA Universal Profile v2.4`版本及其后续升级版本
              *  支持终端接入并正常使用其5G消息功能
          * 行业=行业客户
            * 可向运营商申请开通`Chatbot`
              * 调用运营商提供的API
                * 实现与终端间基于`GSMA RCS Universal Profile v2.4`版本中`Standalone Message`方式的消息交互
    * 其中的
      * RCS商业富媒体消息
        * 技术要求
          * 运营商在自身网络上架设
            * `MaaP`：能力增强开放平台
              * 平台：面向企业开放API接口，以提供服务
            * `Chatbot`：聊天机器人
              * 别称：短信小程序
