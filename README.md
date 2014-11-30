#Localizable

Here you can help me to translate my apps in all languages.

### How it works

This is a git repository, if you are familiar with git you already know how it works, if you don't know git you can download the contents of this repository and e-mail me the translated files, I'll upload them to this git repository ASAP.

How files are organized:

	|PROJECT_NAME
	|--COUNTRY_CODE.jproj
	|----Localizable.strings

exemple:

	|Omnistat
	|--en.lproj
	|----Localizable.strings
	|--fr.lproj
	|----Localizable.strings

The `.strings` files contains the strings key and value like this:

	/* COMMENT_ABOUT_THE_STRING */
	"STRING_KEY" = "STRING_VALUE";


To translate a project:

* make a new directory named COUNTRY_CODE.jproj
* copy one of the existing Localizable.strings files in this directory
* then JUST translate the STRING_VALUE in your COUNTRY_CODE language


##Contact

me@mathieubolard.com<br />
http://mathieubolard.com<br />
http://twitter.com/mattlawer