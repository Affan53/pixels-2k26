PIXELS 2K26 – setup
1) Host this folder on HTTPS (Vercel: drag & drop). Share the link; users tap "Download PIXELS" (top right).
2) PINs: edit CFG.PINS in index.html (captain 2626, admin 1234, president 9999). CHANGE THEM before the event.
3) Shared live data on all phones (REQUIRED for a real event): create a free Firebase project -> Realtime Database -> Rules:
   {"rules":{".read":true,".write":true}}  then paste the database URL into CFG.DB in index.html.
   Without CFG.DB every phone only sees its own data.
4) Optional real event photos: put 0.jpg, 1.jpg ... in the images/ folder (number = event order in the list).
