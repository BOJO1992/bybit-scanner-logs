Usage: bybit-trader <command> [args]

  status                  Print mode + config summary
  probe                   Test read-only Bybit connectivity
  account                 Fetch account snapshot (wallet + positions)
  market --symbol <SYMB>  Fetch market snapshot (klines)
  decision --symbol <SYMB> Generate trade idea and order plan (manual trading)
  plan <json>             Build an OrderPlan from a JSON PlanInput
  preflight               Check execution readiness and system state

  NOTE: Execution commands (confirm, execute) are disabled for manual trading workflow.
        Use decision command to generate trade ideas and place orders manually.
