# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `esprima > expression-assignment > migrated_0006`

```javascript
Program {
  comments: Array []
  corrupt: false
  diagnostics: Array []
  directives: Array []
  filename: 'input.js'
  hasHoistedVars: false
  interpreter: undefined
  mtime: undefined
  sourceType: 'script'
  syntax: Array []
  loc: Object {
    filename: 'input.js'
    end: Object {
      column: 0
      index: 8
      line: 2
    }
    start: Object {
      column: 0
      index: 0
      line: 1
    }
  }
  body: Array [
    ExpressionStatement {
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 7
          index: 7
          line: 1
        }
        start: Object {
          column: 0
          index: 0
          line: 1
        }
      }
      expression: AssignmentExpression {
        operator: '+='
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 7
            index: 7
            line: 1
          }
          start: Object {
            column: 0
            index: 0
            line: 1
          }
        }
        left: AssignmentIdentifier {
          name: 'x'
          loc: Object {
            filename: 'input.js'
            end: Object {
              column: 1
              index: 1
              line: 1
            }
            start: Object {
              column: 0
              index: 0
              line: 1
            }
          }
        }
        right: NumericLiteral {
          value: 42
          format: undefined
          loc: Object {
            filename: 'input.js'
            end: Object {
              column: 7
              index: 7
              line: 1
            }
            start: Object {
              column: 5
              index: 5
              line: 1
            }
          }
        }
      }
    }
  ]
}
```