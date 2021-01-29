# 基于[@hellowuxin/mindmap](https://github.com/hellowuxin/mindmap)修改的思维导图插件

> 基于 [wuxin大佬](https://github.com/hellowuxin)的思维导图插件，结合实际需求进行更改
> 除原版基本功能外，新增协同编辑。节点加锁、解锁、详情。

## 安装

```sh
npm install @chenyanggis/mindmap
```

## PROPS

| Name        | Type    | Default   | Description            |
| ----------- | ------- | --------- | ---------------------- |
| v-model     | Array   | undefined | 设置思维导图数据       |
| width       | Number  | 100%      | 设置组件宽度           |
| height      | Number  | undefined | 设置组件高度           |
| xSpacing    | Number  | 80        | 设置节点横向间隔       |
| ySpacing    | Number  | 20        | 设置节点纵向间隔       |
| strokeWidth | Number  | 4         | 设置连线的宽度         |
| draggable   | Boolean | true      | 设置节点是否可拖拽     |
| gps         | Boolean | true      | 是否显示居中按钮       |
| fitView     | Boolean | true      | 是否显示缩放按钮       |
| showNodeAdd | Boolean | true      | 是否显示添加节点按钮   |
| keyboard    | Boolean | true      | 是否响应键盘事件       |
| contextMenu | Boolean | true      | 是否响应右键菜单       |
| zoomable    | Boolean | true      | 是否可缩放、拖移       |
| showUndo    | Boolean | true      | 是否显示撤销重做按钮   |
| download    | Boolean | true      | 是否显示下载按钮       |
| editable    | Boolean | true      | 节点是否可编辑（新增） |

## EVENTS

| Name           | arguments | Description                                  |
| -------------- | --------- | -------------------------------------------- |
| updateNodeName | data, id  | 更新节点名称时，传入节点数据和节点id         |
| click          | data, id  | 点击节点时，传入节点数据和节点id             |
| showDetial     | data, id  | 点击节点时，传入节点数据和节点id（新增）     |
| delnode        | data      | 右键菜单点击删除节点时，传入节点数据（新增） |
| nodeedited     | data      | 右键菜单点击编辑节点时，传入节点数据（新增） |
| contextMenu    | data      | 节点点击右键时，传入节点数据和id（新增）     |

##  尊重原创

 ### 原作者[wuxin大佬](https://github.com/hellowuxin)

 ### 原项目[@hellowuxin/mindmap](https://github.com/hellowuxin/mindmap)
