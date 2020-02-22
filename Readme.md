# C-Kermit
## Official sources [Here](http://www.kermitproject.org/ck90.html)

## I created this repository in the case that building C-Kermit wasn't working due to `stdin->_cnt` errors, the fix is relatively simple, simply cloning this repo will provide you with the fixed source

## Compiling

#### Haha, this patch is _only_ tested for linux, the huge amounts of systems C-Kermits supports is _not_ tested with this patch
#### That being said, I'm sorry if this doesn't fix your compilation problem with your ancient technology
### How to compile:
Clone the repository

Execute `make linux`

The binary `wermit` should be created

**Compiling for anything that's not linux has not been tested!**

## Notes

If you're having link problems with compiling, this command works on my Raspberry Pi:

`make linux LNKFLAGS="-lcurses -lcrypt -lresolv"`


