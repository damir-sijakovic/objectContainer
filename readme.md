# PHP Object Container

Stores objects into static associative array.
Without any unnecessary overcomplicated features.  

### Install

        composer require dsijak/container

### Usage

#### Add object to container:

        class One{};
        Dsijak\container('one', new One);

#### Get object from container:

        $one = Dsijak\container('one');

#### Empty container:

        Dsijak\container();

     
### Licence
MIT
