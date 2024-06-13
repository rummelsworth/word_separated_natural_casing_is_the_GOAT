# word_separated_natural_casing_is_the_GOAT

Try it. You will not regret it.

Specifically, the rules are:
- Use your language's non-alphanumeric "separator" character in your identifiers!
  - If your language doesn't have such a character, go away.
- Stop forcing yourself to case words-within-identifiers unnaturally!

For example:
- `WordSeparatedNaturalCasingIsTheGoat` (`PascalCase`) Dumb.
- `wordSeparatedNaturalCasingIsTheGoat` (`camelCase`) Not better.
- `word_separated_natural_casing_is_the_goat` (`snake_case`) Almost there.
- `word_separated_natural_casing_is_the_GOAT` YESSSS!!!

Some languages may have environments with constraints you have to accommodate (or even exploit).
For example, in Roslyn C#, the compiler warns against using a type identifier that starts with a lower-case letter.
That's fine, you can simply always upper-case that first letter of a type identifier.
This has a thin silver lining; if a nested type's natural name starts with a lower-case letter, then a member in the containing type can have that natural name as its identifier without provoking a compiler error.

In over a decade (and still going) of experience dealing with many casing styles in a complex STEM domain, word-separated natural casing is by far the most readable casing style I've encountered.
Especially in complex domains where acronyms are plentiful *and also* valuable for conveying necessary meaning.
