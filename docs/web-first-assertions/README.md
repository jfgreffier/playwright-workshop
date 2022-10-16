# Web-first assertions
## It's totally Jest expect
Playwright Test uses [expect](https://jestjs.io/docs/expect) library for test assertions. This library provides a lot of matchers like `toEqual`, `toContain`, `toMatch`, `toMatchSnapshot` and many more.
https://jestjs.io/docs/expect

## Examples 👩‍💻
### Classic expect
Expect from Jest
https://jestjs.io/docs/expect

### toContainText(), ...
```js
expect(locator).toBeChecked()
expect(locator).toBeDisabled()
expect(locator).toBeEditable()
expect(locator).toBeEmpty()
expect(locator).toBeEnabled()
expect(locator).toBeFocused()
expect(locator).toBeHidden()
expect(locator).toBeVisible()
expect(locator).toContainText(text)
expect(locator).toHaveAttribute(name)
expect(locator).toHaveClass(expected)
expect(locator).toHaveCount(count)
expect(locator).toHaveCSS(name, value)
expect(locator).toHaveId(id)
expect(locator).toHaveJSProperty(name, value)
expect(locator).toHaveText(expected)
expect(page).toHaveTitle(title)
expect(page).toHaveURL(url)
expect(locator).toHaveValue(value)
expect(page).toHaveScreenshot()
expect(locator).toHaveScreenshot()
```

Usable with Jest, Vitest, Mocha, Playwright Test, ...

### toMatchSnapshot

References  
https://playwright.dev/docs/test-assertions  
