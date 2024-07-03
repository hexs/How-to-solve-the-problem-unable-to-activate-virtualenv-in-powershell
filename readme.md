# How to solve the problem unable to activate virtualenv in powershell

-----------------------------------------------

## problem

* activate virtualenv: an error occurred

![-](image/1.jpg "-")

## solve

### step 1

* open new Windows PowerShell
* run as admin
  ![-](image/2.jpg "-")

### step 2

```sh
Get-ExecutionPolicy
Set-ExecutionPolicy RemoteSigned
y
 ```

![-](image/3.jpg "-")

### step 3

* new activate virtualenv

```sh
venv\Scripts\activate
```

![-](image/4.jpg "-")

