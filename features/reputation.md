# 🎆 Reputation

With our reputation module you can turn **offchain activity into onchain points**. Use these points to reward your members bwith voting rights, alpha access to content and merch, or specific features related to your dapp or protocol. Once minted, the points will update daily.&#x20;

Read the instructions for how to [activate the module](reputation.md#community-manager) and for [members to mint their score](reputation.md#community-members).

{% hint style="info" %}
Remember to first activate the module so that members can mint their score.&#x20;
{% endhint %}



add video



### Community Manager

As community manager you need to turn on the reputation module. This will release a token id that is tied to your community. The token id acts as an identifier for your community. To activate your module you need to connect your wallet. If you do not yet have a wallet, you can create one here



1. **Connect** your wallet to TogetherCrew app
2. Once your wallet is connected, select **Issue Token**. You will have to confirm and sign a message.&#x20;

{% hint style="info" %}
You need a tiny bit of ETH in your wallet to pay the transaction (less than 0.0001 ETH).
{% endhint %}

1. Once you signed the transaction we will process it and issue a token. This might take a minute, depending on the chain. A message will appear in the reputation module once the transaction is processed.&#x20;
2. Members can only mint their reputation NFT if you give them access to the TogetherCrew app. Head over to [**Community Settings**](../fundamentals/settings.md) **> Roles** and in the field View Access add the necessary Discord roles. Only members who have that role can mint the reputation NFT.
3. And you are done! Head over to [**Smart Announcement**](smart-announcements.md) to schedule a message telling your members that they can mint their score. Make sure to tell them: What handles they need to connect to receive a score (e.g, Discord) and on which chain to mint (e.g, Arbitrum). They need a tiny bit of eth on the respective chain to mint their score (less than 0.0001 ETH).

### Community Members

1. **Create** an account at [togethercrew.com](https://togethercrew.com) by logging in with your Discord (other methods coming soon).
2. After accepting the T\&S, **select your community**_._&#x20;

{% hint style="info" %}
If you do not see your community, reach out to your community manager. They need to either  activate the reputation module or give you the correct Discord role.&#x20;
{% endhint %}

3. Go to **Reputation Score** and **connect** your wallet. Your reputation score will be minted to this wallet.&#x20;
4. Once you have connected your wallet to the TogetherCrew app, you have to link your wallet with your user handle. This is done by attesting that you are the owner of the specific handle. This step is done in LogID, a platform to create secure, onchain attestations of user credentials.&#x20;

{% hint style="info" %}
The user handle you choose will be used to calculate your reputation score.
{% endhint %}

5. Select **Register and Grant permission**_._ You will be directed to the logid app.&#x20;
6. **Connect** your wallet

{% hint style="info" %}
You need a tiny bit of ETH in your wallet to pay the transaction (less than 0.0001 ETH).
{% endhint %}



5. First connect your username (e.g., Discord, Discourse, Telegram etc)  by selecting **Connect**. This will start the attestation flow. The attestation flow has three steps:
   1. Authenticate: Sign in with your username (e.g., Discord, Discourse, Telegram etc)
   2. Attest: Connect your username to your wallet. In this step you make an online attestation that you own both of them.&#x20;
   3. Sign: In this final step you sign a message to confirm your onchain attestation. You will see a green notification at the bottom of your screen and see that the Connect button changed to Revoke.&#x20;
6. Repeat step 7 for as many usernames as you want to link to your wallet.
7. Now that you have linked your wallet to your username, you have to give permission to TogetherCrew to use this username - wallet pair. In logid, head over to **Permissions**.&#x20;
8. In **Permission**, you will see Applications towards the left, followed by all the accounts you have linked to your wallet. Select **Grant Access** for each username you want TogetherCrew to have access to. You have to sign a message in your wallet to confirm this step.&#x20;
9. You are done attesting ownership of your usernames. It's time to see your reputation score! Go back to [togethercrew.com](https://togethercrew.com) and select **See your score.** The score will update daily.



### Smart contract

add smart contract address



