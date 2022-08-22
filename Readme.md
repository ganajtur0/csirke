# Csirke :chicken:

## *[t͡ʃirke]* 

Interpreter for the [chicken esolang](https://esolangs.org/wiki/Chicken) in the **C** programming language.

## Installing

It should be OS-independent, but I've only built it on Linux machines so far.

Has no third-party dependencies that you'll have to link against except for the standard library.
```sh
git clone https://github.com/ganajtur0/csirke
cd csirke
make
```
the above code should result in **csirke.out** appearing in the directory.

## Usage

```sh
csirke.out /path/to/code
```
I wrote it so, that it accepts input from stdin, so if you'd like to try to run [the cat example](insert_link), in order to see something happen, make sure to pipe something into it like so:
```sh
cat file | csirke.out /path/to/cat.chn
```

## But why would you spend time on something like this?

It was fun and I'd learned a lot.

:chicken:
