
Email :: sendCc
-------------------------------------------

Get CC e-mail addresses from an array, string or unlimited number of arguments. Friendly name portions (e.g. Admin <admin@example.com>) are allowed.


### Description ###

**Definition:** `public function sendCc()`

**Located in:** *system/libraries/Email.php*

**Class hierarchy:** *[System](../System.md) > [Email](../Email.md)*


### Parameters ###

1. *mixed*

	Recipients that will receive a carbon copy.
	- **an e-mail address** -
		admin@example.com
	- **a friendly e-mail address** –
		Admin <admin@example.com>
	- **a set of e-mail addresses** –
		admin@example.com, User <user@example.com>
	- **an array e-mail addresses** –
		Array ( [0] => admin@example.com, [1] => User <user@example.com> )


### See also ###

- [`Email::sendBcc`](sendBcc.md) – Send the recipients of blind carbon copy
