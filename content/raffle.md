---
title: "WIN A LOEWE BAG"
description: "THE GIVEAWAY YOU'VE BEEN WAITING FOR"
layout: "raffle"
sitemap:
  disable: true

params:
  # ══════════════════════════════════════════════════════════════════
  #  1. THE ENTRANTS SPREADSHEET
  #     Paste the "Publish to web → CSV" link for the ENTRANTS sheet.
  #     This sheet holds ticket / first name / date only — contact
  #     details live in a separate, unpublished spreadsheet.
  #     Setup steps are in RAFFLE-SETUP.md.
  #     Leave blank and the page shows a friendly "list coming soon".
  # ══════════════════════════════════════════════════════════════════
  sheetCsvUrl: "https://docs.google.com/spreadsheets/d/e/2PACX-1vSTOzOaFtVzy4ooV4qrI8aJM2sS5I-gMnsYEymNjjUbgPJIMxK6TxQ_QGoetAswwPKJ-213XwhmlMxb/pub?gid=0&single=true&output=csv"

  # Optional: link shown under the list so clients can open the sheet
  # themselves if the live list ever fails to load. Use the entrants
  # sheet's "Publish to web → Web page" link, not the edit link.
  sheetViewUrl: ""

  # ══════════════════════════════════════════════════════════════════
  #  1b. THE LIVE DRAW
  #      staffPasswordHash is the SHA-256 of the staff password.
  #      This has been changed from the shipped default — keep a note of
  #      the password somewhere safe, it can't be recovered from the hash.
  #      To change it again, see RAFFLE-SETUP.md Part 4.
  # ══════════════════════════════════════════════════════════════════
  staffPasswordHash: "2afc56b26c263c4ea0d484ae6b96245d6f09dbd3ed8e8188e1f6d184b0bb27b9"

  # AFTER the draw, put the winner here and redeploy. The page then shows
  # the result permanently to everyone, not just the salon device.
  # Leave both blank until then.
  winnerTicket: ""
  winnerName: ""

  # ══════════════════════════════════════════════════════════════════
  #  2. THE PRIZE
  # ══════════════════════════════════════════════════════════════════
  prizeName: "WIN A LOEWE BAG"
  prizeBlurb: "One lucky Palette Co client is taking it home."
  # Must match the actual prize. Under the Australian Consumer Law a prize
  # description can't misrepresent what's being given away, so name the
  # exact item — and add the colour/size if the bag comes in variants.
  prizeDescription: "One (1) LOEWE Medium Anagram Basket Bag."
  prizeValue: "$1,500"          # retail value — required in the T&Cs
  prizeImage: ""                 # e.g. "/img/raffle-handbag.jpg" — optional

  # ══════════════════════════════════════════════════════════════════
  #  3. THE DATES  (shown on the page and in the T&Cs)
  # ══════════════════════════════════════════════════════════════════
  opensOn: "3 August 2026"
  closesOn: "27 September 2026, 3:00pm AEST"
  drawnOn: "28 September 2026, 12:00pm AEST"
  drawLocation: "Palette Co, 2 Baroona Road, Milton QLD 4064"

  # ══════════════════════════════════════════════════════════════════
  #  4. THE PROMOTER  (required in the T&Cs — put the real legal
  #     entity name and ABN here, not just the trading name)
  # ══════════════════════════════════════════════════════════════════
  promoterName: "Palette Co"
  promoterEntity: "Joyce Jean Polancos trading as Palette Co (ABN 65 705 473 046)"
  promoterAddress: "2 Baroona Road, Milton QLD 4064"

  # ══════════════════════════════════════════════════════════════════
  #  5. HOW TO ENTER
  #     TWO ROUTES, both free of any entry fee:
  #       1. Spend $100+ on services  → desk offers a ticket automatically
  #       2. Ask at the desk          → ticket issued, no purchase needed
  #     The second route is what keeps this a Queensland "free entry
  #     draw". Keep freeEntryNote filled in and visible — emptying it
  #     hides the panel and changes the risk position. See Part 6.
  # ══════════════════════════════════════════════════════════════════
  howToEnter: "Spend $100 or more on services with us during the promotion and we'll add your name to the draw at the desk."
  freeEntryTag: "Open to all"
  freeEntryNote: "Booked in, or just saying hello — ask at the desk any time we're open and your name goes straight in the draw. Every ticket has the same chance."

  # The spend at which the desk offers a ticket without being asked.
  # Keep consistent with howToEnter and with what the desk actually does.
  minimumSpend: "$100"
---
