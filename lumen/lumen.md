# Lumen 最佳实践
## 整体原则
- 尽可能复用代码，尽可能统一规范
- 尽可能复用代码，尽可能统一规范
- 尽可能复用代码，尽可能统一规范

## 集成
- [开发环境集成](https://github.com/YunhanPHP/lumen-require-dev)
- `todo` 生产环境集成

## 整体规范
- 目录按照功能模块进行划分，不要全部放在根目录
- 所有 `DB` 操作只能在 `Model` 或 `Service` 层
- 对应 `Model` 操作只能在对应的 `Model` 或 `Service` 文件中

## 整体总结
- [Model](summary/model.md)
