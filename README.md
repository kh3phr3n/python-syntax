# Python syntax highlighting script for Vim

Enhanced version of the original Python syntax highlighting script.
Based on `python.vim` from Vim 7.4 distribution by [Zvezdan Petkovic](https://github.com/zvezdan).

![python-syntax](https://cdn.nixsys.fr/static/github/python-syntax/preview.png)

## Features

Changes from the original `python.vim` are:

* [OFF] Highlight `self`, `cls` keywords
* [ON]  Highlight class, function parameters
* [ON]  Highlight standard operators: `~,!,^,&,|,*,/,%,+,-`
* [ON]  Highlight pseudo operators: `-=,//=,*=,&=,%=,+=,!=`
* 3 extras options:

    * `let python_self_cls_highlight = 1`
    * `let python_no_operator_highlight = 1`
    * `let python_no_parameter_highlight = 1`

* All the options can be switched on together (recommended).

    * `let python_highlight_all = 1`

## Color Scheme

* Vim keywords:

    * `pythonRepeat` `pythonConditional` `pythonInclude` `pythonTodo` `pythonComment` `pythonStatement`
    * `pythonEscape` `pythonSpaceError` `pythonException` `pythonExceptions` `pythonDoctest` `pythonDoctestValue`
    * `pythonNumber` `pythonString` `pythonRawString` `pythonBuiltin` `pythonFunction` `pythonClass` `pythonDecorator`
    * `pythonSelf` `pythonConstant` `pythonBrackets` `pythonOperator` `pythonExtraOperator` `pythonExtraPseudoOperator` `pythonClassParameters` `pythonFunctionParameters`

## How to install

The easiest installation method is to place `syntax/python.vim` script into your `~/.vim/syntax/` directory.
You can also use `Pathogen` or `Vundle` plugin managers in which case you can install the whole `kh3phr3n/python-syntax`
repository into the corresponding plugins directory.

## Informations

This plugin is strongly inspired by:

* [python-mode](https://github.com/klen/python-mode)
* [python-syntax](https://github.com/hdima/python-syntax)
* [pretty-vim-python](https://github.com/pfdevilliers/Pretty-Vim-Python)

## Contributors

* [Aramis Razzaghipour](https://github.com/arzg)

