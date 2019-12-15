# Bitmex-Payroll

An useful script based on CCXT and PYOTP modules that allow you to set an automated payment from Bitmex on a specific date or when your Bitmex wallet exceed a certain amount.
It creates a Payroll to use with bot. 
You can set-up an Event Manager or AWS schedule to run it on daly basis and at your choose date you will recieve automatically a paiment from to your external wallet.

NOTE1 : All input amounts are in BTC.

NOTE2 : Each payment has to be confirmed by mail (time limit 30 min) or will be canceled.

BITMEX: https://www.bitmex.com/register/Sh02pG

CCXT: https://github.com/ccxt/ccxt

PYOTP: https://github.com/pyauth/pyotp

# Usage

For Payroll purpose:
  
    Run Payroll
  
    Input: Date of Payment, Amount to be paied (BTC), The wallet address where you want recieve your funds
    
    PayRoll ('15', '0.1', 'YourWalletAddress')
  
  
For Exceed amount payment:
 
    Add # to Payroll
  
    Remove # from PayExcess
  
    Input:Amount you DON'T want withdrawal(BTC), Amount you want withdrawal(BTC), The wallet address where you want recieve your funds
    
    PayExcess ('0.1','0.01', 'YourWalletAddress')
