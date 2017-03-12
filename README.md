# better-exceptions

Pretty and more helpful exceptions in Python 2.x, automatically.

![Example screenshot of exceptions](screenshot.png)

## Usage

Install `better_exceptions` via pip:

```console
$ pip install better_exceptions
```

And import it somewhere:

```python
import better_exceptions
```

That's it!

### Advanced Usage

If you want to allow the entirety of values to be outputted instead of being truncated to a certain amount of characters:

```python
better_exceptions.MAX_LENGTH = None
```

# License
Copyright &copy; 2017, Josh Junon. Licensed under the [MIT license](LICENSE.txt).
