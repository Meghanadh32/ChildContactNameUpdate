# ChildContactNameUpdate
Consider you are updating account name so whenever acc name gets updated its relative child contacts name should get updated
Well in such a case i would use the helper class for the taskto perform : 

i will create a ContactNameUpdate:

trigger ContactNameUpdate on Account (after update)
{
	if(trigger.isupdate && trigger.isAfter)
	{
		accountNameUpdate.accountMethod(trigger.new, trigger.oldMap);
	}
}


helper class of AccountNameUpdate


public class accountNameUpdate
{
	public static void accountMethod(List<Account> accList, map<Id,Account> oldmap)
		{
		set<Id> accountId = new set<Id>();
		for(Account acc:accList)
		{
			account accountOld = oldMap.get(acc.Id);
			if(acc.Name !=accountOldName)
			{accountId.add(acc.Id);}
		}
if(acc.size()>0)
{map<Id,account> accountMap = new Map<>}
		}

}
