# My fork attempt for [laylavish's blocklist](https://github.com/laylavish/uBlockOrigin-HUGE-AI-Blocklist) but solely for Brave



## NOTE
TLD ".ai" is blocked ENTIRELY in this fork for efficiency

This ends up blocking Anguilla's ccTLD (country code top-level domain) as they unfortunately share the same domain.

(Sorry Anguilla)


# uBlockOrigin & uBlacklist Huge AI Blocklist
A huge blocklist of manually curated sites (1000+) that contain AI generated content, for the purposes of cleaning Brave Search Engine with uBlock Origin. 


## PC/Desktop installation

### Installing it with uBlock Origin


**Manual Import**

1. Make sure that you have the uBlock Origin Extension for [Firefox](https://addons.mozilla.org/en-US/firefox/addon/ublock-origin/), [Chrome](https://chromewebstore.google.com/detail/ublock-origin/cjpalhdlnbpafiamejdnhcphjbkeiagm), or any browser that supports uBlock Origin

2. Click on the uBlock Origin Extension, and in the bottom right, there is a cog-wheel symbol--named the dashboard. Click it.

3. Once you are in the dashboard, look towards the top. Click on the tab that says "Filter lists".

4. Look towards the bottom, and expand the ```Import``` button.

5. Copy and paste this URL into the dialogue box: 
```
https://raw.githubusercontent.com/N1msi/uBlockOrigin-BraveSearch-AI-Blocklist-/main/brave-list.txt
```

6. Apply changes, and you're set!

<details>
<summary>Here's a video guide on how to do this (click the dropdown to expand) </summary>
<br>

https://github.com/user-attachments/assets/c379a750-53eb-4813-8cea-757f34ab5a2d

</details>

> [!TIP]
> uBlock Origin will automatically refresh the filter list once a day, so you'll always have up-to-date filters.
> If you want to force an update of the filter list, pressing the stopwatch next to the newly added list, then pressing ```Update now``` will achieve that.


> [!IMPORTANT]
> If you find that your imported list isn't working, it may be due to an outdated web browsing session. If you haven't restarted your web browser for a long time, there's a chance the session won't update how it should, meaning importing the list into uBlock Origin or uBlacklist won't function correctly. Try creating a new session by closing <ins>**all**</ins> web browser windows, waiting until all processes are fully closed (4-5 second wait), then re-opening your web browser. That should help; if not, then try clearing your browser's cache.

***

> [!IMPORTANT]
> This may look cumbersome, but all you really need to do is just allow the extension to hit your search engine's locale, for example, `google.fr` or `google.co.uk`. You can go through all of them and allow them, but it's not necessary.

5. Now scroll back up, and hit the blue **Extension Settings** button. It will bring you to Safari and open uBlacklist's settings panel.

6. Scroll all the way down until you see the "Subscription" tab, and click on the blue "Add a subscription" button.

7. Give a name for the added blocklist (eg. Main AI blocklist).
  
8. Copy and paste this url 
```
https://raw.githubusercontent.com/laylavish/uBlockOrigin-HUGE-AI-Blocklist/main/list_uBlacklist.txt
``` 
into the **URL** part of the dialogue box, then press the blue **Add** button.

9. Set the update interval to an hour for near-realtime list updates, and you're done!

### Android (via Firefox)

<details>
<summary>Installation for uBlock Origin (expand) </summary>
<br>

***
