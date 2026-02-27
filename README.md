# Pastez Bin

A very simple browser-based text and image paste tool that stores everything directly in the URL.

No database.  
No backend storage.  
No accounts.  
Just text → compressed → stored in the URL.

---

## What This Does

- You type text or paste and image in the editor.
- This is then compressed using **Deflate (pako)**.
- The compressed data is encoded safely for URLs.
- It is stored in the URL hash (`#` part).
- When you open the link again, it decompresses automatically.

You can copy the URL and share it.  
Anyone who opens the link will see the same text or image.

---

## Notes
- Everything is client-side.
- Good for quick sharing of small text snippets.
- No No for large files and sensitive stuff.

