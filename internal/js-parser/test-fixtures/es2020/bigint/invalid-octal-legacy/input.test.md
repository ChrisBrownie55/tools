# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `es2020 > bigint > invalid-octal-legacy`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	directives: Array []
	filename: "es2020/bigint/invalid-octal-legacy/input.js"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "script"
	syntax: Array []
	loc: Object {
		filename: "es2020/bigint/invalid-octal-legacy/input.js"
		end: Object {
			column: 0
			line: 2
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
				message: MARKUP {parts: Array [RAW_MARKUP {value: "A bigint can't be an octal"}]}
			}
			location: Object {
				filename: "es2020/bigint/invalid-octal-legacy/input.js"
				mtime: undefined
				sourceText: undefined
				end: Object {
					column: 6
					line: 1
				}
				start: Object {
					column: 6
					line: 1
				}
			}
		}
	]
	body: Array [
		JSExpressionStatement {
			loc: Object {
				filename: "es2020/bigint/invalid-octal-legacy/input.js"
				end: Object {
					column: 7
					line: 1
				}
				start: Object {
					column: 0
					line: 1
				}
			}
			expression: JSBigIntLiteral {
				value: "016432"
				loc: Object {
					filename: "es2020/bigint/invalid-octal-legacy/input.js"
					end: Object {
						column: 7
						line: 1
					}
					start: Object {
						column: 0
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

 es2020/bigint/invalid-octal-legacy/input.js:1:6 parse/js ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  ✖ A bigint can't be an octal

    016432n
          ^

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

✖ Found 1 problem

```