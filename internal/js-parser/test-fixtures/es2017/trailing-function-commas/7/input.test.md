# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `es2017 > trailing-function-commas > 7`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	directives: Array []
	filename: "es2017/trailing-function-commas/7/input.js"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "script"
	syntax: Array []
	loc: Object {
		filename: "es2017/trailing-function-commas/7/input.js"
		end: Object {
			column: 8
			line: 1
		}
		start: Object {
			column: 0
			line: 1
		}
	}
	diagnostics: Array [
		Object {
			origins: Array [Object {category: "parse/js"}]
			description: Object {
				advice: Array []
				category: "parse/js"
				message: MARKUP {parts: Array [RAW_MARKUP {value: "Unexpected token"}]}
			}
			location: Object {
				filename: "es2017/trailing-function-commas/7/input.js"
				mtime: undefined
				sourceText: undefined
				end: Object {
					column: 7
					line: 1
				}
				start: Object {
					column: 7
					line: 1
				}
			}
		}
	]
	body: Array [
		JSExpressionStatement {
			loc: Object {
				filename: "es2017/trailing-function-commas/7/input.js"
				end: Object {
					column: 8
					line: 1
				}
				start: Object {
					column: 0
					line: 1
				}
			}
			expression: JSStringLiteral {
				value: "foo"
				loc: Object {
					filename: "es2017/trailing-function-commas/7/input.js"
					end: Object {
						column: 6
						line: 1
					}
					start: Object {
						column: 1
						line: 1
					}
				}
			}
		}
	]
}
```

### `diagnostics`

```

 es2017/trailing-function-commas/7/input.js:1:7 parse/js ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  ✖ Unexpected token

    ('foo',)
           ^

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

✖ Found 1 problem

```
