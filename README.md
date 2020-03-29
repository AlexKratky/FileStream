# FileStream
FileSream is class that will enable thread safe file write & read. I am not the author of the the class, I just made some changes and change the protocol to panx://. The license is on the end of this page.

### Usage
The usage is easy, just add to filepath the panx:// protocol.

For example:
```php
file_put_contents("panx://text.txt", "Hello world!");
```

### License
See [safe-stream](https://github.com/nette/safe-stream) and [license](https://raw.githubusercontent.com/nette/safe-stream/master/license.md) on github.