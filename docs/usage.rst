========
Usage
========

To use this template, simply update it::

	pip install sylviorus

Imports::

>>>from sylviorus import SYL
>>>x = SYL()
>>>syl = x.get_info(user.id)
>>>print(x)
>>>print(x.reason)


Take Auto Ban From Core::

>>>    x = SYL()
>>>    syl = x.get_info(int(user.id))   
>>>    if not syl['blacklisted']:
>>>            return        
>>>    else:
>>>                chat.kick_member(user_id)
>>>                reason , enf , user = syl['reason'] , syl['enforcer'] , syl['user']
>>>                print(reason)


Print User Information::

>>>try:
>>>       x = SYL()
>>>       syl = x.get_info(int(user))
>>>       if not syl['blacklisted']:
>>>               pass
>>>       else:                
>>>               if syl:
>>>                   print(syl.reason)       
>>>   except:
>>>       pass  # don't crash if api is down :)          

