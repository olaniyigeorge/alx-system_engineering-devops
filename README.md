### 0. Create alias `ls="rm *"`
**File:** `0-alias`
```bash
#!/bin/bash
alias ls="rm *"
```

### 1. Print hello `<username>`
**File:** `1-hello_you`
```bash
#!/bin/bash
echo "hello $(whoami)"
```

### 2. Add `/action` to PATH (at the end)
**File:** `2-path`
```bash
#!/bin/bash
export PATH="$PATH:/action"
```

### 3. Count number of directories in PATH
**File:** `3-paths`
```bash
#!/bin/bash
echo "$PATH" | tr ':' '\n' | grep -v '^$' | wc -l
```

### 4. List environment variables
**File:** `4-global_variables`
```bash
#!/bin/bash
printenv
```

### 5. List local variables, env vars, and functions
**File:** `5-local_variables`
```bash
#!/bin/bash
set
```

### 6. Create a new local variable `BEST=School`
**File:** `6-create_local_variable`
```bash
#!/bin/bash
BEST="School"
```

### 7. Create a global variable `BEST=School`
**File:** `7-create_global_variable`
```bash
#!/bin/bash
export BEST="School"
```

### 8. Add `128 + $TRUEKNOWLEDGE`
**File:** `8-true_knowledge`
```bash
#!/bin/bash
echo $((128 + TRUEKNOWLEDGE))
```

### 9. Divide `$POWER / $DIVIDE`
**File:** `9-divide_and_rule`
```bash
#!/bin/bash
echo $((POWER / DIVIDE))
```

### 10. Power: `$BREATH ** $LOVE`
**File:** `10-love_exponent_breath`
```bash
#!/bin/bash
echo $((BREATH ** LOVE))
```

### 11. Convert binary to decimal
**File:** `11-binary_to_decimal`
```bash
#!/bin/bash
echo "$((2#$BINARY))"
```

### 12. Print all 2-letter combinations, skip `oo`
**File:** `12-combinations`
```bash
#!/bin/bash
for l1 in {a..z}; do for l2 in {a..z}; do [[ "$l1$l2" != "oo" ]] && echo "$l1$l2"; done; done
```
**Note:** Must be ≤ 64 chars. Compress if needed:
```bash
for a in {a..z};do for b in {a..z};do [[ $a$b != oo ]]&&echo $a$b;done;done
```

### 13. Print float `$NUM` to 2 decimal places
**File:** `13-print_float`
```bash
#!/bin/bash
printf "%.2f\n" "$NUM"
```
