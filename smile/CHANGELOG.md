# Changelog
All changes will be documented in this file.

## [2.0.0] - 2026-05-08
- 在 custompios.sh 中移除根目录下 common.sh
- 在 common.sh 中增加 export_by_cp 函数
- 在 common.sh 中增加 export_by_mv 函数
- 在 custompios 增加逻辑，判断 /tmp/export/ 目录是否存在，将目录中文件移动到 ${BASE_WORKSPACE}/export/ 中
- 在 common.sh 中增加 print_status 函数
- 去掉调试日志（-x）

搜索 bash -x 去掉-x 参数
搜索 set -x 去掉-x 参数
搜索 set -ex 去掉-x 参数
