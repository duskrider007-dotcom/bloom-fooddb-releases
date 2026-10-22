Bloom food database releases

Every release carries three files:

- foods-<version>.db.zst: the compressed SQLite food database Bloom reads;
- manifest.json: the version, sizes, SHA-256 checksums and row counts;
- manifest.json.sig: the Ed25519 signature of the exact manifest.json bytes.

Food data: Health Canada Canadian Nutrient File (Open Government Licence - Canada); USDA FoodData Central (public domain); Open Food Facts (Open Database License, openfoodfacts.org).

The database as a whole is offered under the Open Database License (ODbL) 1.0, as Open Food Facts' licence requires.
