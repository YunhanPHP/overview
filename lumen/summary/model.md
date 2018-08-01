# 模型总结
## 总结
- 使用软删除 [`SoftDeletes`](https://laravel.com/docs/5.6/eloquent)
- 使用 `fillable` 指定可批量填充字段
- 尽量使用 [`Relationship`](https://laravel.com/docs/5.6/eloquent-relationships)

## 常用方法
### 框架内置
- 根据主键查找一个元素
    - find：返回object或null
    - findOrFail：未找到则抛出异常 `Illuminate\Database\Eloquent\ModelNotFoundException`
    - findOrNew：未找到则初始化对象
- 根据一组主键查找一系列元素
    - findMany
- 创建
    - create
    - firstOrCreate：未找到则插入到数据库
    - firstOrNew：未找到则初始化对象

### 项目使用
- 根据某项查找一个数据
    - findOneByXxx
- 根据某项查找一组数据
    - findManyByXxx
