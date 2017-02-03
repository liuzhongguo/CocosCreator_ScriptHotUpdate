# Cocos Creator 脚本热更新
通过脚本实现了官方 C++ 版热更功能，提高的稳定性和易维护性，使用者可在脚本上扩展自定义的版本更新业务。

# 实现功能清单
1. 版本配置文件对比，提示有新版本
2. 版本清单文件对比，分析出添加、更新、删除的资源进行下载或删除
3. 更新失败或异常中断时，记录更新状态，下次触发更新时恢复更新进度，不在下载已更新的文件
4. 支持多模块热更新管理
5. 基于CocosCrator编辑器的版本配置文件生成工具插件

# 使用方式
1. 打开 Cocos Creator 的 XXGAME 项目
2. 菜单选择“项目 > 构建发布”
3. 点击构建按钮
4. 菜单选择“自定义工具 > 热更配置生成”

# 其它说明
1. 热更脚本代码在assets/script文件下AssetsManager.js、AssetsDownload.js两个文件，代码上注释比较全
2. 热更工具代码在packages/hot_update文件下

# 联系方式
gdong@bainainfo.com