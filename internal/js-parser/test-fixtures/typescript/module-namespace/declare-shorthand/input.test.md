# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `typescript > module-namespace > declare-shorthand`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	diagnostics: Array []
	directives: Array []
	filename: "typescript/module-namespace/declare-shorthand/input.ts"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "module"
	syntax: Array ["ts"]
	loc: Object {
		filename: "typescript/module-namespace/declare-shorthand/input.ts"
		end: Object {
			column: 0
			line: 2
		}
		start: Object {
			column: 0
			line: 1
		}
	}
	body: Array [
		TSModuleDeclaration {
			id: JSStringLiteral {
				value: "m"
				loc: Object {
					filename: "typescript/module-namespace/declare-shorthand/input.ts"
					end: Object {
						column: 18
						line: 1
					}
					start: Object {
						column: 15
						line: 1
					}
				}
			}
			body: undefined
			declare: true
			global: undefined
			loc: Object {
				filename: "typescript/module-namespace/declare-shorthand/input.ts"
				end: Object {
					column: 19
					line: 1
				}
				start: Object {
					column: 0
					line: 1
				}
			}
		}
	]
}
```

### `diagnostics`

```
✔ No known problems!

```