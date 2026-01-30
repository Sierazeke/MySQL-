# MySQL

## Transakciju izolāciju līmeņa tabula

| Izolācijas Līmenis |  Dirty Reads  | Non-Repeating Reads | Phantom  Reads |  Lost Updates  |
|--------------------|---------------|---------------------|----------------|----------------|
|  READ  UNCOMMITED  |Ir  iespējams✅|    Ir iespējams✅  |Ir iespējams✅ |Ir  iespējams✅ |
|   READ  COMMITED   |Nav iespējams❌|   Ir iespējams✅   |Ir iespējams✅ | Ir iespējams✅ |
|  REPEATABLE  READ  |Nav iespējams❌|  Nav iespējams❌   |Nav iespējams❌| Ir iespējams✅ | 
|     SERIAZABLE     |Nav iespējams❌|   Nav iespējams❌  |Nav iespējams❌ |Nav iespējams❌| 
