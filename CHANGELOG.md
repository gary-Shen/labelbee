# Changelog

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

## [1.7.0](https://github.com/open-mmlab/labelbee/compare/v1.6.0...v1.7.0) (2022-06-23)


### Features

* [lb-component] Add TagToolInstanceAdaptor to implement toolInstance ([85cd646](https://github.com/open-mmlab/labelbee/commit/85cd64694638e17efee32fdd841b9be7dd281dbf))
* [lb-component] Implement keydown event for tagging ([5f441fe](https://github.com/open-mmlab/labelbee/commit/5f441feb0029cbcf704110c183d81dd8c1f67480))
* [lb-components] Support and export 'VideoPlayer' ([0aea748](https://github.com/open-mmlab/labelbee/commit/0aea748991389933d4d7965af3e21345fffbffa4))
* [lb-components] VideoTagTool Support i18n on hotkeys ([8216f5d](https://github.com/open-mmlab/labelbee/commit/8216f5dfb8ed0d723ed9aa5c2e15bdbbc4edf682))
* [lb-demo] Support the use of VideoPlayer ([7ab27c2](https://github.com/open-mmlab/labelbee/commit/7ab27c2df4a794f0a5695768888da1a4a3b574be))
* Add FileInvalid and FileException components, show operation on videoTagTool ([442318c](https://github.com/open-mmlab/labelbee/commit/442318cf1e38259b8314f538d0e91ada2329168d))
* Add pageChange add stepChange callback ([ea20140](https://github.com/open-mmlab/labelbee/commit/ea201407655675ae48c7e9bcd21e7e530c3d7b7c))
* add renderEnhance function ([009a734](https://github.com/open-mmlab/labelbee/commit/009a73498873ff489f0a2f44ad9bf6ca33a4a771))
* AnntoationView-Polygon adds keypoint showing ([f414dab](https://github.com/open-mmlab/labelbee/commit/f414dab0cec2ce09f14cf7af22272632d9717c17))
* Implement pushHistory on TagToolInstanceAdaptor ([cadd8c7](https://github.com/open-mmlab/labelbee/commit/cadd8c717e22f598325f5589ad9208862d3a1773))
* Init result on state while TagToolInstanceAdaptor mounted ([954ba29](https://github.com/open-mmlab/labelbee/commit/954ba293b21c9bf5110ec7d8c6c5bec0ad0dd5bd))
* PointTool emits messageSuccess when it adsorb edge ([e643dca](https://github.com/open-mmlab/labelbee/commit/e643dca72a7e3bcff45549d63ac3c2af67bb7dc2))
* PolygonTool add combining operation ([56bb126](https://github.com/open-mmlab/labelbee/commit/56bb126da98965afeb1cad414094fea905b774c4))
* PolygonTool add cutting operation ([cbc33ac](https://github.com/open-mmlab/labelbee/commit/cbc33ac68b2b66ca5a6b8d091098a77d0daedc6b))
* Rename Image Error to FileError and replace life cycle fn 'componentWillUnmount' ([3063f7c](https://github.com/open-mmlab/labelbee/commit/3063f7cad8cff6366a209f13ab2b3daca4ba5a06))
* Support batch data acquisition ([2d26c2d](https://github.com/open-mmlab/labelbee/commit/2d26c2d252bdb4c6b73b016f6833fb2b8d24dfe1))
* TagToolInstanceAdaptor export fn: 'setValid' and getter 'valid' ([e73ca3c](https://github.com/open-mmlab/labelbee/commit/e73ca3c64cdf46cafbd235494c9e7c84aaeaa8ba))
* VideoPlayer playPause while video clicked ([c003449](https://github.com/open-mmlab/labelbee/commit/c003449ae7c55428b27abbc7773c98a33da55933))
* VideoTagToolInstance support exporting videoMetaData on exportData ([1b2166c](https://github.com/open-mmlab/labelbee/commit/1b2166c7b5cf7b756396ca7a681f463d099e29b3))


### Bug Fixes

* `GetCloestPoint` function needs to be added `hasClosed` ([1581ed1](https://github.com/open-mmlab/labelbee/commit/1581ed1614cd5c43e432afe18dbbfb78748f6748))
* Click next step jump to the first page ([83a0335](https://github.com/open-mmlab/labelbee/commit/83a033520547dae0d9e57a0a8a338a3c4f2dcfca))
* fix eslint errors ([f20b3a3](https://github.com/open-mmlab/labelbee/commit/f20b3a32572950665e20e670b1531ea8a3697d31))
* Fix problems from comment ([145d20a](https://github.com/open-mmlab/labelbee/commit/145d20a7b1afd45521d41eeb88f8122e83e26e4b))
* Fix the pr error ([4a2fa2b](https://github.com/open-mmlab/labelbee/commit/4a2fa2be649605a0378943e641863b14307d120c))
* Fix the wrong internationalization issue ([3a78658](https://github.com/open-mmlab/labelbee/commit/3a7865844d4560f4f36bb454adf9a2655e2fa784))
* PointTool for reference only to display polygons and lines ([b177dd2](https://github.com/open-mmlab/labelbee/commit/b177dd2143ca62754512bb6e0e2607102c44abc0))
* PointTool is not allowed drawing outside the target when 'drawOutsideTarget' config is false ([2668cd7](https://github.com/open-mmlab/labelbee/commit/2668cd7c5f421b9ae9f8ae9d5c169cdeeb59df43))
* remove ts-ignore ([9065c34](https://github.com/open-mmlab/labelbee/commit/9065c34421d8cbd152eba760233cf452c31e360f))
* TagTool doesn't need to rotate ([c20576c](https://github.com/open-mmlab/labelbee/commit/c20576ce64b97f8610ca1810bac94289ce87a61b))
* Temporarily supports the use of the react AnnotationTool ([004e851](https://github.com/open-mmlab/labelbee/commit/004e851b632f339ee7fe7dd73a2bcde9cfda84d2))
* Update eslint error ([6941977](https://github.com/open-mmlab/labelbee/commit/6941977ab01476aa764d91fa9b60589fc51853d6))
* VideoPlayer have error status while src changed ([0bbf25c](https://github.com/open-mmlab/labelbee/commit/0bbf25c4492e59b3d634849290fe65ae729fa438))
* VideoTag emitEvent after clear result ([865575d](https://github.com/open-mmlab/labelbee/commit/865575da1a0928736f1e61cad588e5bca0d613fa))

## [1.6.0](https://github.com/open-mmlab/labelbee/compare/v1.5.0...v1.6.0) (2022-05-16)


### Features

* Add a annotationPath display ([caf671f](https://github.com/open-mmlab/labelbee/commit/caf671f43c811f1b102301ff0d0d5659e25e6401))
* I18next change init way ([8842bf0](https://github.com/open-mmlab/labelbee/commit/8842bf063c3b404912130e8c3c91e91eaba2d1a1))
* Optimize edgeAbsorption of PolygonTool which can absorpts points ([3a75b04](https://github.com/open-mmlab/labelbee/commit/3a75b04228d8faccf71dee49234980f50a8c054a))
* **pointTool:** The distance between limit points can't be less than 0.2px ([8e1d131](https://github.com/open-mmlab/labelbee/commit/8e1d131159c113d4330ca2ed7d4043868aafe1a9))


### Bug Fixes

* Fix the problem that the edge of rectTool cannot be dragged ([f6d3f11](https://github.com/open-mmlab/labelbee/commit/f6d3f1107773aaf84f60996ddb097b6c099145cb))
* I18n fobid react-useSuspense ([dce6bf0](https://github.com/open-mmlab/labelbee/commit/dce6bf0bbd4ac6b4eecf23f8f95085bdae4dc9aa))
* **pointTool:** DrawOutsideTarget doesn't work ([0a71a00](https://github.com/open-mmlab/labelbee/commit/0a71a008da437f02a6eef49d4199d10c0d7167e2))
* **pointTool:** The point still follows the mouse when mouse is released ([8871e10](https://github.com/open-mmlab/labelbee/commit/8871e10292196047075a8fa7b9554887d70b48c0))

## [1.5.0](https://github.com/Kerwin-L/labelbee-1/compare/v1.4.0...v1.5.0) (2022-03-30)
### Features

* API change: header sider footer ([3abaf5e](https://github.com/Kerwin-L/labelbee-1/commit/3abaf5eaa88c86253795143e8ffba87f2c132fb2))
* PointTool adds edgeAdsorption feature ([73e8d97](https://github.com/Kerwin-L/labelbee-1/commit/73e8d9764b93155091fe855042ebb08ed62eb75d))
* PolygonTool adds rect pattern ([2b0d0f0](https://github.com/Kerwin-L/labelbee-1/commit/2b0d0f0bfdd64451bbbc264a3b872fe03e76919c))
* PolygonTool-rect-pattern add drawOutside judgement ([725c231](https://github.com/Kerwin-L/labelbee-1/commit/725c231cb0c2552ce37796942b19549cd7785a30))
* PolygonView/LineView adds special line/point render ([cad0681](https://github.com/Kerwin-L/labelbee-1/commit/cad0681a4278406d7c50a9c96e5ec9c79130d767))
* RectOperation adds renderEnhance & dataInjection ([f3a5678](https://github.com/Kerwin-L/labelbee-1/commit/f3a56780088cf24036307d6543a0a4d9c6d70d15))

### Bug Fixes

* Fix PointTool MarkerPoint Opeartion ([52bddc7](https://github.com/Kerwin-L/labelbee-1/commit/52bddc7aa6c403c0b5e546e7cabab20e17bb3820))
* TextTool initValue fail and make updateTextValue error([#25](https://github.com/Kerwin-L/labelbee-1/issues/25)) ([f5714a1](https://github.com/Kerwin-L/labelbee-1/commit/f5714a160ed8e88618c93d623dd7c8b6cd1b5645))

## [1.4.0](https://github.com/open-mmlab/labelbee/compare/v1.3.0...v1.4.0) (2022-01-14)


### Features

* Add dragMove event trigger ([e31b578](https://github.com/open-mmlab/labelbee/commit/e31b578ed46940365081ddb112a5faa72f1c53eb))
* Add tag dom rendering / adapt to Polygonal curve ([ec0bfcc](https://github.com/open-mmlab/labelbee/commit/ec0bfcc27c723955b772f428de85817c79e11fb9))
* Add ToolStyleConverter in lb-utils ([393e07e](https://github.com/open-mmlab/labelbee/commit/393e07ea81acdc1340f22843519298498880f963))
* AnnotationView - text rendering added to graphics type ([e673fb8](https://github.com/open-mmlab/labelbee/commit/e673fb8f02cfc4b7cfbed6ed724101d2dd601ad2))
* AnnotationView add text annotation dispaly ([1c21c06](https://github.com/open-mmlab/labelbee/commit/1c21c061dc165aa95103fcc3cfc1949aae753571))
* AnnotationView Text support Position ([db6c9b3](https://github.com/open-mmlab/labelbee/commit/db6c9b3e386783e36bb5db8b0de7648041f5aecb))
* AnnotationView updates Label Render ([484395e](https://github.com/open-mmlab/labelbee/commit/484395e6cc1cc1be142ded965faef1c671f131c9))
* LineView adds Direction Render ([b2a474e](https://github.com/open-mmlab/labelbee/commit/b2a474e66b64e148e31f5053016fe3c3261f4849))
* PointTool adds list-annotation feature ([64ed73e](https://github.com/open-mmlab/labelbee/commit/64ed73e37ae95fe41e49a15b76424bed90aae2f1))
* PolygonView adds Direction Render ([bba3248](https://github.com/open-mmlab/labelbee/commit/bba3248c86931fbebd671b7d4b13b29b08755e19))
* Real-time update of text changes for ViewOperation ([1bd807b](https://github.com/open-mmlab/labelbee/commit/1bd807bc280c61835c12fb06e03b40caec431660))
* Support Custom text-dom using Style ([ae9031d](https://github.com/open-mmlab/labelbee/commit/ae9031d7a88ca1f734d53c22ac4b6ea4d1213e66))
* ViewOperation adds reference pattern(lineDash) ([5b2083b](https://github.com/open-mmlab/labelbee/commit/5b2083b060d0d2e46c8f64266167803d7636ae3c))


### Bug Fixes

* Adaptation of list annotations in the case of dependencies ([6ea04c6](https://github.com/open-mmlab/labelbee/commit/6ea04c64c0f1b2ce71ee705705bd92ecd392f55a))
* Adapting to the case where textConfigurable does not exist ([d084e7a](https://github.com/open-mmlab/labelbee/commit/d084e7af995c6181cdbb2da42dd2b8342bb8f380))
* Add viewOperation render data judgment ([b35a123](https://github.com/open-mmlab/labelbee/commit/b35a12353e002d4100182e8d0ea7f4f4ef60e281))
* Change canvas Mount Position / Add forbidBasicResultRender ([8020e3b](https://github.com/open-mmlab/labelbee/commit/8020e3b77c24f107449fb26c38c2e2d3f905ae84))
* Change the param of AnnotationView from color to stroke ([027ced8](https://github.com/open-mmlab/labelbee/commit/027ced8e7b1b1a82c37378119f018b0a258a3bee))
* Clear domMap in ViewOperation ([643aed1](https://github.com/open-mmlab/labelbee/commit/643aed1333e09166c5d4090051be2ae564c12db3))
* Compatible with old config of PointOperation ([2f0a4ae](https://github.com/open-mmlab/labelbee/commit/2f0a4aec6ccbf476e01cac433ec4983284413726))
* Fix getStyle2String function ([33c17b9](https://github.com/open-mmlab/labelbee/commit/33c17b9916786bffb30004d8653ced34ba47ff3a))
* Fix invalid page size error caused by canvas size change ([c958b71](https://github.com/open-mmlab/labelbee/commit/c958b71bcdf6e0461b0f1321a0a086495bbcbe62))
* Fix invalid page size error caused by window size change ([07784dd](https://github.com/open-mmlab/labelbee/commit/07784dddeebd03eadf294f7babb7508126bd2221))
* Fix lint -  Unreachable code  no-unreachable ([59e5bc2](https://github.com/open-mmlab/labelbee/commit/59e5bc2d8df747ad67620920c63b68cab459007b))
* Fix the accuracy of point-selected ([10fc24c](https://github.com/open-mmlab/labelbee/commit/10fc24c9fe0936f5b2e29d0e2e12cd90a3191b85))
* Fix the LowerLimitPoint of PointTool ([6976a51](https://github.com/open-mmlab/labelbee/commit/6976a51d0c2c9e1d4dda57f68b97dc09e46f7c32))
* Solve the problem caused by discontinuous steps in stepList ([007ed21](https://github.com/open-mmlab/labelbee/commit/007ed210a2fac0475b02c1143792212c05be36bd))
* Update the ActiveHistory of the PointOperation ([bcca28b](https://github.com/open-mmlab/labelbee/commit/bcca28bd84a5e1927f479121a8270f9f9198accb))

## 1.3.0 (2022-01-14)


### Features

*  label-bee 查看模式 ([c7dae52](https://github.com/open-mmlab/labelbee/commit/c7dae524c1a0345f0e84bbb25d9ae93a766df375))
* [lb-components]步骤切换优化: 单步骤不显示下一步, 步骤列表禁止切换为相同步骤 ([100d165](https://github.com/open-mmlab/labelbee/commit/100d165aa0d09f7540331ea34a7ce252303c2328))
* 暴露 i18n 到外部 / 修改默认 i18n 的语言 ([50a3565](https://github.com/open-mmlab/labelbee/commit/50a356552f86ddf4e4b25e0130d84cb1cc83cf81))
* 标注的 toolHeader 下一步添加限制 ([ae35161](https://github.com/open-mmlab/labelbee/commit/ae3516106ea2481647b52c0c87172978ab25ec27))
* 不存在的工具去除快捷键 ([af51252](https://github.com/open-mmlab/labelbee/commit/af5125211c578053d4699722e2795389da1ec66a))
* 查看工具添加选中 hover 的操作效果 ([08c3baa](https://github.com/open-mmlab/labelbee/commit/08c3baa1b57e5a074f98265f4ce7f4bf0a71a0a1))
* 查看工具支持适配 label-bee ([1ebb670](https://github.com/open-mmlab/labelbee/commit/1ebb67011da5d6f14c9cb758e3ebfa4186ec45b7))
* 查看模式内填充的添加 ([b9183c0](https://github.com/open-mmlab/labelbee/commit/b9183c0ae36755ce7ef3beccbb1ed1d161d788a7))
* 多边形/线条/拉框 - 边缘限制添加 ([7f09847](https://github.com/open-mmlab/labelbee/commit/7f09847ab97d0a7a2057e2ea13530fc01f3c5704))
* 多边形完成标注操作跟拉框同步 - 未开启文本标注不默认选中 ([34f2df6](https://github.com/open-mmlab/labelbee/commit/34f2df6b3d4ac6d3b4e5baed99fbedf8f2b519e5))
* 分离图片渲染/添加依赖渲染 ([e4d39c2](https://github.com/open-mmlab/labelbee/commit/e4d39c2591814249d2cc5104dfaa80b84140b507))
* 鼠标离开 canvas 清除一些缓存状态 ([45a16cc](https://github.com/open-mmlab/labelbee/commit/45a16cc0dbb6debfd373ca7f9d5e688f3d200c85))
* 添加 annotationEngine 用于管理各类工具的切换 ([46a070b](https://github.com/open-mmlab/labelbee/commit/46a070b67934a9431279f9fc657e97b92f8da04a))
* 添加save功能 修改工具图标 ([2e7eab8](https://github.com/open-mmlab/labelbee/commit/2e7eab8d83fe8f3fe37bf4aac8cc0cce305a521e))
* 线条支持被标签依赖 ([67a0b63](https://github.com/open-mmlab/labelbee/commit/67a0b6345a2f0a7c81df735e59cb5edc68f20456))
* 修改测量器的部分功能 / 提供外层位置信息的直接注入 ([e9c1fc8](https://github.com/open-mmlab/labelbee/commit/e9c1fc8192d24ae161975906a9885b5277f02308))
* 依赖情况下切换步骤保持图片位置 ([11b356b](https://github.com/open-mmlab/labelbee/commit/11b356bd440c43e1e16ca595ed4de6af602ba0ac))
* 优化 ViewOperation 内 hover 的优先级 ([1b59c4d](https://github.com/open-mmlab/labelbee/commit/1b59c4dc7134479f4f5edcbd967f9cf31c718417))
* 优化多边形双击操作的延迟卡顿问题 ([e70a94d](https://github.com/open-mmlab/labelbee/commit/e70a94d305457c4838c4a11e0fd733a12c86bee9))
* 暂时提供 toolFooter 缩放的图标的明亮模式 ([464b89c](https://github.com/open-mmlab/labelbee/commit/464b89c5d7e0289f6951e86f08e396f5c39812cd))
* label-bee 添加步骤切换组件 ([4100181](https://github.com/open-mmlab/labelbee/commit/410018170620ed8954c63850cbb1324a681019e0))
* Label-Bee 页面添加 loading ([382e4ae](https://github.com/open-mmlab/labelbee/commit/382e4aefd6b2cb1e6e2449ff1770463f8aa7b43e))
* SENSEBEE-7425: lb-component - 支持切换标注步骤 ([d939c43](https://github.com/open-mmlab/labelbee/commit/d939c4364bad21d34b63cd643df74f93318308ff))
* SENSEBEE-7425: lb-component 标注内支持依赖 ([79a2e7e](https://github.com/open-mmlab/labelbee/commit/79a2e7e1b78f464b78a2fee84c4b3209656c5511))
* SENSEBEE-7425: lb-demo配置多步骤列表 ([c7756ef](https://github.com/open-mmlab/labelbee/commit/c7756ef17fc88b44c9b80ebc363c29c54818221c))
* SENSEBEE-7665: 【lb-components】展示当前依赖的小页下标 ([b80dc59](https://github.com/open-mmlab/labelbee/commit/b80dc593f174b1b6a04205835eb8cc50c63f38dd))
* SENSEBEE-7666: 支持图片错误处理 ([4604407](https://github.com/open-mmlab/labelbee/commit/46044075044d0ad8f89ffb87b5597e35e6d06b8b))
* SENSEBEE-7668: 工具依赖下禁止更新旋转 ([73ec6f2](https://github.com/open-mmlab/labelbee/commit/73ec6f2f7834fde0560184e72be8345361b4d34a))
* SENSEBEE-8010: 【label-bee】提交数据的时候，需要过滤当前标注完成的数据 ([aea59d0](https://github.com/open-mmlab/labelbee/commit/aea59d07f50b5d3b33fb96c8711ffa93e2e1104b))
* SENSEBEE-8017: 依赖情况下旋转限制 ([65224a3](https://github.com/open-mmlab/labelbee/commit/65224a3fdbc2c637255aec8428f31fb212ce1231))
* SENSEBEE-8262:【lb-component】i18n支持 ([310086e](https://github.com/open-mmlab/labelbee/commit/310086e6bf6773a7acd67f32d23e4f83c6f83202))


### Bug Fixes

*  禁止滚轮操作触发外层事件 ([a3daa56](https://github.com/open-mmlab/labelbee/commit/a3daa56bde85fb4afc3baa1017e17481f367129c))
* 【lb-annotation】修复types问题 ([6be42f1](https://github.com/open-mmlab/labelbee/commit/6be42f15456a0873c91279b9ee85d4ab7fc6fb8d))
* 标签工具结果初始化添加 ([4449b2b](https://github.com/open-mmlab/labelbee/commit/4449b2b380ded1eeebddf2b5e15121f217207969))
* 标签工具隐藏撤销重做 ([b2cf41a](https://github.com/open-mmlab/labelbee/commit/b2cf41ab218012602eaa87e4f7528c8635668111))
* 单步步骤 toolheader 不展示下一步 ([e2b8b99](https://github.com/open-mmlab/labelbee/commit/e2b8b99f567540fda51d322b928d91109d8bd1f3))
* 多边形工具的双击添加点没有限定最大点数 ([c354ca2](https://github.com/open-mmlab/labelbee/commit/c354ca2f513e4bb6dce002fb1b3a5943048b56e6))
* 发布由于版本名称更新导致的命名错误问题 ([9c96caa](https://github.com/open-mmlab/labelbee/commit/9c96caaaeec2f0fb909c070ef96e9cc1bbc9d97f))
* 工具在无对应快捷键时, footer 不展示快捷键 ([06eb50f](https://github.com/open-mmlab/labelbee/commit/06eb50f46035e766a4c0b0dbc9e581a6843f1ff2))
* 将 antd 转为 antd/es ([0cdda82](https://github.com/open-mmlab/labelbee/commit/0cdda8242f21d0bda4a7f49cbd0c8a1c1e919c25))
* 将 basicOperation 双击事件绑定应用于上层(多边形), 避免误触使用 ([042df7c](https://github.com/open-mmlab/labelbee/commit/042df7c93366513fc4500e1dba30773c2f668ccf))
* 将 lb-utils 更改为 @sensetime/utils ([1a4becf](https://github.com/open-mmlab/labelbee/commit/1a4becf39899877ac278075c3b705e145652606e))
* 将所有 toolInstance 的事件监听从 on 转为 singleOn ([294f0d5](https://github.com/open-mmlab/labelbee/commit/294f0d5e6dc7bbaf2d9d12db90f4fcc1b8d39ba5))
* 禁止文本标注输入框keydown事件传播 ([8ff6091](https://github.com/open-mmlab/labelbee/commit/8ff609168d63970c9d91b4fc68745de3173f7731))
* 快捷键功能隐藏 ([d8f7201](https://github.com/open-mmlab/labelbee/commit/d8f7201fad3a7e02d324429bb3bf1726221fc1e0))
* 拉框工具 - 多变形工具重写 destroy 函数,清楚文本的属性注入 ([2a99fea](https://github.com/open-mmlab/labelbee/commit/2a99fea24237afea850eed7a863c7576de9902a2))
* 修复 getFileData 外层注入不可用问题 ([9691811](https://github.com/open-mmlab/labelbee/commit/969181189f73bac61de1449d499a33cf033f7404))
* 修复 label-bee 内 ts 编译错误问题 ([6b65e59](https://github.com/open-mmlab/labelbee/commit/6b65e59d360ba1a7d3dd2ff118e74ca170508bfb))
* 修复 mock 数据的问题 ([77aeb2c](https://github.com/open-mmlab/labelbee/commit/77aeb2c4406b511a5db7bf64e306fab046eef72f))
* 修复 Sense-annotation 编译错误问题 ([8c16888](https://github.com/open-mmlab/labelbee/commit/8c1688818c4d8c3dc4846ebb7052b068ce70cd2c))
* 修复 Sense-annotation 内 ts 编译错误问题 ([bfa0d9f](https://github.com/open-mmlab/labelbee/commit/bfa0d9f596b061572df9ebcb95489914018a8b66))
* 修复 ts compile error ([5e60694](https://github.com/open-mmlab/labelbee/commit/5e606948abe0dc3a0896e5da61d006bbefe2714a))
* 修复标签工具内sourcei的Ddiff错误 ([be488aa](https://github.com/open-mmlab/labelbee/commit/be488aa4de123bc53161b93bb31c5ce454f9f079))
* 修复标签工具切换崩溃的问题 ([60c2497](https://github.com/open-mmlab/labelbee/commit/60c249727ef05c424d6543d5247a957356726fc8))
* 修复标签工具切换没有清除渲染标签的问题 ([caf4644](https://github.com/open-mmlab/labelbee/commit/caf4644723c59d86fc9b2d2abb72acc2c84d50fa))
* 修复标签工具在无依赖情况下还会初始化结果 ([5aa5811](https://github.com/open-mmlab/labelbee/commit/5aa58118304323585bc71456372aaa1552227bb3))
* 修复标注工具键盘事件配置未限制的错误 ([3402d47](https://github.com/open-mmlab/labelbee/commit/3402d47e9930f5003ba912c8e2804669301f80ea))
* 修复打包错误 ([882efe5](https://github.com/open-mmlab/labelbee/commit/882efe5f16aa26a418f90b83ffdbfd2ce6eaa0ee))
* 修复多步骤跳转的结果找不到的问题 ([e7a9519](https://github.com/open-mmlab/labelbee/commit/e7a95194f6b9b30517adb0c300c41d49e947c49d))
* 修复国际化的小问题 ([0f834b9](https://github.com/open-mmlab/labelbee/commit/0f834b9d478038477d046b79b4f65d728faf81c2))
* 修复获取order时候sourceID的diff问题 ([00b8c2c](https://github.com/open-mmlab/labelbee/commit/00b8c2c7091db4140b4c65bb62386e539351e728))
* 修复结果中嵌入了数组结构数据 ([e28c124](https://github.com/open-mmlab/labelbee/commit/e28c124c68cde117216db4374d80b241a428ab3c))
* 修复界面被撑开以及原图显示的问题 ([89ac3e0](https://github.com/open-mmlab/labelbee/commit/89ac3e0ac5a5c85c02358ba526f37fe7ab750e55))
* 修复外界缩放和图片更改 canvas 无法立即响应的问题 ([7d5d1d5](https://github.com/open-mmlab/labelbee/commit/7d5d1d5b39462189f1eed7639f10a436b0614e41))
* 修复无效图层的层级 ([864d34c](https://github.com/open-mmlab/labelbee/commit/864d34c45b9c28818f3b031cd657ceb611f52833))
* 修复线条工具键盘切换属性不生效的问题 ([90de51c](https://github.com/open-mmlab/labelbee/commit/90de51c3a38decccceb7f8e87977588ecd9640ef))
* 修复线条工具十字线不存在的问题 / 拖动选中线条拖影的问题 ([13cb586](https://github.com/open-mmlab/labelbee/commit/13cb5865890f9374983fe7cb196ba693da3b4416))
* 修复小页下标从 0 开始的问题 ([25ee20f](https://github.com/open-mmlab/labelbee/commit/25ee20fc65b3e994a914070c4a630e2a84c3ec25))
* 修复因图片路径问题导致的加载错误问题 ([2367f65](https://github.com/open-mmlab/labelbee/commit/2367f6549dfbf00a682a5d26c938ffda74de8416))
* 渲染添加限制 ([6945607](https://github.com/open-mmlab/labelbee/commit/6945607716719ec59aec04921eb5034cb75e5a83))
* 优化细节交互 ([fd6be60](https://github.com/open-mmlab/labelbee/commit/fd6be60dd5e94b33722ce5c396a05e0138386b1f))
* 组件销毁时清除事件绑定 ([cdaa3ba](https://github.com/open-mmlab/labelbee/commit/cdaa3bae7ed9093b99581633b6ca49e6fcb154f7))
* annotation 类型修复 ([5bc5b60](https://github.com/open-mmlab/labelbee/commit/5bc5b6063a69bac2940d85571df5d948c899f8c6))
* AppProps 新增style属性  layout 布局改动 ([6a44392](https://github.com/open-mmlab/labelbee/commit/6a443924ec408877d8ac153f2736e27b065c16b5))
* BasicOperation 滚轮操作禁止默认操作 ([d5e9eb6](https://github.com/open-mmlab/labelbee/commit/d5e9eb65be6419d9499cec46c12811a1c7f4f2ed))
* canvas 宽高调整 ([c729aa4](https://github.com/open-mmlab/labelbee/commit/c729aa4b843ab9f30a4ca37c1da13d2638717008))
* checkoperation添加多边形textattribute显示 ([60d7c1a](https://github.com/open-mmlab/labelbee/commit/60d7c1a157b6452bec7f48b02ee3b0ea71b9bd9f))
* Eslint 问题修复 ([2de721c](https://github.com/open-mmlab/labelbee/commit/2de721c2658d66b5d9a523a184ef6ee5b69125e7))
* Hotkey 的国际化修复 ([0e5a431](https://github.com/open-mmlab/labelbee/commit/0e5a431f5c14c66442d7ff7bbcce88a7a0b22dc6))
* SENSEBEE-7610: 【lb-annotation】线条文本标注icon颜色不更新 ([8e6ff49](https://github.com/open-mmlab/labelbee/commit/8e6ff49667fd0445f23d7162615c930998ea80b9))
* SENSEBEE-7610: 线条的侧边栏并未检查文本输入 ([a1024c9](https://github.com/open-mmlab/labelbee/commit/a1024c9d1ebb755a8d797e3db3710c1be059a1e5))
* SENSEBEE-7610: 线条工具目标外标注失效 ([716bf6b](https://github.com/open-mmlab/labelbee/commit/716bf6bc6532f43b9ddb2942094e0a9129049e41))
* SENSEBEE-7751: 修复基础数据消失问题 ([73a6dbc](https://github.com/open-mmlab/labelbee/commit/73a6dbcf1ff940b807182c179ecd47f61c1035f1))
* SENSEBEE-7910: 【Label-bee + annotation】标签工具 / 文本工具在依赖初始化有问题，仅能初始化第一个依赖 ([12e22b3](https://github.com/open-mmlab/labelbee/commit/12e22b3941f029e06b0ed868a103702c3d7bab43))
* SENSEBEE-7939: [lb-component] 文本工具无法快捷翻页 ([5ad2a9d](https://github.com/open-mmlab/labelbee/commit/5ad2a9d1480edbe88e9a4a1d558796c8d006e905))
* SENSEBEE-7940: 点击下一步时，没有正常回显已标注的文本信息 ([dd470f5](https://github.com/open-mmlab/labelbee/commit/dd470f5c7cb23ec95da3792925eab4d643898576))
* SENSEBEE-7940: 修复文本工具无法切换依赖数据 ([35e506e](https://github.com/open-mmlab/labelbee/commit/35e506e3a4709e544cc71957bfde4affcb03ab57))
* SENSEBEE-7976: 【label-bee】线条工具 - 选中线条后侧边信息未同步 ([46a156b](https://github.com/open-mmlab/labelbee/commit/46a156b8a7a34db16786d40d8135f7ae0114f9d5))
* SENSEBEE-7977: 【label-bee】单步骤创建的时候，toolHeader 上方的旋转点击不生效 ([d8de761](https://github.com/open-mmlab/labelbee/commit/d8de76178e6b6f6abaa4a5fc6b5ba98d5ad2909f))
* SENSEBEE-7983: 【SDK】【单步骤标注任务】--线条步骤点击清除标注数据没有效果 ([1da14c0](https://github.com/open-mmlab/labelbee/commit/1da14c0d729b389b2e8850206750f7dbf527ad83))
* SENSEBEE-8010: 【label-bee】点击 toolHeader 的下一步切换步骤，若切换前页面为无效图片，则切换后始终保持无效 ([9747288](https://github.com/open-mmlab/labelbee/commit/9747288c96229242d6e766839a38d0b17f81b1af))
* SENSEBEE-8012 多步骤 依赖拉框目标外标注问题 ([348f522](https://github.com/open-mmlab/labelbee/commit/348f52296969fdab13127d0ee774d262f943eb2c))
* SENSEBEE-8014: 【label-bee】当前页面完全新的，复制上张会复制上张图片的所有数据 ([ee6a2d7](https://github.com/open-mmlab/labelbee/commit/ee6a2d7831ee358382e7428a47914baef02291be))
* SENSEBEE-8277: 【annotation】拉框选中时 space + 左键拖动会有点小问题 ([4cd2c72](https://github.com/open-mmlab/labelbee/commit/4cd2c72bbac839abb4fa0b82adf29af2af7216af))
* SENSEBEE: 7908 7909 ([baf8173](https://github.com/open-mmlab/labelbee/commit/baf81734f61feb373a19da35b4cc8c9e796a8b7c))
* SENSEBEE: 7913 7915 ([bb3f3cf](https://github.com/open-mmlab/labelbee/commit/bb3f3cf5e017fd6c4fdc1536cd651371a6497c39))
* SENSEBEE: 8003 标点工具计数问题 ([e79b488](https://github.com/open-mmlab/labelbee/commit/e79b4888de46122ce3e6e49aa49fdbbd5c47b92f))
