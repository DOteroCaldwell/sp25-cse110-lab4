##Part 1##

1. line 5 prints `values added:  20`
2. line 13 prints `final result:  20`
3. var has no block scope and is hoisted at the start of each function, but assigned later. This can lead to confusing behavior and should be avoided.
4. line 5 prints `values added:  20`
5. line 13 prints nothing as the script returns an error. This happens because `result` is out of scope outside of the `if(add)` block.
6. line 5 prints nothing as the script returns an error. This happens because `result` is a constant and `result = num1 + num2;` attempts to illegaly reassign it.
7. line 13 prints nothing as the script returns an error. This happens because `result` is a constant and `result = num1 + num2;` attempts to illegaly reassign it.