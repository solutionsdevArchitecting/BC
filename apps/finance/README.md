# Finance apps

- `Company.Finance.Core` — shared finance capability primitives.
- `Company.Finance.Payables` — accounts payable.
- `Company.Finance.Receivables` — accounts receivable.
- `Company.Finance.CashManagement` — cash and bank management.
- `Company.Finance.Consolidation` — consolidation processes.
- `Company.Finance.Tests` — finance app tests.

Keep ownership and dependencies explicit; shared behavior belongs in core only when multiple finance apps need it.
