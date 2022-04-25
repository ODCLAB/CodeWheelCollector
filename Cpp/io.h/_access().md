```cpp
int _access(const char *__name,int __type)
```
- 作用
获取文件访问权限

- 参数

<table>
    <tr>
        <th>名称</th>
        <th>意义</th>
        <th>值</th>
        <th>意义</th>
    </tr>
    <tr>
        <td>__name</td>
        <td>文件名</td>
        <td></td>
        <td></td>
    </tr>
    <tr>
        <td rowspan="6">__type</td>
        <td rowspan="6.">模式</td>
    </tr>
    <tr>
        <td>0</td>
        <td>检查文件是否存在</td>
    </tr>
    <tr>
        <td>1</td>
        <td>检查文件是否可运行</td>
    </tr>  
    <tr>
        <td>2</td>
        <td>检查文件是否可写访问</td>
    </tr>   
    <tr>
        <td>4</td>
        <td>检查文件是否可读访问</td>
    </tr>   
    <tr>
        <td>6</td>
        <td>检查文件是否可读/写访问</td>
    </tr>
</table>

- 返回值

  | 值 | 意义 |
  | ------ | ---- |
  | 0      | 具有给定的模式 |
  | -1     | 不存在或没有给定的模式 |