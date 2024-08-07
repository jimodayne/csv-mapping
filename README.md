# csv-mapping

This is a simple tool to map CSV files and validate them against a schema.

## Input

The input is a CSV file with the following columns:

payee | description | bsb | account_number | amount | reference

Example

| payee         | description | bsb     | account_number | amount  | reference         |
| ------------- | ----------- | ------- | -------------- | ------- | ----------------- |
| Ya Suo        | GAM         | 123-456 | 12345678       | 1000.00 | Rent for January  |
| Lee Sin       | TW          | 123456  | 123321123      | $50     | Rent for February |
| Captain Teemo | VKE         | 123 456 | 123 21123      | $1,500  | Rent for March    |
| Jax           | VKE         | 12345   | 123 211 231    | 200     | Rent for April    |
