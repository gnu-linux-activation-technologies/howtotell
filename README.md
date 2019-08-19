# How to Tell

## How can I check is my GNU/Linux copy genuine?
It is possible to check is GNU/Linux copy genuine using GNU/Linux Activation Technologies Client.

You should configure it for correct key server.

When you buy GNU/Linux license, you should receive Certificate of Authenticity (COA). You will find two user IDs and product key.

- If you see "OEM Software", then it will automatically activate unless you have changed some hardware. In this case, you should contact your OEM (original equipment manufacturer). They will replace your COA and insert new hardware ID into their databases.
- If you have retail or volume license, you should insert your product key in the following format: XXXXX-XXXXX-XXXXX-XXXXX-XXXXX, where X are key digits/letters. In addition, retail license could be used on only one computer at once.

## I have lost my hardware ID and cannot delete it from key server
You should contact key server administrator and provide them your COA.

## Which key server should I chose?
Unless you're disconnected from the Internet, every GNU/Linux distribution which distributes genuine copies will have key server. You should visit your distribution website to find it.

If you're disconnected from the Internet, but connected to LAN, your system administrator might have key server set up.

If your computer is not connected to any network, you could set up local key server.

## Where is product key stored?
By default, /etc/gnu-linux-activation-technologies/product-key

## What is the purpose of user IDs?
User IDs could be used to determined which person/organisation has the license. Real names are not stored in key server databases, but in central databases which are not connected to any network, to make it impossible for crackers to steal this data. Linux Foundation own the first database and GNU Project owns the second one. Only few authorised organisations could ask for this data.

## Why does my retail/volume product key no longer work?
If you have leaked the product key, it is blacklisted and no longer valid. COA is no longer valid too. You should ask your key server administrator for new COA.
