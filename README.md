# alamo-labs-ai-log
Experimental AI builds at Alamo Labs. Documenting the journey from basic web crawlers to advanced personal agents using Claude,Maple AI, and beyond. Building tools to stack Bitcoin and save time.

# 🧪 Alamo Labs: The Free Crawler Post-Mortem

This is a documentation of the first successful bot build. The goal was simple: Build a functional web crawler for $0 that could pull data for content ideas.

## 🛠 The "Free & Cheap" Stack
- Server: Hostinger VPS (Already owned for web hosting).
- Language: Node.js / JavaScript.
- Library: Playwright (for headless browsing).
- Brain: A "Zero-Cost" implementation using basic scraping logic.

## 🧠 The Reality of the Build
This bot wasn't "impressive" in its output, but it was a massive win in execution. We went back and forth for hours because:
- Permission Issues: Getting the VPS to allow the bot to "talk" to the outside world.
- Hidden Folders: Learning the hard way how Linux hides files (like .env) that the bot needs to run.
- The "Circle" Loop: Figuring out why the bot would start and then immediately go silent without errors.

## ⚠️ Lessons Learned (The Headaches)
1. Free isn't always "Free": You save money, but you pay in time. The amount of troubleshooting we did just to save a few bucks on an API was the first big lesson of Alamo Labs.
2. Context is King: The bot could pull raw information, but without a high-level AI "brain" (like Claude API), the information was just a wall of text that still required manual work.
3. The "CEO Path" vs. The "Hacker Path": This build proved that while you *can* do it for free, sometimes paying for the right API saves your sanity.

## 🗂 Status: ARCHIVED
I am not building this specific crawler out any further. It served its purpose: it proved we could build a bridge between a server and the web. We are moving on to more advanced, stable builds.
