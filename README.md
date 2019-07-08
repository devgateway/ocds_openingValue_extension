# Opening Value

We need a local extension for Direccion Nacional de Vialidad Argentina (DNV) to adjust values to opening date due to inflation:

* Opening Value

This extension will allow DNV to show more precise information about initial value of the project adjusted to the opening date of tender process.

## Worked example
The "openingValue" extension will be a field that will be added at planning.budget to show the value of the project adjusted to the opening date by a coefficient of inflation.

```json
{
	"openingValue" : {
		"amount" : 446578912.61,
		"coefficient" : 1.21,
		"currency" : "ARS"
	}
}

```
