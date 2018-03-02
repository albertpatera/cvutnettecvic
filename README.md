# BI-ZNF

## Cvičení 1

Varianta B projektu pro první cvičení předmětu BI-ZNF.

### Úkol

1. Naklonujte si projekt do adresáře vašeho lokálního webového serveru.
2. Jděte do složky projektu a nainstalujte ho pomocí přikazu ``composer install``.
3. Vyzkoušejte, že vidíte úvodní stránku pro příslušnou URL adresou (např. http://localhost/cviceni01).
4. Implmentujte chybějící bitové operace v modelu kalkulačky - */app/model/CalculatorManager.php*.
5. Ověřte vaši implementaci spuštěním jednotkových testů v projektu pomocí [Nette Tester](https://tester.nette.org/cs/)
```shell
vendor/bin/tester tests # Linux
# NEBO
vendor/bin/tester.bat tests # Windows
# NEBO
php vendor/nette/tester/src/tester tests # Přímo pomocí PHP
```

6. Vyzkoušejte postupně všechny binární operace přímo v prohlížeči pomocí GET parametrů URL:
	* Bitový součin (AND) - */and/\<number1\>/\<number2\>*
	* Bitový součet (OR) - */or/\<number1\>/\<number2\>*
	* Bitový posuv doleva - */left/\<number1\>/\<number2\>*
	* Bitový posuv doprava - */right/\<number1\>/\<number2\>*
7. Pro ty co to nestihnou na cvičení
	* Bitová nonekvivalence (XOR) - */xor/\<number1\>/\<number2\>*
	* Bitová ekvivalence (EQ) - */eq/\<number1\>/\<number2\>*
	* Bitová negace (NOT) - */not/\<number1\>*
	* Automatizované testy pro nově přidané operace
