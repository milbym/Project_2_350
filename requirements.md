couchdb requires Erlang OTP,
ICU for unicode support
OpenSSL
Mozilla Spidermonkey ot run web assembly
GNU Make and the GNU compiler
help2man to produce the help command (if installing with docs)
Python 3.6 >= for docs and tests
Java for nouveau

They can all be installed with
```bash
sudo apt-get --no-install-recommends -y install \
    build-essential pkg-config erlang \
    libicu-dev libmozjs185-dev
```