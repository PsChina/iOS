## React-Native iOS 依赖问题

```bash
# 1. 清理 CocoaPods 缓存
pod cache clean --all

# 2. 删除损坏的 podspec 仓库
rm -rf ~/.cocoapods/repos/trunk

# 3. 更新仓库
pod repo update

# 4. 进入 iOS 目录重新安装
cd /path/to/loyalty-rn-frontend/ios

bundle install

bundle exec pod install

```
