# cash

## Features

- Convert initially cash in USD  into several currencies (EUR , GBP)
- Can change the inatially curency
- Can change the currency in witch the cash is change



## Getting started

Converts an amount from one currency list un the devices currency into several other ones [EUR,GBP].

```
node bin/index.js <amount> <currency>

```
###Exemple

```

node bin/index.js 33 CAD

√ 25.59 (USD) US Dollar
√ 20.82 (EUR) Euro
√ 18.51 (GBP) Pound Sterling

```



## Commands

### -h (--help)
Display help message


### -s (--save)
Save currencies as default currencies

#### Example
Before using the --save Command
The cash is initially in USD and convert in Euro and Pound Sterling
```
node bin/index.js 33

√ 26.85 (EUR) Euro
√ 23.87 (GBP) Pound Sterling


```
Using the --save command

```
node bin/index.js --save eur
Saved default currencies to C:\Users\Carel\AppData\Local\cash-nodejs\Config\config.json

node bin/index.js 33

√ 40.56 (USD) US Dollar
√ 29.33 (GBP) Pound Sterling

 Conversion of EUR 33

```
'


### -v (--version)
Display version number
