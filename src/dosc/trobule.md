问题原因
项目启动失败是因为缺少 TypeChain 生成的 ABI 类型文件。错误信息显示无法解析 "abis/types" 模块导入。
修复步骤
我已经执行了以下操作：
✅ 检查了 ABI 源文件 - 确认 src/abis/ 目录下有 token.json 和 voucher.json
✅ 运行了 TypeChain 编译 - 执行 yarn compile-abis 成功生成了 7 个类型文件
✅ 生成的类型文件：
src/abis/types/Token.ts
src/abis/types/Voucher.ts
src/abis/types/common.ts
src/abis/types/index.ts
factories 目录下的工厂文件