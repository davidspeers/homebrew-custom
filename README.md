# homebrew-custom
## My custom homebrew taps with extra options

To create a new tap:
1. Copy the ruby code of the formula you want
2. Make the desired changes
3. Call the formula with - brew install davidspeers/custom/<formula_name> (no .rb required)

https://github.com/Homebrew/brew/blob/master/docs/How-to-Create-and-Maintain-a-Tap.md

Changes:
* imagemagick -> changed --without-pango to --with-pango and added depends_on "pango"
