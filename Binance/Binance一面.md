1. 自我介绍
2. 项目都是自己写的吗？
3. 我看你用 koa2 写后端，为什么选择它，能讲讲吗？
4. 那你提到 koa2 它是不提供中间件的，你是怎么解决的？
5. 中间件的原理是什么？（洋葱模型）
6. 你刚刚说碰到 next() 就进入下一个中间件，那 next 只能执行同步，如果是异步的话，你是怎么处理的？（async/await，但是我发现，有的中间件需要在异步中间件之前执行，所以我用 try/catch 来处理异步中间件的异常）
7. JS 异步发展史，以及它们的优缺点说一下 （回调函数--Promise--Generator--async/await）
8. 你刚刚说 Promise 状态不能更改，那如果我要设计一个能修改 Promise 状态的函数，你会怎么设计？
9. CSS 水平垂直居中的方法（flex、grid、绝对定位 + margin:auto、绝对定位 + 负 margin、绝对定位 + transform、table-cell）
10. 你刚刚说到 flex 布局，那 flex：1 是什么意思？（flex: flex-grow  flex-shrink  flex-basis;等价 flex:1 1 0%表示元素可以均分剩余空间，可拉伸、可压缩，不依赖内容宽度，自动自适应填充布局。）
11. 父容器宽是 500px，然后它左右各有两个子容器是 100px，如果设置 flex: 1，那它的宽度是多少？（500-100-100=300px）
12. 说说你对浏览器缓存的理解（强缓存、协商缓存）
13. 如果一个用户，他怎么去刷新都无法刷到最新版的代码，你能说下可能的原因吗？（版本号、hash等）还有吗？（我说我不知道了，面试官说还有 CDN 没有同步，我说企业才会这么干，自己写项目一般不会，我知道 cdn 是用来解决高并发的手段）
14. React你熟吗？说下 React 函数组件和类组件的区别
15. 怎么避免 Hooks 导致组件重新渲染？（使用 useCallback、useMemo、React.memo、useRef等等）
16. 谈一下我对 React 的状态管理的理解（Redux、Mobx、Zustand，我说 Zustand 用的最多）
17. React 常见的 hooks 有哪些？（useState、useEffect、useRef、useCallback、useMemo、useReducer、useContext、useImperativeHandle、useLayoutEffect、useDebugValue）
18. TS 你熟吗？我们引进 TS 的目的是为什么？
19. interface 和 type 的区别
20. 说下 TS 里的泛型
21. 我现在有十个字段，比如十个字段就要 A B C D E F G 这种。那我现在另有另外一个方法，这个方法接受的参数呢，必须是这个 interface A 里面的这个 K。就比如说你可以是 A B C 可以 A B C D 任何组合都可以，但是必须是这个 interface 里面的 A 里面的定义的。这个 K 这种类型的话是怎么去定义呢？（说实话我有点不太理解啥意思，反正我说了 keyof）
``` TypeScript
interface Obj {
  A: string
  B: string
  C: string
  D: string
  E: string
  // 其他字段...
}
```
22. vite 用过吗？说说和 webpack 的区别。vite 的优缺点是什么
23. 说说 Tree shaking（树摇） 和 Code Splitting （代码分割）的区别
24. Git 你熟吗？说说 git merge 和 git rebase 的区别，什么时候用 git merge，什么时候用 git rebase？
25. web3 你熟吗？（不太熟，听说过而已）
26. 我看你自我介绍说了 AI，你是怎么用的？
27. 除了提示词，还有什么能让 AI 更聪明？
28. AI 的优缺点你说一下
29. AI 发展这么快，你觉得我们以后会扮演什么角色？
30. 反问