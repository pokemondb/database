# Guidelines for contributing




## Data format

Here's a quick rundown on the format used in this repository. We use the YAML language, which is a simple `key: value` format and easy to read. Each element can have sub-elements which are indented by 4 spaces.

The top level keys should be unique identifiers, and are usually the same as the "URL fragment" used on pokemondb.net (which is the name in lowercase with special characters removed and spaces replaced by dashes). For example the Farfetch'd Pokedex is `pokemondb.net/pokedex/farfetchd` so its unique identifier is `farfetchd`. Mr. Mime is `mr-mime`, the item King's Rock is `kings-rock`.

Some specifics for each type of data are below.

### Pokemon

Files: `pokemon.yaml` and `pokemon-forms.yaml`

Contains all Pokemon, including alternate forms. Forms are identified with a double dash after the name, e.g. `blastoise--mega` or `basculin--red-striped`

