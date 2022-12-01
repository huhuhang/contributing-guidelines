# GitHub Copilot Tips

You can use some tips to get the most out of GitHub Copilot.

## Writing Comments First

Writing comments in your code can help Copilot understand what you're trying to do. For example, if you're trying to create a function that adds two numbers, you can write a comment like this:

```js
// Add two numbers (GitHub Copilot adds the following)
function add(a, b) {
  return a + b;
}
```

Copilot also works well when you write step verification scripts.

```bash
# check if the file exists (GitHub Copilot adds the following)
test -f ~/hello.py
# check if the file contains the string "Hello World"
grep "Hello World" ~/hello.py
```
