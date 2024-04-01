---
cover: ../.gitbook/assets/TextOnly.png
coverY: 0
layout:
  cover:
    visible: true
    size: hero
  title:
    visible: true
  description:
    visible: true
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
---

# Discord authentication error

We use Discord within RusticRP to grant you access to the server (once whitelisted) we also use it for in game roles and support packages. On some occasions this bugs out and will not allow you onto the server. In that case you will recieve an error when trying to join the server. To fix this follow the below.



* Open up task manager (you can do this CTRL+ALT+DEL) find the FiveM process and click end task.

<figure><img src="../.gitbook/assets/image (7).png" alt=""><figcaption></figcaption></figure>

* Open up Discord and go to User Settings

<figure><img src="../.gitbook/assets/image (5).png" alt=""><figcaption></figcaption></figure>

* Find "Authorized Apps"
* Look in the list for FiveM. If it is in that list then Deauthroize the app to remove it.

<figure><img src="../.gitbook/assets/image (6).png" alt=""><figcaption></figcaption></figure>

* In task manager again find Discord and click "end task" double check FiveM is still closed, if it is in task manager kill it again.

<figure><img src="../.gitbook/assets/image (8).png" alt=""><figcaption></figcaption></figure>

* Now re-open Discord and then FiveM
* Connect to the RusticRP server, you should recieve a prompt asking FiveM to access Discord.
* Grant the access
* Close and re-open FiveM
* Once in FiveM go to settings, it should now show you that your Discord is linked.
* Try and join the server again, it should now succeed.
* If this does not fix your problem please open a ticket and a member of the support team will assist you.
