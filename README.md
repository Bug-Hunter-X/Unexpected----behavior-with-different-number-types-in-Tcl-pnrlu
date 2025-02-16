This repository demonstrates a subtle bug in Tcl related to the behavior of the '==' operator when comparing numbers of different types. The included Tcl script showcases a scenario where comparing an integer with a floating point number using '==' results in an unexpected outcome due to type coercion. The solution provides a corrected approach to ensure accurate comparisons.

**Bug:**
The '==' operator in Tcl attempts to coerce operands to a common type before comparison, which can lead to unexpected comparisons, especially between integers and floating-point numbers. 

**Solution:**
The solution offers a more robust method for comparing numbers, explicitly handling type differences and achieving more precise results.