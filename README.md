# Hello world javascript action

This action prints "Hello World" or "Hello" + the name of a person to greet the log.

##Inputs

### `who-to-greet`

**Required** The name of the persom to greet. Default `"World"`.

##Outputs

### `time`

The time we greeted you.

## Example usage

uses: actions/test-javascript-action@v1
with:
  who-to-greet: 'Mona the Octocat' 
