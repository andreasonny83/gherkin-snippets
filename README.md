# Gherkin Snippets for Atom

![Cucumber logo](https://cucumber.io/images/cucumber-logo.svg)

## Install
Go to `atom > Preferences...` then search for Gherkin Snippets in the `Install` tab.

## Usage

![Cucumber logo](https://raw.githubusercontent.com/andreasonny83/gherkin-snippets/master/doc/feature.gif)

### Available snippets

##### Feature

```
Feature: ${1:Refund item}
  ${2:Sales assistants should be able to refund customers' purchases.
  This is required by the law, and is also essential in order to
  keep customers happy.}

  Scenario: ${3:Jeff returns a faulty microwave}
    Given ${4:Jeff has bought a microwave for £100}
    And ${5:He has a receipt}
    When ${6:He returns the microwave}
    Then ${7:Jeff should be refunded £100}
```

##### Scenario

```
Scenario: ${1:Jeff returns a faulty microwave}
  Given ${2:Jeff has bought a microwave for $100}
  And ${3:He has a receipt}
  When ${4:He returns the microwave}
  Then ${5:Jeff should be refunded $100}

```

##### Given

```
Given ${1:Jeff has bought a microwave for $100}
```

##### And

```
And ${1:He has a receipt}
```

##### When

```
When ${1:He returns the microwave}
```

##### Then

```
Then ${1:Jeff should be refunded £100}
```

##### Background

```
Background:
  Given ${1:A £100 microwave was sold on 2015-11-03}
  And ${2:Today is 2015-11-18}
```

##### Example

```
Examples:
  | ${1:weight} | ${2:energy} | ${3:protein} |
  | ${4:450}    | ${5:26500}  | ${6:215}     |
```

##### Rules

```
Rules:
- ${1:Customer must present proof of purchase}
- ${2:Purchase must be less than 30 days ago}
```


## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request

## License

[MIT License](https://github.com/andreasonny83/gherkin-snippets/LICENSE.md)
