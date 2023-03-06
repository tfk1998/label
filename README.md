# 运营标签系统
#### 开发技术:

```JS
前端：Vue.js全家桶+vue-property-decorator+TypeScript
element+Sass+mock.js+moment.js+echarts、vuedraggable、sortTable、papaparse
```

#### 项目描述：

`标签系统的价值在与帮助运营团队高效、安全、便捷的筛选设备、商户和用户等实体，助力实现精细化运营。保障数据安全，保障设备筛选能力稳定可靠，便于业务系统对接通过标签系统对接升级系统，消除人工筛设备的流程。对业务方提供标签管查询能力、数据包投放能力、在线查询服务、自助分析能力，主要模块有：模块数据首页仪表盘、场景管理、标签管理、数据包管理、设备标签预览、自定义分析。`

#### 岗位职责：
- 负责模块
  - 标签管理
  - 自定义分析
  - 标签预览
- 主要负责标签系统需求调研、需求评审、http协议设计、UI设计、评审
- 负责所有模块页面开发，工程化配置、前端项目架构搭建
- 对用户体验、缓存、dom、http、代码等进行优化，编写测试用例对测试
- 测试环境的项目进行黑盒测试，保证发布质量，贡献出灵活、复用性高的UI业务组件及工具类

#### 项目技术：
- 使用div+css+Sass+element编写静态页面,实现页面布局。
- 使用 ES Module、TypeScript 对项目中的公共方法进行提炼封装、请求封装。
- 使用 vue-router.beforeEach+vuex 配合后台接口做全局模块权限管理。
- 使用 vue-property-decorator+TypeScript封装公共组件、业务组件。
- 使用 codemirror 封装web端在线代码编辑器，实现在线编辑SQL输出表内容。
- 使用 Vuex对用户信息、场景等公共数据进行管理。
- 使用keepalive 对每个页面进行动态缓存。
- 使用directive 对常用的事件封装成Vue快捷自定义指令。
- 使用echarts 做标签分布、维度动态下钻进行多维分析。
- 使用 vue mixins 做全局数据加载处理进行和校验。
- 使用papaparse 对标签创建修改人工打标导入、导出csv文件。
- 使用 vue-router、vuex  实现动态路由+权限管理。
- 使用类的形式对各模块请求统一封装。对axios二次封装并处理各种异常。
