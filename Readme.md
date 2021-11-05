# C-Kermit
## Official sources [Here](http://www.kermitproject.org/ck90.html)

## I created this repository in the case that building C-Kermit wasn't working due to `stdin->_cnt` errors, the fix is relatively simple, simply cloning this repo will provide you with the fixed source

## Compiling

### How to compile:
Clone the repository

Execute `make linux`

The binary `wermit` should be created

**Compiling for anything that's not linux has not been tested!**

## Notes

If you're having link problems with compiling, this command works on my Raspberry Pi:

`make linux LIBS="-lcurses -lcrypt -lresolv"`

You can clone the original C-Kermit source by using the branch `NOFIX`:

`git clone https://github.com/AmFobes/CKermit.git --branch=NOFIX`
