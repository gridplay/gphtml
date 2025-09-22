# GPHtml
## Fork of LaravelCollective's HTML package for Laravel

```
composer require gridplay/gphtml
```

Did this mostly to keep the project alive and to get rid of those composer warnings.

Yes i know about spartie but that package docs is confusing, not facade friendly and seem to not have the Form::open i want

No code changes yet just a change from v6 to v7 and Class name change from Collective to GP

Oh and PHP min is 8.2 and Laravel min version is 11.0

Credits to LaravelCollective for making this package and allowing me to maintane it in a fork

### 7.0.3 - Sept 22 2025
- I see that Laravel 10 is end of life now so this package will NOT suppport EoL's
- Removed Laravel 10 support
- Added support for Laravel 13 if they dont skip the unlucky number
- Left the LaravelCollective's branch so that this fork is on its own

### 7.0.2 - Nov 22 2024
- Changed Laravel's min to 10 (sorry 9 users but time to upgrade)
- Added support for the upcoming 12 (hopefully no code changes needs to be made)
- Min php is now 8.2
- Composer's minimum-stability is set to stable
- Took out "test" stuff because well, the code works, no need to run tests on it

