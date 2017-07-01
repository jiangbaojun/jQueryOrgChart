
## data数据选项
<table>
  <thead>
    <tr><th>选项</th><th>类型</th><th>描述</th></tr>
  </thead>
  <tbody>
    <tr>
      <td>id</td><td>string</td><td>数据节点id</td>
    </tr>
    <tr>
      <td>parentId</td><td>string</td><td>数据节点父id</td>
    </tr>
    <tr>
      <td>name</td><td>json array</td><td>节点名称</td>
    </tr>
    <tr>
      <td>collapsed</td><td>boolean</td><td>是否折叠</td>
    </tr>
    <tr>
      <td>url</td><td>number</td><td>节点超地址链接</td>
    </tr>
    <tr>
      <td>orderNum</td><td>boolean</td><td>no</td><td>同级节点顺序编号</td>
    </tr>
    <tr>
      <td>nodeClass</td><td>boolean</td><td>自定义node节点class</td>
    </tr>
  </tbody>
</table>

## options选项

<table>
  <thead>
    <tr><th>选项</th><th>类型</th><th>默认</th><th>描述</th></tr>
  </thead>
  <tbody>
    <tr>
      <td>depth</td><td>number</td><td>-1</td><td>显示级数限制，-1为不限制</td>
    </tr>
    <tr>
      <td>chartClass</td><td>string</td><td>"org-chart"</td><td>结构图容器class名称</td>
    </tr>
    <tr>
      <td>data</td><td>json array</td><td>[]</td><td>结构图数据</td>
    </tr>
    <tr>
      <td>rootId</td><td>number</td><td>0</td><td>根节点</td>
    </tr>
    <tr>
      <td>showOrderNum</td><td>boolean</td><td>true</td><td>是否显示orderNum</td>
    </tr>
  </tbody>
</table>

##　说明
    参考 [wesnolte](https://github.com/wesnolte)的[jOrgChart](https://github.com/wesnolte/jOrgChart)