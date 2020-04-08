# 計算機

**等級:** 1-初學者

計算機不僅是現在最有用的工具之一，而且還是理解應用程式中 UI 和事件處理的一種很好的方式。 在這個問題中，你將建立一個計算機，該計算機支援整數的基本算術計算。

UI 外觀風格由你決定的，所以運用你的想象力和創造力！ 你可能也會發現值得花時間在你的行動裝置上體驗一下這個計算機應用程式，以便更好地理解基本功能和異常的邊緣情況。

### 限制

- 你不可以使用 `eval()` 函式來執行計算

## 使用者故事

-   [ ] 使用者可以看到當前輸入顯示的數字或上次操作的結果
-   [ ] 使用者可以看到一個輸入面板包含有以下的按鈕，數字0-9，計算操作-’+’ ，’-’ ，’*’ ，’/’ 和 ’=’ ，一個’c’按鈕(用來做清除)和一個’ AC’按鈕(清除所有)
-   [ ] User can enter numbers as sequences up to 8 digits long by clicking on
digits in the entry pad. Entry of any digits more than 8 will be ignored.
-   [ ] User can click on an operation button to display the result of that
operation on:
    * the result of the preceding operation and the last number entered OR
    * the last two numbers entered OR
    * the last number entered
-   [ ] User can click the 'C' button to clear the last number or the last
operation. If the users last entry was an operation the display will be
updated to the value that preceded it.
-   [ ] User can click the 'AC' button to clear all internal work areas and
to set the display to 0.
-   [ ] User can see 'ERR' displayed if any operation would exceed the 
8 digit maximum.

## Bonus features

-   [ ] User can click a '+/-' button to change the sign of the number that is
currently displayed.
-   [ ] User can see a decimal point ('.') button on the entry pad to that 
allows floating point numbers up to 3 places to be entered and operations to
be carried out to the maximum number of decimal places entered for any one
number.

## Useful links and resources

- [Calculator (Wikipedia)](https://en.wikipedia.org/wiki/Calculator)
- [MDN](https://developer.mozilla.org/en-US/)

## Example projects

- [Javascript Calculator](https://codepen.io/giana/pen/GJMBEv)
- [React Calculator](https://codepen.io/mjijackson/pen/xOzyGX)
- [Javascript-CALC](https://github.com/x0uter/javascript-calc)
