# Downloading Signing Apps to Your Device




::: info
NeoSign customers are provided with a one-click Feather install link in the email containing their certificate. It is highly recommended that you install via our one-click install link because Feather is automatically pre-signed with your certificate.

You may continue with this guide if you aren’t a NeoSign customer or if you need any extra help.
:::

## Prerequisites

After receiving your certificates from NeoSign (or a communication from another cert provider, if applicable) containing your cert. Save your `neosign.zip` to your Files app.
Download your chosen signing app:
- [Feather Default](https://github.com/khcrysalis/Feather/releases/latest/download/Feather-default.ipa)
- [idevice Feather](https://github.com/khcrysalis/Feather/releases/latest/download/Feather-pairing.ipa)

::: warning
If you don't know which one to install and sideload, choose Feather default.
:::

## Sideload Using an Online Signer
1. In the iOS Files app, unzip your development certificate. You may see different files, such as development, distribution, etc. You may choose any for this process, but make sure to use the correct `.p12` with its corresponding `.mobileprovision`.
2. Navigate to [https://sign.neosign.dev](https://sign.neosign.dev/). Select the IPA file of your signer from prerequisites, or another signer if you wish (there won't be documentation from us about it).
3. Select your `.p12` certificate and provisioning profile from the same folder. Enter the password found in `password.txt`.
4. Select `Sign IPA`, then select "Install".
5. Your setup should look similar to this:

![Signing interface](./assets/sign.PNG)

Now, proceed to enable [developer mode](/guide/getting-started/developer-mode).
