# JavaScript-Notes 學習日記
## 4/16
1. 樣板字面值 (Template literals / Template strings) [參考文件](https://developer.mozilla.org/zh-TW/docs/Web/JavaScript/Reference/Template_literals)
2. 箭頭函式 (arrow function) [參考文件](https://developer.mozilla.org/zh-TW/docs/Web/JavaScript/Reference/Functions/Arrow_functions)
3. ES module & import / export [參考文件](https://www.casper.tw/development/2020/03/25/import-export/)
4. 陣列 / 物件的解構賦值(Destructuring Assignment) [參考文件](https://eyesofkids.gitbooks.io/javascript-start-from-es6/content/part4/destructuring.html)
5. 展開運算子 (Spread Operator) 與其餘運算子 (Rest Operator) [參考文件](https://developer.mozilla.org/zh-TW/docs/Web/JavaScript/Reference/Operators/Destructuring_assignment)
## 4/17
1. immutable 與 mutableLinks to an external site. [參考文件](https://howtocreateapps.com/mutable-and-immutable-types-in-javascript-with-examples/)
## 5/6 開始使用LeetCode 刷題
1.  [2703. Return Length of Arguments Passed]  
[延伸學習-剩餘參數語法Rest parameter](https://ithelp.ithome.com.tw/articles/10214394)  
[延伸學習-展開運算子Spread operator](https://ithelp.ithome.com.tw/articles/10214412)  
2. [2723. Add Two Promises]  
[延伸學習-Promise&async await](https://medium.com/@cherylrueichun/leetcode%E5%88%B7%E9%A1%8C-%E8%A4%87%E7%BF%92promise-async-await-93950d4f670b)
## 5/9
1.  [2621. async promise -Sleep]
[參考資料](https://medium.com/@cherylrueichun/leetcode%E5%88%B7%E9%A1%8C-%E8%A4%87%E7%BF%92promise-async-await-93950d4f670b)
## 5/10
1. [2704. To Be Or Not To Be] [參考資料](https://medium.com/@yachuh/leetcode-%E5%88%B7%E9%A1%8C%E7%AD%86%E8%A8%98-easy-2704-to-be-or-not-to-be-9e23d1a2011f)
## 5/11
1. [3110. Score of a String]
 [參考資料-String.charCodeAt()](https://www.runoob.com/jsref/jsref-charcodeat.html)
 [參考資料-Math.abs(x)](https://developer.mozilla.org/zh-CN/docs/Web/JavaScript/Reference/Global_Objects/Math/abs)
## 5/12
1. [2715. Timeout Cancellation]
   [參考資料 - setTimeout & clearTimeout](https://vocus.cc/article/6524f9e8fd89780001bee027)
## 5/13
1. [2695. Array Wrapper] 
[參考資料 - JavaScript Prototype ](https://www.shubo.io/javascript-prototype/)
[參考資料 - JavaScript Reduce](https://medium.com/unalai/%E8%AA%8D%E8%AD%98-javascript-reduce-940806267bfb)
[參考資料 - JSON.stringify() and JSON.parse()：變 JSON 和變物件](https://medium.com/itsems-frontend/javascript-json-stringify-and-json-parse-7a1251d3824c)
## 5/14
1. [2666. Allow One Function Call]
[參考資料 - Allow One Function Call](https://www.youtube.com/watch?v=m_SWhM9iX3s)
[延伸閱讀 -JavaScript - call，apply，bind](https://ithelp.ithome.com.tw/articles/10195896)
## 5/15
1. [git ignore使用](https://ithelp.ithome.com.tw/m/articles/10329189)
2. [Git flow](https://enginebai.medium.com/git-flow-60b9466e9942)
3. [CSS - background](https://developer.mozilla.org/zh-CN/docs/Web/CSS/background-attachment)
4. [CSS - flex、justify-content、align-items]
5. [Google-Fonts]
6. [box-shadow]
***
## 待完成筆記&每日閱讀筆記
1. Optional Chaining Operator (?.)Links to an external site. [參考文件](https://developer.mozilla.org/zh-TW/docs/Web/JavaScript/Reference/Operators/Optional_chaining)
2. ClosureLinks to an external site. [參考文件](https://developer.mozilla.org/zh-TW/docs/Web/JavaScript/Closures)
3. Class-componentLinks to an external site. [參考文件](https://legacy.reactjs.org/docs/components-and-props.html#function-and-class-components)
4. 學好 React 需要的前置基本功 [參考文件](https://ithelp.ithome.com.tw/articles/10292582)
5. React 起手式 — JS — ES6篇 [參考文件](https://milkmidi.medium.com/react-%E8%B5%B7%E6%89%8B%E5%BC%8F-js-es6%E7%AF%87-4b8f1a9e07e0)
6. Creating and nesting components
7. Writing markup with JSX
8. Adding styles
9. Displaying data
10. Conditional rendering
11. Rendering lists
12. Responding to events
13. Updating the screen
14. Using hooks
15. Sharing data between components
16. Break the UI into a component hierarchy
17. Build a static version in React
18. Find the minimal but complete representation of UI state
19. Identify where your state should live
20. Add inverse data flow
21. Outlet {children} Route 關係
22. useEffect、useState
23. useNavigate、useParams
24. useDispatch、useSelector
25. 物件解構
26. Promise、await、async try...catch...
27. html axios 導入 與 react axios 導入方式差別
28. require 與import差別
29. React幾大特性
30. Node.js React.js Next.js Express.js 
31. 使用Vite 的功能 [參考影片](https://www.youtube.com/watch?v=vj8KSZjPTUU)
***
//TODO
<a id="get-1"></a>
### [Return Length of Arguments Passed]
* …args 是一個剩餘參數，傳入的任何參數都可以被綁定為陣列
* 如果確定要做陣列處理 可以使用 …args  
<pre><code>function test() {
  console.log("notice the blank line before this function?");
}
</code></pre>  
3. 若不確定是要單純做 Array處理可以這樣做(傳入參數必須為Array，不然整個參數型態都會變掉)：  
<pre><code>
function argumentsLength (args){
	return args.length;
}
console.log(argumentsLength([{},null],"3") //3
</code></pre>
//TODO
