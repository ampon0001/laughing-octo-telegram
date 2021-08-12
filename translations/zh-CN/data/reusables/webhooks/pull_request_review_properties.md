| 键                     | 类型    | 描述                                           |
| --------------------- | ----- | -------------------------------------------- |
| `action`              | `字符串` | 执行的操作内容. 可以是以下选项之一：<ul><li>`submitted` - 拉取请求审查被提交为非挂起状态。</li><li>`edited` - 审查的正文被编辑。</li><li>`dismissed` - 审查被驳回。</li></ul> |
| `pull_request`        | `对象`  | 与审查相关的[拉取请求](/rest/reference/pulls)。         |
| `审查`                  | `对象`  | 受影响的审查。                                      |
| `changes[body][from]` | `字符串` | 正文的先前版本，如果操作为 `edited`。                      |