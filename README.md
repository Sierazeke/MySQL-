# MySQL

## Transakciju izolāciju līmeņa tabula

| Izolācijas Līmenis |  Dirty Reads  | Non-Repeating Reads | Phantom  Reads |  Lost Updates  |
|--------------------|---------------|---------------------|----------------|----------------|
|  READ  UNCOMMITED  |Nav iespējams❌| Nav iespējams❌  |Nav iespējams❌|Nav  iespējams❌|
|   READ  COMMITED   |Ir  iespējams✅| Nav iespējams❌  |Nav iespējams❌|Nav  iespējams❌|
|  REPEATABLE  READ  |Ir  iespējams✅|  Ir iespējams✅  |Nav iespējams❌|Nav  iespējams❌| 
|     SERIAZABLE     |Ir  iespējams✅|  Ir iespējams✅  |Ir iespējams✅ | Ir iespējams✅ | 
