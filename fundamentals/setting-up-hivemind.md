# Setting up HiveMind

## HiveMind

HiveMind is your community's personal intern, never tired or grumpy helping you out. Ask it to give you the main point of a conversation, help you prepare proposals and make it easier for you and your members to stay up to date on conversations.

{% hint style="warning" %}
When you add a new platform, give HiveMind 24 hours to process new data sources.
{% endhint %}

<figure><img src="../.gitbook/assets/Hivemind setting UI june 2024.png" alt=""><figcaption></figcaption></figure>

<details>

<summary>Discord</summary>

![](<../.gitbook/assets/hivemind - discord>)

_HiveMind needs to know what conversations (aka channels) it can use to **learn** about your community and where it is allowed to answer questions._

* **Select** Discord in the row of platforms.
* In the Learning panel (left side)
  * **Select** the starting date. This marks of far back HiveMind can go to learn about your community. You can not select a date further than 3 months back.&#x20;
  * **Select** which channels HiveMind can use to build knowledge about your community. TogetherCrew needs **read** access to those channels.
    * If you can not select the toggle for a specific channel, this means your permissions aren't set properly. Read [here](permission-settings-for-discord.md) how to do it.
* In the **Answering** plane (right side) you can select in which channels HiveMind can answer questions. The HiveMind command (`/question`) will only work in the channels that you have selected. TogetherCrew needs **write** access to those channels.&#x20;
  * If you can not select the toggle for a specific channel, this means your permissions aren't set properly. Read [here](permission-settings-for-discord.md) how to do it.

</details>

<details>

<summary>Google Drive</summary>

![](<../.gitbook/assets/hivemind - google drive>)

_HiveMind will know the content and metadata about your files._

* **Select** GDrive in the top row of platforms.
* Add the shared drive, folder or page ids. You can not add the connected account's personal drive, only shared drives. You can add folders and files of the connected account.
* You'll find the id of a shared drive, folder, or file in its url.
  * To add **folder ids, i**n a new tab, **open** your Google Drive and go to the folder you want HiveMind to have access to. Now in the address bar, **copy** everything after the last slash. For example the folder TogetherCrew has the url [`https://drive.google.com/drive/folders/1-4y1kMFOyu244mmhVdKym_YGAWKB4c1G`](https://drive.google.com/drive/folders/1-4y1kMFOyu244mmhVdKym\_YGAWKB4c1G). I'm adding `1-4y1kMFOyu244mmhVdKym_YGAWKB4c1G` into the form field **folder id**. Press enter after you pasted the id.
  * To add **Files ids**, follow the same steps and add the id in the form field **Files ids**. The id is the string after `/d/` and the next slash `/.` Press enter after you pasted the id.
  * To add shared drive, follow the same steps. The id is the string after `/folders/`. Press enter after you pasted the id.

</details>

<details>

<summary>Notion</summary>

![](<../.gitbook/assets/Hivemind - notion.png>)

_HiveMind will know the content and metadata about your files._

To connect the Notion platform to the HiveMind module you need to add the specific page and database ids. You find the ids as part of the page or database url.&#x20;

* **Select** Notion in the top row of platforms.
* Now you have to  give HiveMind access to specific pages and databases. You do this by adding their id. **Open Notion** in a **browser.**
* You'll find the id of a page or database in its url.
  * To add a **Notion page**, in a new tab **open** Notion and navigate to the page you want HiveMind to have access to.&#x20;
    * Now in the address bar, **copy** the string of letters and numbers that come after the human readable string. For example, the url for RnDAO's welcome page in Notion is [`https://www.notion.so/rndadocs/Welcome-to-RnDAO-1fe31552c82a45278e7a30a8d9cb89f1`](https://www.notion.so/rndadocs/Welcome-to-RnDAO-1fe31552c82a45278e7a30a8d9cb89f1). To make this page available to HiveMind, add `1fe31552c82a45278e7a30a8d9cb89f1`.
    * Press enter after you pasted the id.
  * To add a **Notion Database**, navigate to the database you want HiveMind to have access to.&#x20;
    * From the url in the address bar, copy the string between the last slash `/` and the question mark `?`. For example, the URL for RnDAO's database of ventures is [`https://www.notion.so/rndadocs/9bb634baa80542e1adf64b8d9b0716db?v=72d1ea9cc19f4f6e876767d9e7647649`](https://www.notion.so/rndadocs/9bb634baa80542e1adf64b8d9b0716db?v=72d1ea9cc19f4f6e876767d9e7647649). The database id is `9bb634baa80542e1adf64b8d9b0716db.`
    * Press enter after you pasted the id.

</details>

<details>

<summary>MediaWiki</summary>

* You need to add the individual pages you want HiveMind to have access to. Go to your url and **add** the slug (word after the final backslash `/`) in the field page id.

</details>
