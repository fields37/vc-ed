# Intro to CHAPI Badge

![intro-chapi-logo](https://user-images.githubusercontent.com/20584379/235524136-0ee025bd-c476-4ce9-98b2-c679d1104ae3.jpg)

## What is CHAPI?

This is a tutorial to teach you the basics of CHAPI! CHAPI (Credential Handler API) is a protocol that mediates between digital wallets and a 3rd party issuer or verifier, so that you can easily exchange and receive credentials with whatever wallet you happen to use. It does this by popping up a little box on the requesting website, where you can interface with your wallet and accept or send out credential information. It's designed to be interoperable with any wallet that implements its protocol. You can read more about CHAPI at its [project website](https://chapi.io/).

Today we will be issuing an _Intro to CHAPI_ badge, and storing it in our wallets. In the process we will learn a bit about how CHAPI works!

## Set up a Wallet

If you don't yet have a digital wallet set up, you will need one to authenticate and receive your credential today. The CHAPI team currently recommends the [Veres](https://demo.vereswallet.dev/) and [LearnCard](https://learncard.app/login) digital wallets for use with the protocol. Make an account with whichever you prefer.

## CHAPI Playground

Start by opening up the [CHAPI Playground](https://playground.chapi.io/issuer). Select the _Intro to CHAPI_ badge and press "Issue Verifiable Credential", then "Sign In With Your DID". This will open up CHAPI's wallet choice screen.

![chapi-playground](https://user-images.githubusercontent.com/20584379/236932380-5f19bb79-9011-44d9-b62c-d0bdda23ed83.png)


## Share your DID

In this step, CHAPI will facilitate the process of you sharing your personal identifier with the website, to be included in the issued credential. If your browser allows third party cookies, you'll see an on-screen window prompting you to select a wallet:

![chapi-select-in-screen](https://user-images.githubusercontent.com/20584379/236928792-73312eaa-1672-42d2-a3e5-d77e112ba5cc.png)

Otherwise, you'll get a prompt to open up a popup window:

![chapi-select-popup](https://user-images.githubusercontent.com/20584379/236932433-ae17a8a2-fc18-4267-868b-71cfdbb2d809.png)


Log in to your preferred wallet, and accept the transfer of your did:

![chapi-authenticate](https://user-images.githubusercontent.com/20584379/236933900-ef7945e0-1f39-4ce2-8670-d60ca076ca53.png)


## Accept your Credential

You should see two messages at the top of your screen that indicated the website has authenticated with your DID and generated your _Intro to CHAPI_ credential! Now we just need to store the credential in our wallet, so scroll down and hit the "Store In Wallet" button.

![chapi-credential-issued](https://user-images.githubusercontent.com/20584379/236933972-f4df1b01-72d4-46ba-98a4-d696bb235401.png)

This will open the CHAPI wallet selector back up. CHAPI will remember your last choice of wallet, but you can choose either to store your badge in.

![chapi-store](https://user-images.githubusercontent.com/20584379/236934125-69f930c5-2722-4d4d-b68f-f5bdc5df829f.png)

You should now see a message saying "Successfully stored credential in wallet", and if you navigate to your wallet, you should be able to see your new badge. You've now learned the basics of CHAPI!
