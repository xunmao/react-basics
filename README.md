# react-basics

此项目用于学习和尝试 React ( https://react.docschina.org ) 框架的各种功能。  
此项目属于 React 框架学习系列的第一季，主要学习 React 基础。

## 准备工作

为了减少对其他知识的依赖，此项目没用使用 Node.js 而是通过 UNPKG ( https://unpkg.com/ ) 来获取外部依赖。

此项目使用到的外部依赖如下：
- React: 18.2.0
- ReactDOM: 18.2.0
- Babel: 7.0.0-beta.2: 使用 Babel 将 JSX 翻译成 JS
- PropTypes: 15.6.2: 使用 PropTypes 进行类型检查

执行以下命令即可将依赖包下载至此项目的`lib`文件夹：

```sh
# 下载 React 依赖
curl https://unpkg.com/react@18.2.0/umd/react.development.js > lib/react.development.js

# 下载 ReactDOM 依赖
curl https://unpkg.com/react-dom@18.2.0/umd/react-dom.development.js > lib/react-dom.development.js

# 下载 Babel 依赖
curl https://unpkg.com/browse/@babel/standalone@7.0.0-beta.2/babel.min.js > lib/babel.min.js

# 下载 PropTypes 依赖
curl https://unpkg.com/prop-types@15.6.2/prop-types.js > lib/prop-types.js
```

关于 PropTypes 的介绍和用法，具体参考：  
https://zh-hans.reactjs.org/docs/typechecking-with-proptypes.html#gatsby-focus-wrapper

## 各种插件

推荐使用以下插件来提升效率：
1. VS Code 插件：open in browser ( https://github.com/SudoKillMe/vscode-extensions-open-in-browser )
1. Chrome 插件：React Developer Tools ( https://chrome.google.com/webstore/detail/react-developer-tools/fmkadmapgofadopljbjfkapdkoienihi )

## 内容提要

[TODO]

1. [01-HelloReact](./01-HelloReact/HelloReact.html)
1. 02-虚拟DOM的两种创建方式
    1. [01-使用JSX创建](./02-虚拟DOM的两种创建方式/01-使用JSX创建.html)
    1. [02-使用JS创建](./02-虚拟DOM的两种创建方式/02-使用JS创建.html)
    1. [03-虚拟DOM与真实DOM](./02-虚拟DOM的两种创建方式/03-虚拟DOM与真实DOM.html)
1. [03-JSX语法规则](./03-JSX语法规则/JSX语法规则.html)
1. [04-JSX应用练习](./04-JSX应用练习/JSX应用练习.html)
1. 05-定义组件
    1. [01-函数式组件](./05-定义组件/01-函数式组件.html)
    1. [02-类式组件](./05-定义组件/02-类式组件.html)
1. 06-组件实例的三大属性-state
    1. [01-标准State](./06-组件实例的三大属性-state/01-标准State.html)
    1. [02-简化State](./06-组件实例的三大属性-state/02-简化State.html)
1. 07-组件实例的三大属性-props
    1. [01-Props的基本用法.html](./07-组件实例的三大属性-props/01-Props的基本用法.html)
    1. [02-对Props进行类型限制](./07-组件实例的三大属性-props/02-对Props进行类型限制.html)
    1. [03-函数式组件使用Props](./07-组件实例的三大属性-props/03-函数式组件使用Props.html)
1. 08-组件实例的三大属性-refs
    1. [01-字符串形式的Refs](./08-组件实例的三大属性-refs/01-字符串形式的Refs.html)
    1. [02-回调函数形式的Refs](./08-组件实例的三大属性-refs/02-回调函数形式的Refs.html)
    1. [03-关于回调Ref中回调函数的执行次数](./08-组件实例的三大属性-refs/03-关于回调Ref中回调函数的执行次数.html)
    1. [04-使用createRef创建Ref](./08-组件实例的三大属性-refs/04-使用createRef创建Ref.html)
1. [09-事件处理](./09-事件处理/事件处理.html)
1. 10-收集表单数据
    1. [01-非受控组件](./10-收集表单数据/01-非受控组件.html)
    1. [02-受控组件](./10-收集表单数据/02-受控组件.html)
1. [11-高阶函数（函数柯里化）](./11-高阶函数（函数柯里化）/高阶函数（函数柯里化）.html)
1. 12-组件的生命周期
    1. [01-引出生命周期](./12-组件的生命周期/01-引出生命周期.html)
    1. [02-旧版（v16）生命周期](./12-组件的生命周期/02-旧版（v16）生命周期.html)
    1. [03-父子组件](./12-组件的生命周期/03-父子组件.html)
    1. [04-新版（v18）生命周期](./12-组件的生命周期/04-新版（v18）生命周期.html)
    1. [05-使用getSnapshotBeforeUpdate](./12-组件的生命周期/05-使用getSnapshotBeforeUpdate.html)
1. 13-DOM的Diffing算法
    1. [01-验证Diffing算法](./13-DOM的Diffing算法/01-验证Diffing算法.html)
    1. [02-key的作用](./13-DOM的Diffing算法/02-key的作用.html)
1. 复习
    1. [01-类的基本知识](./复习/01-类的基本知识.html)
    1. [02-原生事件绑定](./复习/02-原生事件绑定.html)
    1. [03-类的方法中this的指向](./复习/03-类的方法中this的指向.html)
    1. [04-展开运算符](./复习/04-展开运算符.html)