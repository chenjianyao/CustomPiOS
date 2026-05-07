# Changelog
All changes will be documented in this file.

## [1.1.0.smile] - 2024-10-16
- 在 common.sh 中增加 export_by_cp 函数
- 在 common.sh 中增加 export_by_mv 函数
- 在 custompios 增加逻辑，判断/tmp/export/目录是否存在，将目录中文件移动到${BASE_WORKSPACE}/export/中
- 在 common.sh 中增加 print_status 函数
- 去掉调试日志（-x）