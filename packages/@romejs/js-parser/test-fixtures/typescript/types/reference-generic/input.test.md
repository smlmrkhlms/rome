# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `typescript > types > reference-generic`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	diagnostics: Array []
	directives: Array []
	filename: "input.ts"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "module"
	syntax: Array ["ts"]
	loc: Object {
		filename: "input.ts"
		end: Object {
			column: 0
			index: 22
			line: 2
		}
		start: Object {
			column: 0
			index: 0
			line: 1
		}
	}
	body: Array [
		JSVariableDeclarationStatement {
			loc: Object {
				filename: "input.ts"
				end: Object {
					column: 21
					index: 21
					line: 1
				}
				start: Object {
					column: 0
					index: 0
					line: 1
				}
			}
			declaration: JSVariableDeclaration {
				kind: "let"
				loc: Object {
					filename: "input.ts"
					end: Object {
						column: 21
						index: 21
						line: 1
					}
					start: Object {
						column: 0
						index: 0
						line: 1
					}
				}
				declarations: Array [
					JSVariableDeclarator {
						id: JSBindingIdentifier {
							name: "x"
							loc: Object {
								filename: "input.ts"
								end: Object {
									column: 20
									index: 20
									line: 1
								}
								start: Object {
									column: 4
									index: 4
									line: 1
								}
							}
							meta: JSPatternMeta {
								definite: undefined
								loc: Object {
									filename: "input.ts"
									end: Object {
										column: 20
										index: 20
										line: 1
									}
									start: Object {
										column: 4
										index: 4
										line: 1
									}
								}
								typeAnnotation: TSTypeReference {
									loc: Object {
										filename: "input.ts"
										end: Object {
											column: 20
											index: 20
											line: 1
										}
										start: Object {
											column: 7
											index: 7
											line: 1
										}
									}
									typeName: JSReferenceIdentifier {
										name: "Array"
										loc: Object {
											filename: "input.ts"
											identifierName: "Array"
											end: Object {
												column: 12
												index: 12
												line: 1
											}
											start: Object {
												column: 7
												index: 7
												line: 1
											}
										}
									}
									typeParameters: TSTypeParameterInstantiation {
										loc: Object {
											filename: "input.ts"
											end: Object {
												column: 20
												index: 20
												line: 1
											}
											start: Object {
												column: 12
												index: 12
												line: 1
											}
										}
										params: Array [
											TSNumberKeywordTypeAnnotation {
												loc: Object {
													filename: "input.ts"
													end: Object {
														column: 19
														index: 19
														line: 1
													}
													start: Object {
														column: 13
														index: 13
														line: 1
													}
												}
											}
										]
									}
								}
							}
						}
						init: undefined
						loc: Object {
							filename: "input.ts"
							end: Object {
								column: 20
								index: 20
								line: 1
							}
							start: Object {
								column: 4
								index: 4
								line: 1
							}
						}
					}
				]
			}
		}
	]
}
```
