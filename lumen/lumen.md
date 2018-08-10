# Lumen 最佳实践
## 整体原则
- 尽可能复用代码，尽可能统一规范
- 尽可能复用代码，尽可能统一规范
- 尽可能复用代码，尽可能统一规范

## 框架工具
- [常用方法](https://laravel.com/docs/5.6/helpers)
- [数组深度处理](https://laravel.com/docs/5.6/collections)

## 集成
- [开发环境集成](https://github.com/YunhanPHP/lumen-require-dev)
- [生产环境集成](https://code.aliyun.com/jqb-php/lumen-require)：暂时仅供内部使用

## 整体规范
### 必须遵守
- 目录按照功能模块进行划分，不要全部放在根目录
- 所有 `DB` 操作只能在 `Model` 或 `Service` 层
- 对应 `Model` 操作只能在对应的 `Model` 或 `Service` 文件中
- 使用 `guzzle` 进行数据请求

### 建议
- 尽量准确定义入参和出参
- 尽量使用对象当做参数传递
- 使用 `Carbon` 作为所有时间参数 

## 整体总结
- [Model](summary/model.md)
