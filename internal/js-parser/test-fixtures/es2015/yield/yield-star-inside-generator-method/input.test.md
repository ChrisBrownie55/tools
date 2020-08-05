# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `es2015 > yield > yield-star-inside-generator-method`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	diagnostics: Array []
	directives: Array []
	filename: "es2015/yield/yield-star-inside-generator-method/input.js"
	hasHoistedVars: true
	interpreter: undefined
	mtime: undefined
	sourceType: "script"
	syntax: Array []
	loc: Object {
		filename: "es2015/yield/yield-star-inside-generator-method/input.js"
		end: Object {
			column: 34
			line: 1
		}
		start: Object {
			column: 0
			line: 1
		}
	}
	body: Array [
		JSVariableDeclarationStatement {
			loc: Object {
				filename: "es2015/yield/yield-star-inside-generator-method/input.js"
				end: Object {
					column: 34
					line: 1
				}
				start: Object {
					column: 0
					line: 1
				}
			}
			declaration: JSVariableDeclaration {
				kind: "var"
				loc: Object {
					filename: "es2015/yield/yield-star-inside-generator-method/input.js"
					end: Object {
						column: 34
						line: 1
					}
					start: Object {
						column: 0
						line: 1
					}
				}
				declarations: Array [
					JSVariableDeclarator {
						id: JSBindingIdentifier {
							name: "x"
							loc: Object {
								filename: "es2015/yield/yield-star-inside-generator-method/input.js"
								identifierName: "x"
								end: Object {
									column: 5
									line: 1
								}
								start: Object {
									column: 4
									line: 1
								}
							}
						}
						loc: Object {
							filename: "es2015/yield/yield-star-inside-generator-method/input.js"
							end: Object {
								column: 33
								line: 1
							}
							start: Object {
								column: 4
								line: 1
							}
						}
						init: JSObjectExpression {
							loc: Object {
								filename: "es2015/yield/yield-star-inside-generator-method/input.js"
								end: Object {
									column: 33
									line: 1
								}
								start: Object {
									column: 8
									line: 1
								}
							}
							properties: Array [
								JSObjectMethod {
									kind: "method"
									key: JSStaticPropertyKey {
										value: JSIdentifier {
											name: "test"
											loc: Object {
												filename: "es2015/yield/yield-star-inside-generator-method/input.js"
												identifierName: "test"
												end: Object {
													column: 15
													line: 1
												}
												start: Object {
													column: 11
													line: 1
												}
											}
										}
										loc: Object {
											filename: "es2015/yield/yield-star-inside-generator-method/input.js"
											end: Object {
												column: 15
												line: 1
											}
											start: Object {
												column: 11
												line: 1
											}
										}
									}
									loc: Object {
										filename: "es2015/yield/yield-star-inside-generator-method/input.js"
										end: Object {
											column: 31
											line: 1
										}
										start: Object {
											column: 10
											line: 1
										}
									}
									head: JSFunctionHead {
										async: false
										generator: true
										hasHoistedVars: false
										params: Array []
										rest: undefined
										returnType: undefined
										thisType: undefined
										typeParameters: undefined
										loc: Object {
											filename: "es2015/yield/yield-star-inside-generator-method/input.js"
											end: Object {
												column: 18
												line: 1
											}
											start: Object {
												column: 16
												line: 1
											}
										}
									}
									body: JSBlockStatement {
										directives: Array []
										loc: Object {
											filename: "es2015/yield/yield-star-inside-generator-method/input.js"
											end: Object {
												column: 31
												line: 1
											}
											start: Object {
												column: 19
												line: 1
											}
										}
										body: Array [
											JSExpressionStatement {
												loc: Object {
													filename: "es2015/yield/yield-star-inside-generator-method/input.js"
													end: Object {
														column: 29
														line: 1
													}
													start: Object {
														column: 21
														line: 1
													}
												}
												expression: JSYieldExpression {
													delegate: true
													loc: Object {
														filename: "es2015/yield/yield-star-inside-generator-method/input.js"
														end: Object {
															column: 29
															line: 1
														}
														start: Object {
															column: 21
															line: 1
														}
													}
													argument: JSReferenceIdentifier {
														name: "v"
														loc: Object {
															filename: "es2015/yield/yield-star-inside-generator-method/input.js"
															identifierName: "v"
															end: Object {
																column: 29
																line: 1
															}
															start: Object {
																column: 28
																line: 1
															}
														}
													}
												}
											}
										]
									}
								}
							]
						}
					}
				]
			}
		}
	]
}
```

### `diagnostics`

```
✔ No known problems!

```