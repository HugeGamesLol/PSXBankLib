# Pet Simulator X Bank Library
###### Because none of you can figure out how to use fucking banks
i don't use github so don't expect an actual fucking description

This Library makes it 100x easier for idiots to use banks :)
Instead of passing just BankID, you can use either Username, UserID or Bankid, Example: GetBank("YourRobloxName")

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
