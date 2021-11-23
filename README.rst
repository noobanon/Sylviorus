SylviorusSystem
========

$Sylviorus is Antispam System we are here to create a safe environment in telegram froms scammers, threats, raiders, spammers etc

Look how to use:
    
# Get your stuff done

>>> from sylviorus import SYL
>>> x = SYL()
>>> syl = x.get_info(user)
>>> print(x)
>>> print(x.reason)

# Print Ban Reason

>>> try:
>>>        sylban = SYL()
>>>        spamer = sylban.get_info(int(user.id))
>>>        if spamer.blacklisted != False:
>>>            text += "\n\n<b>This person is banned on Sylviorus!</b>"
>>>            text += f"\nReason: <pre>{spamer.reason}</pre>"
>>>            text += "\nAppeal at @Sylviorus_Support"
>>>        else:
>>>            pass
>>>    except:
>>>        pass  

Features
--------

- Spam Free Groups
- Make a Better Environment

Installation
------------

Install $project by running:

>>> pip install sylviorus

Contribute
----------
Team Sylviorus

Support
-------

If you are having issues, please let us know.
We have a support group located at: https://t.me/Sylviorus_support

License
-------

The project is licensed under the GPLV3 license.
