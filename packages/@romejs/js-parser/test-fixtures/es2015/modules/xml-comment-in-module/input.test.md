# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `es2015 > modules > xml-comment-in-module`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	diagnostics: Array []
	directives: Array []
	filename: "input.js"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "module"
	syntax: Array []
	loc: Object {
		filename: "input.js"
		end: Object {
			column: 0
			index: 12
			line: 2
		}
		start: Object {
			column: 0
			index: 0
			line: 1
		}
	}
	body: Array [
		JSExpressionStatement {
			loc: Object {
				filename: "input.js"
				end: Object {
					column: 11
					index: 11
					line: 1
				}
				start: Object {
					column: 0
					index: 0
					line: 1
				}
			}
			expression: JSBinaryExpression {
				operator: "<"
				loc: Object {
					filename: "input.js"
					end: Object {
						column: 11
						index: 11
						line: 1
					}
					start: Object {
						column: 0
						index: 0
						line: 1
					}
				}
				left: JSReferenceIdentifier {
					name: "foo"
					loc: Object {
						filename: "input.js"
						identifierName: "foo"
						end: Object {
							column: 3
							index: 3
							line: 1
						}
						start: Object {
							column: 0
							index: 0
							line: 1
						}
					}
				}
				right: JSUnaryExpression {
					operator: "!"
					prefix: true
					loc: Object {
						filename: "input.js"
						end: Object {
							column: 11
							index: 11
							line: 1
						}
						start: Object {
							column: 5
							index: 5
							line: 1
						}
					}
					argument: JSUpdateExpression {
						operator: "--"
						prefix: true
						loc: Object {
							filename: "input.js"
							end: Object {
								column: 11
								index: 11
								line: 1
							}
							start: Object {
								column: 6
								index: 6
								line: 1
							}
						}
						argument: JSReferenceIdentifier {
							name: "bar"
							loc: Object {
								filename: "input.js"
								identifierName: "bar"
								end: Object {
									column: 11
									index: 11
									line: 1
								}
								start: Object {
									column: 8
									index: 8
									line: 1
								}
							}
						}
					}
				}
			}
		}
	]
}
```
