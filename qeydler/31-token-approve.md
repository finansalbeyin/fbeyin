# Token approve və limitsiz icazə

ERC-20 tokenlərini DEX və ya protokola vermək üçün əvvəlcə kontrakta `approve` (xərcləmə icazəsi) verilir.

- Çox tətbiq defolt olaraq **limitsiz** icazə istəyir — kontrakt sındırılsa, bütün həmin tokenlər oğurlana bilər.
- Mümkün olduqda yalnız lazım olan məbləğə icazə ver.
