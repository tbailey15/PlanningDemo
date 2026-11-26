# PlanningDemo

AG06 Planning and Reflection tutorial.

A small controller that packs pretend orientation kits (one folder and one label each). It compares:

- a fixed plan that fails because of a label shortage
- a plan fixed by hand after reading the failure
- a rule-based picker that chooses the next step from what it sees

The notebook also tests the four stop statuses (success, blocked, action_error, step_limit) and includes the practice runs and report.

## Run it

```
python -m pip install -r requirements.txt
```

Open `PlanningDemo.ipynb` and choose Restart and Run All. Only the Python standard library is used.
