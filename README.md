# Claymore-10.1-with-Nodevfee
How to use:  
Copy nodevfee.exe and nodevfeeDll.dll to Claymore directory (in same directory with EthDcrMiner64.exe). 
Create bat file and use it nodevfee.exe EthDcrMiner64.exe YOUR_USUAL_PARAMETERS. 
Example: nodevfee.exe EthDcrMiner64.exe -epool eu1.ethermine.org:4444 -ewal 0x043B3b62201Bdf08cA97E3C7a2b00C359c0d4c0a.worker1 -epsw x -r 1 To make it work after miner restart add option -r 1 to bat file and create reboot.bat with exactly same parameters 
nodevfee.exe EthDcrMiner64.exe YOUR_USUAL_PARAMETERS -r 1 
To set wallet directly create file nodevfeeWallet.txt with your wallet address inside. 
Note: might be needed to work with -allcoins / -allpools. 
Create nodevfeeLog.txt file in same directory to enable logging / delete to disable. 
To redirect devfee pools to your main pool create file nodevfeePools.txt. 
Example (redirecting pools to eu1.ethermine.org:4444): https://pastebin.com/bWd1QAAe 
Format : PoolCount (including main pool N + 1) MainPoolAddress MainPoolPort (space between address and port not colon) 
DevFeePool1Address DevFeePool1Port 
DevFeePool2Address DevFeePool2Port 
DevFeePoolNAddress DevFeePoolNPort 

Big advantage there is no need to give administrative privilages...:)
Happy Mining...!!!
Donation:  ETH: 0x043B3b62201Bdf08cA97E3C7a2b00C359c0d4c0a
Credits:  minhook - The Minimalistic x86/x64 API Hooking Library for Windows (Tsuda Kageyu) http://www.codeproject.com/KB/winsdk/LibMinHook.aspx https://github.com/TsudaKageyu/minhook
