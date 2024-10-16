# Changelog
All changes will be documented in this file.

## [1.1.0.smile] - 2024-10-16
- 在common.sh中增加export_by_cp函数
- 在common.sh中增加export_by_mv函数
- 在custompios增加逻辑，判断/tmp/export/目录是否存在，将目录中文件移动到${BASE_WORKSPACE}/export/中
- 在common.sh中增加print_status函数
- 去掉调试日志（-x）