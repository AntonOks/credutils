## credutils

A set of command-line tools to manipulate the Windows Credential Manager with
UTF-8 names.

#### writecred

    Usage: writecred <credential-name> ( <filename> | - )

Store in a credential with the specfied `<credential-name>` the contents of the
specfied `<filename>` if specified or standard input if `-` was specified.

#### readcred

    Usage: readcred <credential-name>

Write the contents of the credential with the specified `<credential-name>` to
standard output.

#### delcred

    Usage: delcred <credential-name>

Deletes the credential with the specified `<credential-name>`.

## License

Copyright (C) 2015 Masud Rahman

Permission is hereby granted, free of charge, to any person obtaining a copy of
this software and associated documentation files (the "Software"), to deal in
the Software without restriction, including without limitation the rights to
use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies
of the Software, and to permit persons to whom the Software is furnished to do
so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

