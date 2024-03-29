# Nostr Horror Stories

This document outlines the various issues that people have encountered on clients and relays built on the NOSTR protocol. To locate the thread here is the QR code:

![nostr-horror-stories.png](./assets/nostr-horror-stories.png)

And here is a text link people can use to locate the thread.

```
nostr:nevent1qyvhwumn8ghj7un9d3shjtnndehhyapwwdhkx6tpdshsz9mhwden5te0wfjkccte9ec8y6tdv9kzumn9wshsz9nhwden5te0wfjkccte9ehx7um5wghxuet59uq3xamnwvaz7tmsw4e8qmr9wpskwtn9wvhszrnhwden5te0dehhxtnvdakz7qg4waehxw309aex2mrp0yhxgctdw4eju6t09uq3wamnwvaz7tmjv4kxz7fwdehhxarj9e3xzmny9uq3vamnwvaz7tm9v3jkutnwdaehgu3wd3skuep0qywhwumn8ghj7mn0wd68ytnzd96xxmmfdejhytnnda3kjctv9uq35amnwvaz7tmwdaehgu3w0fjkyetyv4jjucmvda6kgtcqyq5kxxjxwvqjq3hq6x6kvwrxycqq605v8hphspy8zpuzgny767a5zk28ft3
```

I did my best to provide as much attribution as possible. If I missed anyone please let me know.

## Stories

- Improve resource use efficienty on clients (Amethyst). [petterhs][petterhs]
- Having to set zap amounts and zap emojis after each nsec login. [Felix](https://nostr.band/?q=nevent1qythwumn8ghj7un9d3shjtnswf5k6ctv9ehx2ap0qyghwumn8ghj7mn0wd68ytnhd9hx2tcpz3mhxue69uhkummnw3ezud3c8qhx7un89uqjvamnwvaz7tmxw3czu6rpd35kvctc9ee8warg94skzcmgv4hzuer99ahx7um5wgq3jamnwvaz7tmsw43xc6tr9eex2mrp095kueewd9hj7qgnwaehxw309ac82unsd3jhqct89ejhxtcprdmhxue69uhhyetvv9ujummjv9hxwetsd9kxctnyv4mz7qghwaehxw309aex2mrp0yhxummnw3ezucnpdejz7qgwwaehxw309ahx7uewd3hkctcpz4mhxue69uhhyetvv9ujuerpd46hxtnfduhsqgyxwtqdxml20cgaamleeyk09khuregc5hl3vx6q4ynlkvh07tj47g3rqeth)
- More support for third-party signers. Source: [mattybs](https://nostr.band/?q=note18jezfc73fd6rvpdjpf56w0zsx2rzjnpy4vnt0dqnwhyu6t33hwvszweac6)
- Typos. Traumatized by all typos made. Source: [Eryn Bracco](https://nostr.band/?q=note13aecr7tp7u8xgzm9w0u0jq79kdqcfxt5nz3457j4jq9rr9cn5y5qmh69ny)
- Improve Communties. Source: [MKD Podcast](https://nostr.band/?q=note1pad48m90f4frntd8sc5fstzz2687a4qhvhl8fkghzx5pddaxry5qn0z90l)
- Inconsistency or challenges viewing parent notes or threads. Source: [Biebs][biebs]
- Improve onboarding experience. Make it easy as possible.
- Some clients do not use the full set emojis for reacting to notes. [Jedi](https://nostr.band/?q=note1mh35v6jr5094lxd0z9ln56djjk5tm3xqhtlnnpktnpsa0v0nmkcsuevsh3)
- Problems connecting to relays when traversing a broad geographical area. [Dawn](https://nostr.band/?q=note1wkcwhsjsf4q0kaw33arwlslljmz3fhwtrg6shdwpn4v6ewzxsh2qhqaa9k)
- Add integrated wallets to clients [jamw](https://nostr.band/?q=note1zzrut0vjm5flwv7zdd32pd63765lgyffq4fm7hpaf6pvxkgpehxse3ue4x)
- Add different sorting methods for events. [chris][christ]
	- Oldest -> Newest
- Event counting (source same as above)
- Missing replies in Primal. [acoustics][acoustics]
- Add better offline support. [b][b]
- Problems logging in with Alby on iOS clients (except Coracle) [capsule_corp][capsulecorp]
- Add better Tor support. [Big Barry Bitcoin][bigbarry]
- Improve threads. [charliesurf][charliesurf]
- iOS clients erase all relays. 
- Improve tagging support to reduce toil. [Derek Ross][derekross]
	- tagging with npubs is labor intensive.
- Some replies not do appear in threads. 
- Some profiles get unfollowed without user consent. [FiddleHodlHomestead][fiddlehodl]
- Lack of twitter friends. [dackdel](https://nostr.band/?q=note1xzj28q2su3gapvsufpe0yzztvrcnckrlefpw30fszcgtcnemfcys3zyp6t)
- Clients are not consistent. [Gergg](https://nostr.band/?q=note1j7u2gunxmj5zmxe00kpk877uchlmwp8rys863kly705f6395l5hqyz429p)
	- Different clients have novel implementations of features.
- Add better messaging when rejected from a relay [Jedi](https://nostr.band/?q=note1l24p2k0jdwkmmgz29jf0hqfpuqtf8dc7uhce472weu4gv8uy7eks8m83uq)
- Add [SSO (Single sign-on)](https://en.wikipedia.org/wiki/Single_sign-on) solution
	- At least one effort exists: [nsecbunker](https://nsecbunker.com/)
- Add metrics to see reach and distribution of notes.
- No good network wide search
- Improve the ability to connect with friends without knowing their relays.
	- Sources suggests using a [DHT (Distributed Hash Table)](https://en.wikipedia.org/wiki/Distributed_hash_table) index of notes
- When closing a note, client forgets location and takes user to the top of the page. [Paul Allen](https://nostr.band/?q=note1047d0g5yuwwau46q0cmanlv06jhpdm02tqrn0l9w5jkchzjukxfqhmue9r)
- Improve the ability for Users to migrate apps. Login with Nostr should be consistent between web and mobile. [Oscar Merry](https://nostr.band/?q=note1y40dzcnhed5403646u2wqp0q0jnxm8f56sjq97k50vx3v0qdrrsssgnhhv)
	- User refers to [nsecbunker](https://nsecbunker.com/)
	- Pablo agrees
- No search. More following, but less posts. [Hypnotic HODL](https://nostr.band/?q=note1qkq005glqt3pqzlcz2nlu3dns2j0lstpv276n4nrjf7hzgzez0qqytklar)
- User must clear cache on [Amethyst](https://github.com/vitorpamplona/amethyst) everyday. [FROGFREN17](https://nostr.band/?q=note1frq89qt0c5kl47cndvg0le7eezd2der2ztehmp7zdr25hm99ny7qpzrg9e)
- Improve image & video exploring on Damus [xiangcai](https://nostr.band/?q=note15jvrwvzm6fx3f3z606a2h9jyr5tzzj0gcdn9e5hapq270jydfuksmm6cr5)
- Suhail zap plugin does not work
- Improve text selection in Primal
- Primal does not show indirect replies
- Improve Client [antifragiliity](https://en.wikipedia.org/wiki/Antifragility) [Karnage](https://nostr.band/?q=note15uc9mlpj5rkmxa46u3ur74n20x0zuyl9c3tkt7qp2q8mk9fg3tjqtpcvve)
- Flat-earthers [invetor](https://nostr.band/?q=note123ee2r8cdc9mfkq3dmsp5zlpjqm5jdkay5llev0gd9pnypzcvzzsg4ptj4)
- Improve audience building tools. Improve reliability [Uncle Ted](https://nostr.band/?q=note15yk002uwqfu4evdqnhud0nfxa00pxtws9mv38p5lrhg29txs2qmqg7xl9k)
	- User loses followers
- Add a 10 second window to cancel posting a note [Bauzen](https://nostr.band/?q=note12ffq29mye5jekrn7r2pra0y627ar4jnudpnzs7la068cgq4v076qp25524)
	- [Nostur](https://nostur.com/) does this
	- [Plebstr](https://plebstr.com/) does this
- Data / Bandwidth usage is high [Connie](https://nostr.band/?q=note1ka4s6fn2xv2fsa4xwh8kzruqkaqugyvcaqk72vnlryrc2xy0vuasrfcxe0)
	- Binary format NIP?
- Lost nsec. [SavageWhit](https://nostr.band/?q=note1yf9djks03ruqcrtw940wseftqjgl8rwkm4rmacq6xacxl9k6l7yqh29nf8)
- Not enough users. [Phantom Bullfrong][phantom]

[petterhs]: https://nostr.band/?q=note15k7rh79zav384r77420nm3nu3x8g943hl930k4zxru0lgtws3h0qtawq7l
[phantom]: https://nostr.band/?q=note19huqqc0m63a829d0z5xfk6w53qfhwje00lcmhwn0hupvamd39erq5vt9uc
[biebs]: https://nostr.band/?q=note193epjvj23d8hzdqq8plq5zg59eqke5s2vfywepcemr7rj6d5x4tsuu5nfp
[derekross]: https://nostr.band/?q=note1yl0tanfczwlj98r3ep07xrnd2hzm5tgxal36j9vnvc5ww5mjk4fqt6l93k
[fiddlehodl]: https://nostr.band/?q=note185s5r7f3q4vcrdddv8mlthkkkyla2l4p94fhmfcpdxy6czd0udkq5xy6rd
[charliesurf]: https://nostr.band/?q=note19rsnvgcgs9lxzl7ar9qfe4kv087z0pvcvcyesagn2sjjjnlst32smw5chg
