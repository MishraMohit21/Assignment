Scraping Assignment

Email: mishraloopmohit@gmail.com

Libraries utilized: Django, Django REST Framework, Selenium, Decouple, Webdriver Manager, Redis, Pandas, Openpyxl

Let us examine the output provided by the API.
Job_ID: 919d938b-6341-46f6-995c-667d6e0c7ad1
Requests made:
i) POST Request
ii) GET Request (PENDING)
iii) GET Request (SUCCESS)

Responses received for:

iii) {
"job_id": "919d938b-6341-46f6-995c-667d6e0c7ad1",
"status": "SUCCESS",
"task": [
{
"coin": "ethereum",
"output": {
"price": 3691.77,
"price_change": -2.76,
"market_cap": "443558257798",
"market_cap_rank": 2,
"volume": "16037501852",
"volume_rank": 3,
"volume_change": 3.63,
"circulating_supply": "120147950",
"total_supply": "120147950",
"diluted_market_cap": "443558257798",
"contracts": [
{
"name": "BNB Smart Chain (BEP20):",
"address": "0x2170...f933f8"
}
],
"official_links": [
{
"name": "Whitepaper",
"link": "https://github.com/ethereum/wiki/wiki/White-Paper"
},
{
"name": "GitHub",
"link": "https://github.com/ethereum/go-ethereum"
}
],
"socials": [
{
"name": "𝕏\nTwitter",
"url": "https://twitter.com/ethereum"
},
{
"name": "Reddit",
"url": "https://reddit.com/r/ethereum"
},
{
"name": "Chat",
"url": "https://gitter.im/orgs/ethereum/rooms"
}
]
}
},
{
"coin": "DUKO",
"output": {
"price": 0.004783,
"price_change": -13.1,
"market_cap": "46220417",
"market_cap_rank": 660,
"volume": "12166421",
"volume_rank": 392,
"volume_change": 26.32,
"circulating_supply": "9663955990",
"total_supply": "9999609598",
"diluted_market_cap": "47825769",
"contracts": [
{
"name": "Solana:",
"address": "HLptm5...2G7rf9"
}
],
"official_links": [
{
"name": "Website",
"link": "https://dukocoin.com/"
}
],
"socials": [
{
"name": "𝕏\nTwitter",
"url": "https://twitter.com/dukocoin"
},
{
"name": "Telegram",
"url": "https://t.me/+jlScZmFrQ8g2MDg8"
}
]
}
},
{
"coin": "usd-coin",
"output": {
"price": 1.0,
"price_change": 0.01,
"market_cap": "32189572236",
"market_cap_rank": 6,
"volume": "5709062693",
"volume_rank": 5,
"volume_change": 17.81,
"circulating_supply": "32186712711",
"total_supply": "32186712711",
"diluted_market_cap": "32189572236",
"contracts": [
{
"name": "Ethereum:",
"address": "0xa0b8...06eb48"
}
],
"official_links": [
{
"name": "Website",
"link": "https://www.centre.io/usdc"
},
{
"name": "Whitepaper",
"link": "https://f.hubspotusercontent30.net/hubfs/9304636/PDF/centre-whitepaper.pdf"
},
{
"name": "GitHub",
"link": "https://github.com/centrehq/centre-tokens"
}
],
"socials": [
{
"name": "𝕏\nTwitter",
"url": "https://twitter.com/circle"
}
]
}
},
{
"coin": "XRP",
"output": {
"price": 0.494,
"price_change": -5.74,
"market_cap": "27420881963",
"market_cap_rank": 7,
"volume": "2138027760",
"volume_rank": 8,
"volume_change": 7.8,
"circulating_supply": "55506158411",
"total_supply": "99987553871",
"diluted_market_cap": "49407386089",
"contracts": [
{
"name": "BNB Smart Chain (BEP20):",
"address": "0x1d2f...c60dbe"
}
],
"official_links": [
{
"name": "Website",
"link": "https://xrpl.org/"
},
{
"name": "Whitepaper",
"link": "https://ripple.com/files/ripple_consensus_whitepaper.pdf"
},
{
"name": "GitHub",
"link": "https://github.com/ripple/rippled"
}
],
"socials": [
{
"name": "𝕏\nTwitter",
"url": "https://twitter.com/Ripple"
},
{
"name": "Reddit",
"url": "https://reddit.com/r/ripple"
}
]
}
}
]
}

Django admin: Django Admin

Celery Console: Celery Console

Django Console: Django Console

Job_ID: 25336f36-34fd-4bc7-bdd7-28a1f538ca30
Requests Made:

i) [08/Jun/2024 21:16:31] "POST /api/taskmanager/start_scraping HTTP/1.1" 202 50 Json-Body: {
"payload":[
"bitcoin",
"solana",
"dogecoin",
"avalanche",
"filecoin"
]
}

ii) [08/Jun/2024 21:16:45] "GET /api/taskmanager/scraping_status/25336f36-34fd-4bc7-bdd7-28a1f538ca30 HTTP/1.
