
# website_info
make your own wesite 
#thanks to DIL bhai
#make your own about website 
#it's a copy repo of original repo
## Deployment of Contact Form on Cloudflare Workers

### 𝐃𝐞𝐩𝐥𝐨𝐲 𝐓𝐨 𝐇𝐞𝐫𝐨𝐤𝐮

[![Deploy+On+Heroku](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/parthxsharma/parthxwebsite)

- ### 𝐎𝐰𝐧𝐞𝐫 𝐎𝐟 𝐓𝐡𝐢𝐬 𝐑𝐞𝐩𝐨𝐬𝐢𝐭𝐨𝐫𝐲
[![Ari](https://telegra.ph/file/ad1557c30dddeff2c2351.jpg)](https://t.me/lll_notookk_lll)

Setup The Code Required:

- Create a Telegram bot from [BotFather](https://t.me/botfather) and copy its API Token
- Start your newly created bot by sending /start in its PM
- Then goto [Yoshitsu](https://yoshitsubot.t.me) and send /id and copy your user id
- Open [cf-worker.js](/contactform/cf-worker.js) and edit your Bot token and User ID you got from earlier.
- Copy the edited cf-worker.js to your clipboard.

Deploy Cloudflare worker:
- Go to [Cloudflare Workers](https://workers.cloudflare.com) & Create an Account.
- After that, Create a worker and Edit it to Paste the Javascript Code you Copied earlier.
- Save and Deploy the worker and copy its URL.

Add in your website:
- Just replace the [form_worker_url](/index.html#L129) in index.html to your cloudflare worker URL and you are good to go!
-
