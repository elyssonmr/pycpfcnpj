Pycpfcnpj
=======

Description
-----------
Python module for brazilian register numbers for persons (CPF) and companies (CNPJ).

[![Build Status](https://travis-ci.org/matheuscas/pycpfcnpj.png?branch=master)](https://travis-ci.org/matheuscas/pycpfcnpj)

###Quick Start
To use pycpfcnpj is simples like as every python module shoud be!

```python
from pycpfcnpj import cpfcnpj
cpf_number = '11144477735'
cnpj_number = '11444777000161'
print cpfcnpj.validate(cpf_number)
print cpfcnpj.validate(cnpj_number)

Expected output:
>>>True
>>>True
```
Simple like that. =)

You can use, as well, the cpf and cnpj packages. The cpfcnpj is like a Facade to the other modules. Make yourself confortable.

Oh, fork and contribute either if you want to.

Obs.: There is no dependencies. 

In portuguese:
--------------

Módulo python para validar números de CPF e CNPJ.

### Como usar
```python
from pycpfcnpj import cpfcnpj
cpf_number = '11144477735'
cnpj_number = '11444777000161'
print cpfcnpj.validate(cpf_number)
print cpfcnpj.validate(cnpj_number)

Expected output:
>>>True
>>>True
```

Simples assim! Você também pode usar os pacotes internos que tratam em separado os números de CPF e CNPJ. O módulo 'cpfcnpj' é um tipo de interface para os módulos mais especificos e se encarrega de saber quando você está passando um CPF ou um CNPJ. 

Fique à vontade em contribuir com o projeto ou da maneira que quiser. Ah, sim: pure python (sem dependências ;) ).


