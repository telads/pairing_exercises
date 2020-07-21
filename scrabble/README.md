### Task

Given a word, compute the scrabble score for that word.

### Acceptance Criteria

```ruby
Scrabble.new('').score # => 0
Scrabble.new(" \t\n").score # => 0
Scrabble.new(nil).score # => 0
Scrabble.new('a').score # => 1
Scrabble.new('f').score # => 4
Scrabble.new('street').score # => 6
Scrabble.new('quirky').score # => 22
Scrabble.new('OXYPHENBUTAZONE').score # => 41
```

Each `Scrabble` method should be no more than 5 lines and contain no more than 5 operations.

##### Letter Values

You'll need these:

| Letter                        | Value  |
| ----                          |  ----  |
| A, E, I, O, U, L, N, R, S, T  |     1  |
| D, G                          |     2  |
| B, C, M, P                    |     3  |
| F, H, V, W, Y                 |     4  |
| K                             |     5  |
| J, X                          |     8  |
| Q, Z                          |     10 |

Example
"cabbage" should be scored as worth 14 points:

- 3 points for C
- 1 point for A, twice
- 3 points for B, twice
- 2 points for G
- 1 point for E

And to total:

```
3 + 2x1 + 2x3 + 2 + 1
= 3 + 2 + 6 + 3
= 14
```


##### Extensions
> You can play a double or a triple letter.

> You can play a double or a triple word.

##### To run tests

In the project directory `/scrabble` run

```bash
$ m-spec ./spec/scrabble_spec.rb
```

Go to m-spec [documentation](https://github.com/dearshrewdwit/m-spec).

##### Source
Inspired by Exercism Ruby Track
