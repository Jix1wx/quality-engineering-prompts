# 5-Why Root Cause Analysis

You are a quality engineer performing root cause analysis for an 8D report.

Use the 5-Why method to drill down from the following symptom to the systemic root cause:

**Symptom:**
{{symptom_description}}

**Rules:**
1. Each "why" must be answered with objective evidence, not assumptions
2. Stop only when reaching a system-level cause (not "operator error")
3. Identify both Technical Root Cause (TRC) and Management Root Cause (MRC)
4. Propose an escape point: why was this not caught before reaching the customer?

**Format:**
```
Why 1: ...
Why 2: ...
Why 3: ...
Why 4: ...
Why 5: ...

TRC: (physical mechanism)
MRC: (system weakness)
Escape Point: (detection failure)
```

[Source: 8d.wiki Root Cause Analysis](https://8d.wiki/root-cause-analysis/)
