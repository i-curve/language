# apt命令大全

- apt-get update: 更新缓存
- apt-get upgarde: 根据缓存更新软件(简单更新,不会解决依赖问题)
- apt-get dist-upgrade: 更新软件, 会解决依赖  


卸载命令  
- apt-get autoremove:自动卸载无用依赖和软件
- apt-get remove  **name**: 卸载软件,不会卸载配置文件
- apt-get purge  **name**: 卸载软件和配置文件
安装命令
- apt-get install **name**:安装软件
