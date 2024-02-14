# 🚔 Permission settings for Discord

You can set write access to TogetherCrew at 3 levels, from broad (server) to fine-grained (channel)

1. Server: Permissions for every category and every channel
2. Category: Permissions for channels grouped into one category
3. Channel: Permissions for specific channels

If you have different permission settings for category and server, the server settings are overridden by the category settings. Similarly, channel level settings override category level settings.&#x20;

**How to set permissions**

1. Decide what access level you should grant. We recommend setting write access only for specific channels.&#x20;

In Discord:

1. Navigate to the settings for a specific channel (select the wheel on the right of the channel name)

<figure><img src="../.gitbook/assets/Screenshot 2024-02-14 at 12.20.04.png" alt=""><figcaption></figcaption></figure>

1. Select “Permissions” (left sidebar), and then in the middle of the screen check Advanced permissions. You might have to scroll down a bit.
2. Check that TogetherCrew is in the list of Roles/Members that have access to the channel. If not, select the ⊕ and add it.
3. Now, select “TogetherCrew” and scroll down the list of  Advanced Permissions. Make sure that the following are marked as \[✓]
   * “Read” access settings: Read channel and Read Message History
   * For “Write” access settings, the following is required
     * Send Message, Send Messages in Threads, Create Public Threads, Create Private Threads
     * If your announcement will include links, files and mentions, add these permissions: Embed Links, Attach Files, Mention @everyone, @here, and All Roles
4. Save your settings and go back to TogetherCrew

In TogetherCrew, Community Settings page give the bot access to the channel.

1. On the top right of your Discord server panel, select the menu (three dots)

<div align="center">

<figure><img src="../.gitbook/assets/Screenshot 2024-02-14 at 12.46.44.png" alt=""><figcaption></figcaption></figure>

</div>

1. Click on "Show channels"
2. Click on the Refresh List&#x20;
3. Save and go back to the Announcement page
