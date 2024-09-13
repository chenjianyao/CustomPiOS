# Changelog
All notable changes to Mainsail will be documented in this file.

## [1.0.0.smile] - 2024-09-11

- bash -x 去掉-x参数，不打印调试日志
- 在common.sh中增加export_by_cp函数
- 在common.sh中增加export_by_mv函数
- 在custompios增加逻辑，判断/tmp/export/目录是否存在，将目录中文件移动到${BASE_WORKSPACE}/export/中
