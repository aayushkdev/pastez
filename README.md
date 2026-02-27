# Pastez Bin

A very simple browser-based text editor that stores your text directly in the URL.

No database.  
No backend storage.  
No accounts.  
Just text → compressed → stored in the URL.

---

## What This Does

- You type text in the editor.
- The text is compressed using **Deflate (pako)**.
- The compressed data is encoded safely for URLs.
- It is stored in the URL hash (`#` part).
- When you open the link again, it decompresses automatically.

You can copy the URL and share it.  
Anyone who opens the link will see the same text.

---

## Notes
- Everything is client-side.
- Good for quick sharing of small text snippets.
- No No for large documents and sensitive stuff (yet).

