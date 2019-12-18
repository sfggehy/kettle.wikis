# 添加序列（Add sequence）

## 描述

添加序列步骤向流添加序列。序列是一个不断变化的整数值，具有特定的开始和增量值。您可以使用数据库序列来确定序列的值，也可以让它由Kettle生成。

> - Kettle 序列仅在用于相同转换时才是唯一的。此外，它们不会存储，因此每次启动转换时，值都会以相同的值重新开始
> - 如果在群集环境中需要唯一ID，请查看从Slave Server获取ID的步骤。
> - 另请参阅：[添加值字段更改序列]() - 根据字段值更改添加序列;每次至少有一个字段值改变时，PDI将重置序列
> - 另请参见：[逐个分组]() - 按时间在一个组中构建聚合，并在具有重复值的行中生成序列号。

## 选项

下表包含"添加序列"步骤的各个选项：

| 选项 | 描述 |
| --- | --- |
| 步骤名称 | 此步骤的名称显示在转换工作区中。此名称在单个转换中必须是唯一的。|