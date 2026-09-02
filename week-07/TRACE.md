# Week 07 trace

| Test fixture | Validation outcome | Expected status |
| --- | --- | --- |
| empty code | invalid | rejected |
| `ARCHIVED` | not in three-state list | rejected |
| both rejected | combined logical check | pass |
