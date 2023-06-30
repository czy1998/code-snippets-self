# code-snippets-self

一些注释的代码片段的集合

# How To Use

在 `js、ts` 文件中输`hera`前缀，即可选择应用相应的代码片段，下面列举几个示例

```ts
页面注释(详细)
hera-page-specific
/**
 * @title ${1: 标题}
 * @pagePath ${2: 页面地址}
 * @router ${3: 路由}
 * @description ${4: 具体介绍}
 */

组件注释
hera-com
/**
 * @title ${1: 标题}
 * @description ${2: 具体介绍}
 */

函数注释(详细)
hera-func-specific
/**
 * @title ${1: 标题}
 * @description ${2: 具体介绍}
 * @param ${3: 变量}
 * @return ${4: 返回结果}
 */

获取当前时间
hera-time
/**
 * @完整时间 ${1: $CURRENT_YEAR-$CURRENT_MONTH-$CURRENT_DATE $CURRENT_HOUR:$CURRENT_MINUTE:$CURRENT_SECOND}
 * @月份 ${2: $CURRENT_MONTH_NAME_SHORT}
 * @星期 ${3: $CURRENT_DAY_NAME_SHORT}
 */

获取当前文件信息
hera-fileInfo
/**
 * @文件名_带后缀 ${1: $TM_FILENAME}
 * @文件名_不带后缀 ${2: $TM_FILENAME_BASE}
 * @项目完整地址 ${3: $TM_DIRECTORY}
 * @文件完整地址 ${4: $TM_FILEPATH}
 * @文件相对地址 ${5: $RELATIVE_FILEPATH}
 */
```
