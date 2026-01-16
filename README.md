# base3yhyt
Tracking Average Gas Used by ERC20 Transfers
gas_used = [r.gasUsed for r in receipts if r.to == token]
print(sum(gas_used)/len(gas_used))
