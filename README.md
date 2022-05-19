# kotlin-money
Small utility library to help with working payment amounts in the paylike ecosystem.

## Features

Currently this package only supports a fraction of our JavaScript library. We may extend
functionality if we can find usecases for it.

## Usage

// TODO
```kotlin 
import 'package:paylike_money/dart_money.dart';

void main() {
  var eur = PaylikeCurrencies().byCode(CurrencyCode.EUR);
  var amount = Money.fromDouble(eur, 12.5);
  print(amount.toJSONBody());
}
```