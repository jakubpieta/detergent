Detergent - An emulsifying Erlang SOAP library
==============================================

## Installing
    $ git clone git://github.com/devinus/detergent.git
    $ cd detergent
    $ git submodule init
    $ git submodule update
    $ make

## Testing
    $ erl -pa ebin deps/erlsom/ebin
    > inets:start().
    > l(detergent).
    > detergent:qtest().