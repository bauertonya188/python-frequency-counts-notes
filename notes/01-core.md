# Count repeated values: implementation

## What the example does

Counter provides linear-time counting. Inputs here are strings so the JSON object keys have an unambiguous representation.

The public function is `solve(value)`. The JSON input contract can be seen in this concrete example:

```json
[
  "apple",
  "pear",
  "apple"
]
```

Expected result:

```json
{
  "apple": 2,
  "pear": 1
}
```

Run `python3 example.py` for the Python representation of the result. `solution.py` contains the full implementation and can also be imported by another script.

## Scope

The function implements exactly the behavior described above. It does not perform network or filesystem access. Python exceptions indicate unsupported input; the next lesson turns them into a command-line error response. Review the limitations before reusing it in an application.
