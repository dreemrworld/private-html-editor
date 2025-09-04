
**🎉 Project Overview**
I have been vocal about the power of cloudflare workers as a fullstack backend with a thin layer of html, css and js frontend. Proof is in the pudding.  

**📍 Live**
Link to the live version: https://chatgoat.dreemrworld.workers.dev


**💾 Installation**
Download the project to your computer and install needed packages with command:

    $ git clone https://github.com/dreemrworld/https://github.com/dreemrworld/private-html-editor
    
	$ cd private-html-editor
    
    $ pnpm install 
        
    $ pnpm dev 
    
    $ pnpm deploy

Thats it!

**🔧 Tech/framework used**

**Front-end**
Single page index.html 

**Back-end**
Cloudflare workers template

    pnpm create cloudflare@latest 
Hello world 
Static website

**Why this stack?**

* **Zero Frontend Dependencies:** No framework runtime. Pure HTML, CSS, and JS mean instant load, no bundle bloat, and no client-side performance tax.

* **Minimal, Native Backend:** No virtual machines, containers, or complex orchestration. Code runs in microsecond-start V8 isolates.

* **Unmatched Cost Efficiency:** You pay only for CPU time (microseconds), not idle time (seconds/minutes). This is orders of magnitude cheaper than Vercel,/AWS/Azure.

* **Global Low Latency:** The entire stack (CDN for assets, Workers for logic) runs on Cloudflare's 300+ global edge locations, ensuring the fastest possible response for every user.

* **Free Tier Leverage:** This architecture consumes minimal resources, allowing even complex-seeming apps to operate entirely within the generous free usage limits.

**Evidence**

    $ pnpm run deploy
    > --hidden--
    > wrangler deploy
    > 
     ⛅️ wrangler 4.33.2 (update available 4.34.0)
    ─────────────────────────────────────────────
    🌀 Building list of assets...
    ✨ Read 1 file from the assets directory --hidden--
    🌀 Starting asset upload...
    No updated asset files to upload. Proceeding with deployment...
    Total Upload: 0.34 KiB / gzip: 0.24 KiB
    Uploaded html-online-viewer (12.31 sec)
    Deployed html-online-viewer triggers (2.75 sec)
      https://html-online-viewer.dreemrworld.workers.dev
    Current Version ID: --hidden--

This stack is a no brainer. 

Special shout out to https://github.com/stefwxters/online-html-viewer/

If you encounter a problem, write to this e-mail address: carlos@goat.africa . 

May the yield be with you. Don't forget to leave a star!
 


