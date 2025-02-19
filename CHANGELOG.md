# Changelog

All notable changes to `laravel-health-env-vars` will be documented in this file.

## 1.5.0 - 2023-01-14

### added

- support for PHP `8.2`
- chore: use Laravel Pint

## 1.4.0 - 2022-11-26

### added

- add `requireVarsForEnvironments`: check if some variables have been set only in the given environments (
  e.g. `['qa', 'production']`)
- more comments in the code

### fix

- typos

## 1.3.1 - 2022-10-05

### fixed

- change condition to fix PHPStan check

## 1.3.0 - 2022-10-05

### added

- improve documentation adding *Caveats* section in README.md

## 1.2.3 - 2022-03-24

### fix

- typo (again...)

## 1.2.1 - 2022-03-03

### fixed

- remove duplicates from README.md
- update run-test GitHub action - same specs as spatie/laravel-health

## 1.2.0 - 2022-03-01

### added

- Laravel 8 support

## 1.0.1 - 2022-02-28

### fixed

- translations didn't work

## 1.0.0 - 2022-02-27

- initial release
