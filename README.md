# Pet Simulator X Bank Library  
###### Because none of you can figure out how to use fucking banks  
i don't use github so don't expect an actual fucking description  
also this is VERY Experimental, and might not be tip top condition omg, but it's just for people tryna make simple little scripts  


This Library makes it 100x easier for idiots to use banks :)  
Instead of passing just BankID, you can use either Username, UserID or Bankid, Example: GetBank("YourRobloxName")  

`local Lib = loadstring(game:HttpGet("https://raw.githubusercontent.com/HugeGamesLol/PSXBankLib/main/Lib.lua"))()`  
Obfuscated due to ugly code lol, will prolly unobfuscate when i clean it up xo
  
###### **Lib.Deposit**
Lib.Deposit([Name/UID/BUID], [PetsTable], [GemsAmount])  
Returns: ActionID  
Queue things to be deposited into bank  
  
###### **Lib.Withdraw**
Lib.Withdraw([Name/UID/BUID], [PetsTable], [GemsAmount])  
Returns: ActionID  
Queue things to be deposited into bank  
  
###### **Lib.GetBank**
Lib.GetBank([Name/UID/BUID])  
Returns: Bank Info  
Get Your Bank Information Duh  
  
You should know everything above, otherwise stop tryna make psx scripts  
  
###### **Lib.Initialize**
  
Lib.Initialize(OPTIONAL: BankID)  
Returns: Nil  
Will request all banks, after then, banks are useable after 30 seconds.  
Requesting with no arguments will initialize all banks you are in.  
(Banks will automatically be initialized if you try to Deposit/Withdraw, but a 30 second wait is set Between GetBank and Actions to the bank by Preston(He Can't Patch Duper Properly))
  
  
###### **Lib.ToBankID**
Lib.ToBankId([Name/UID])  
Returns: BankID  
Returns your BankID Associated with the user given  
  
  
###### **Lib.IdToStatus**
Lib.IdToStatus(ActionID)  
Returns: Status  
Gets the status of your deposit/withdraw requests  
(Will either return "WaitingToDeposit", "WaitingToWithdraw" or "CompleteOrInvalid")  
  
  
This lib is like Dogshit, first time i tested doing smth like this so get fucked  
  
Will upload the actual lib later lol
