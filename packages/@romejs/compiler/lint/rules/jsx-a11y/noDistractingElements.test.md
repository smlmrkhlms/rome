# `noDistractingElements.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/compiler/lint/rules/jsx-a11y/noDistractingElements.test.ts --update-snapshots` to update.

## `jsx a11y no distracting elements`

### `0`

```

 unknown:1 lint/jsx-a11y/noDistractingElements ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  ✖ Do not use blink elements as they can create visual accessibility issues and are deprecated.

    <blink />
    ^^^^^^^^^

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

✖ Found 1 problem

```

### `0: formatted`

```
<blink />;

```

### `1`

```

 unknown:1 lint/jsx-a11y/noDistractingElements ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  ✖ Do not use marquee elements as they can create visual accessibility issues and are deprecated.

    <marquee />
    ^^^^^^^^^^^

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

✖ Found 1 problem

```

### `1: formatted`

```
<marquee />;

```

### `2`

```
✔ No known problems!

```

### `2: formatted`

```
<div />;

```
