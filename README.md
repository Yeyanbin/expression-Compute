
# 返回toReversePolishNotation和computeReversePolishNotation两个方法
- toReversePolishNotation 将中缀表达式转化为逆波兰表达式
- computeReversePolishNotation 计算逆波兰表达式
```js
npm i expression-compute

// in code
import ExpressionCompute from 'expression-compute';

const { toReversePolishNotation, computeReversePolishNotation } = useExpressionCompute(state, defaultFormValue);

console.log(computeReversePolishNotation(toReversePolishNotation('1+2+(3*2)/4')))
```