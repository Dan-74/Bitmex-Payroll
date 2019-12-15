# Bitmex-Payroll

An useful script based on CCXT and PYOTP modules that allow you to set an automated payment from Bitmex on a specific date or when your Bitmex wallet exceed a certain amount.
It creates a Payroll to use with bot. 
You can set-up an Event Manager or AWS schedule to run it on daly basis and at your choose date you will recieve automatically a paiment from to your external wallet.

NOTE1 : All input amounts are in SATOSHI.

NOTE2 : Each payment has to be confirmed by mail (time limit 30 min) or will be canceled.

CCXT: https://github.com/ccxt/ccxt
PYOTP: https://github.com/pyauth/pyotp

# Usage

For Payroll purpose:
  Input: date 
