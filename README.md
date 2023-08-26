<div align="center">
    <a href="https://github.com/weebzone/WZML">
        <kbd>
            <img width="250" src="https://graph.org/file/80f677693ae80cbd8707e.jpg" alt="FZ Bypass Logo">
        </kbd>
    </a>

## ***FZBypassBot***

<i>A **Elegant Fast Multi Threaded Bypass Telegram Bot** for Bigger Deeds like Mass Bypass. Try Now, and Feel the Speedy Work.</i>

[**Demo Bot**](https://t.me/FZBypassBot) | [**Supported Sites**](#supported-sites) | [**Support Group**](https://t.me/FXTorrentz)

</div>

---

## ***Features***
- _Fastest written in Async_
- _Build with Simultaneously Bypass Method_
- _Supported for Authorized Chats & Topics_
- _Added Support for Inline Bypass ( Use anytime anywhere)_
  > **Enable:** BotFather -> Bot Settings -> Inline Mode (Turn On)

---

## ***Supported Sites***
- All `Credits` to Respective Script Owner & Contributors
- All these are Collected from the Internet / Web

| __Websites / Sites__ | __Status__ |
|:--------------------:|:----------:|
|`new9.gdtot.cfd`|✅️|
|`appdrive.club`|✅️|
|`tinyfy.in`|✅️|
|`xpshort.com` + `push.bdnewsx.com` + `techymozo.com`|✅️|
|`gtlinks.me` + `gyanilinks.com`|✅️|
|`droplink.co`|✅️|
|`earn.moneykamalo.com`|✅️|
|`adrinolinks.com`|❌️|
|`krownlinks.me`|✅️|
|`du-link.in`|✅️|
|`link.tnshort.net`|✅️|
|`go.lolshort.tech`|✅️|
|`indianshortner.in`|✅️|
|`rslinks.net`|❌️|
|`m.easysky.in`|❌️|
|`linkbnao.com`|✅️|
|`go.indiurl.in.net`|⚠️|
|`go.earnl.xyz`|⚠️|
|`linkvertise.com`|✅️|
|`link.tnlink.in`|❌️|
|`link4earn.com` + `link4earn.in`|✅️|
|`shortingly.in`|❌️|️
|`go.flashlink.in`|⚠️|
|`short2url.in`|✅️|
|`urlsopen.com`|⚠️|
|`mdisk.pro`|✅️|
|`ouo.io` + `ouo.press`|✅️|
|`shareus.in` + `shareus.io` + `shrs.link`|✅️|
|`dropbox.in`|✅️|
|`disk.yandex.ru` + `yandex.com`|✅️|
|`try2link.com`|✅️|
|`shrdsk.me`|✅️|
|`linkpays.in`|✅️|
|`pkin.me` + `go.paisakamalo.in`|✅️|
|`sklinks.in` + `sklinks.tech`|✅️|
|`link1s.com`|✅️|
|`tulinks.one` + `go.tulinks.online` + `tulinks.online`|✅️|
|`powerlinks.site`|✅️|
|`link.vipurl.in` + `vipurl.in` + `count.vipurl.in`|✅️|
|`v2links.com`|✅️|
|`indyshare.net`|✅️|
|`9qr.de`|✅️|
|`linkyearn.com`|✅️|
|`earn4link.in`|✅️|
|`linksly.co`|✅️|
|`download.mdiskshortner.link`|✅️|
|`shrdsk.me`|️❌️|
|`mediafire.com`|✅️|
|`terabox.*` + `terabox.*` + `nephobox.*` + `4funbox.*` + `mirrobox.*` + `momerybox.*` + `teraboxapp.*`|✅️|
|`hotfile.io` + `bayfiles.com` + `megaupload.nz` + `letsupload.cc` + `filechan.org` + `myfile.is` + `vshare.is` + `rapidshare.nu` + `lolabits.se` + `openload.cc` + `share-online.is` + `upvid.cc`️|⚠️|
|`rocklinks.net`|✅️|
|`More Sites...Updating`|✅️|

### ***Scrape Sites***
| __Websites__ | __Status__ |
|:--------------------:|:----------:|
|`cinevood.*` **(Page)** |✅️|
|`toonworld4all.*` **(Page + Episode)** |✅️|

---

## ***Deploy Guide***
1. `Heroku` _(Recommended)_
    - Use [HK-Loader](https://github.com/SilentDemonSD/HK-Loader) and Follow further Steps.
    - Use Process Type `worker` to run without any Stop.
    - **Variables Values:**
      - `REPO_URL`: https://github.com/SilentDemonSD/FZBypassBot
      - `REPO_BRANCH`: main
      - `START_CMD`: bash start.sh
2. `VPS`
    - **Build And Run The Docker Image Using Official Docker Commands**
        - _Clone the Repository_
            ```
            git clone https://github.com/SilentDemonSD/FZBypassBot && cd FZBypassBot
            ```
        - _Build Docker image:_
            ```
            docker build . -t fzbypass
            ```
        - _Run the image:_
            ```
            docker run fzbypass
            ```
        - _To stop the running image:_
            - Check Running Containers
                ```
                docker ps
                ```
            - Get the ID and Stop the Container
                ```
                docker stop idxxxxx
                ```
    - _Add `sudo` at the Start of Each Command if your CLI is rooted_
    - _Add all Config Data in `config.env`_
    - _Update your Repo Directly, Make sure to fill Up `UPSTREAM_REPO` & `UPSTREAM_BRANCH`_
        ```
        docker restart idxxxxx
        ```

---

## ***Config Setup***
- `BOT_TOKEN`: Telegram Bot Token that you got from BotFather.
- `OWNER_ID`: Telegram User ID (not username) of the Owner of the bot.
- `API_ID`: This is to authenticate your Telegram account for downloading Telegram files. You can get this from https://my.telegram.org.
- `API_HASH`: This is to authenticate your Telegram account for downloading Telegram files. You can get this from https://my.telegram.org.
- `AUTH_CHATS`: Group ID (with Topic ID), Separated by space.
  > **Format:** chat_id:topic_id chat_id chat_id:topic_id
- `GDTOT_CRYPT`: GdToT Crypt (Optional). It works with & without Crypt!
- `TERA_COOKIE`: Get the Terabox `ndus` Cookie from Cookie Editor Extension.
- `UPSTREAM_REPO`: Put Upstream Repo to Update. Defaults to `https://github.com/SilentDemonSD/FZBypassBot`
- `UPSTREAM_BRANCH`: Put Branch Name. Defaults to `main`

---

## ***Credits***
- `SilentDemonSD` (Developer)
- `Link-Bypasser-Bot` (Many Scripts are Taken & Totally Modified)