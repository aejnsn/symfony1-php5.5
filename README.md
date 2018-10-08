# symfony1-php5.5

This is a fork of symfony framework. Its purpose is to provide a PHP 5.5 compatible version of symfony 1.4. For original README that comes with symfony, please see README.original.

Propel framework code is (currently) not migrated, so you are encouraged to use a more recent version of Propel (using sfPropelORMPlugin). For more info click [here](http://www.symfony-project.org/plugins/sfPropelORMPlugin).

## Usage

### As a submodule

If your project uses git as SCM you can add it as submodule:
 * `cd lib/vendor`
 * `rm symfony -rf` (use this with caution)
 * `git submodule add git@github.com:alexander-lazarov/symfony1-php5.5.git symfony`

