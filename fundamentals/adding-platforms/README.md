# 🕸️ Adding platforms

You can toggle on different modules that work on top of your data TogetherCrew is ingesting. For each module you have a choice of different platforms. Remember

* A **platform**  is any tool that you use. For example: Discord, Notion, Discourse, Github.
* A **module** is a "widget" that is offered as part of TogetherCrew For example: [HiveMind](../setting-up-the-ai-assistant.md), reputationNFT

To set up a module you always follow this flow

1. Go to **Community Settings**
2. **Select** the chosen platform
3. **Connect** the chosen platform
4. **Manage the access** a **module** should have to the **platform**

{% hint style="info" %}
When you connect a platform you make it _possible_ for other modules to pull data from these platforms. But you still need to set up these modules and tell them exactly what data to pull.&#x20;
{% endhint %}



### Add a platform to your community

<details>

<summary>Discord</summary>

_Currently (June 204) you can only set up one Discord server per Community on TogetherCrew_

* Select **+Connect**
* Select your server. You might have to first authenticate your Discord account
* Select **Continue** and then **Authorize**



</details>

<details>

<summary>Discourse (coming)</summary>

_summer 2024_

</details>

<details>

<summary>Telegram (coming)</summary>

_July 2024_

</details>

<details>

<summary>Google Drive</summary>

Connect a Google Account

* Select the Google Platform
* Select **+Connect**
* Select your Google account
* Select **Continue**
*   Select the following permissions and then select **Continue**

    * See and download all your Google Drive files
    * See information about your Google Drive files



Disconnect a Google Account

* Select the Google Platform
* Next to the account that you want to disconnect, select the **wheel** and then select **Disconnect & Delete**

</details>

<details>

<summary>GitHub</summary>

Connect a GitHub account

* **Sel**ect the Github Platform
* **Sign** in to your GitHub account
* Select the Organization you want TogetherCrew to have access to. You can also give it access to your personal account.&#x20;
* **Decide** what repositories TogetherCrew should have access to. You can select **All repositories** or **Only select repositories**.&#x20;
  * If you select **Only select repositories** you have to specify which ones in the dropdown menu.
* Select **save** and go back to TogetherCre community settings.&#x20;

Disconnect a GitHub account

* Option 1: In TogetherCrew by selecting the platform, then select the little wheel and **Disconnect & Delete**
* Option 2: In Github, under Account (Organization) setting -> Integrations -> Applications scroll down to the **Danger zone** and select **Suspend your installation** or **Uninstall TogetherCrew**

</details>

<details>

<summary>Notion</summary>

Connect a Notion Account. You can only connect a Notion account to one community

* Select the Notion Platform
* Select **+Connect**
* Select the Notion you want to integrate. Remember, you need to have admin access to that Notion.
* Select **Select Pages** and in the next window you decide what pages TogetherCrew should have access to
* Then select **Allow Access**

Disconnect a Notion Account

* Select the Notion Platform
* Next to the account that you want to disconnect, select the **wheel** and then select **Disconnect & Delete Data**

</details>

<details>

<summary>Mediwiki</summary>

* Select the MediaWiki Profile
* Select **+Connect**
* Add the MediaWiki URL **without** a blacklash at the end.&#x20;
  * ✅ [https://www.mediawiki.org/wiki/MediaWiki](https://www.mediawiki.org/wiki/MediaWiki)
  * ❌[https://www.mediawiki.org/wiki/MediaWiki](https://www.mediawiki.org/wiki/MediaWiki)/

</details>



## Manage Module settings

Use this to manage the access a module has to the platforms you connected to your community

<details>

<summary>HiveMind</summary>

HiveMind helps members get quick answers to their questions, and supports knowledge management in communities. You have to specify the settings for each platform.&#x20;

[**Setting up HiveMind**](../setting-up-the-ai-assistant.md) explains how to set up different platforms for the HiveMind module

</details>
