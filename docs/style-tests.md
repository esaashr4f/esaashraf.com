# Night Street — style test prompt pack

Run these in Higgsfield (web app, Claude chat or Cowork, where your unlimited
plans work). Goal: compare models and routes before committing to a look.
Run each scene prompt on **every** model below, then pick a winner.

## Models to compare (all on your unlimited list)

| Model | Settings |
|---|---|
| Nano Banana Pro | 2K |
| Nano Banana 2.1 | 2K, thinking: high |
| Seedream 5.0 Pro | 2K |
| GPT Image 2.6 | 2K, quality: high |
| GPT Image 2.5 | 2K, quality: high, variant: sunburst |

## 1. Shared style block

Paste this at the end of every scene prompt.

> Style: an original Japanese shin-hanga woodblock print from the 1920s, crossed with flat cut-paper shapes from a 1960s film title sequence. Flat colour fields with visible woodgrain and paper-fibre texture, carved keyblock outlines, soft bokashi gradation only around light sources. Palette limited to: near-black ink #0b0d14, night sky #141a2e, Prussian blue #1f3a5f, dark plum #2a1830, warm off-white snow #e9e4d8, amber lamplight #f2b45a, and at most one tiny touch of red #b3282d. Light comes only from lamps and windows, never from the sky. Figures are faceless solid silhouettes. Large areas of empty dark space; quiet, lonely but warm. No Japanese text, no temples, no torii, no cherry blossoms, no drop shadows, no glossy 3D rendering, no photorealism.

## 2. Scenes

Use 21:9 for the street and plaza, 16:9 for rooms.

**A. The street (hub)**
> An empty city street at night in falling snow, seen from the side like a stage. A row of low shopfronts and narrow buildings. One lone figure in a long coat, hands in pockets, small in the frame, standing under a single gas street lamp that casts a warm cone onto the snow. Three doorways each have a hand-painted wooden sign: "RECORDS", "GAMES", "PICTURES". Only a few windows are lit. Snow settled on rooftops and ledges.

**B. The record room (Music)**
> A small back room behind a record shop at night, seen through a doorway. An old wooden record player on a low cabinet, lid open, lit by one warm table lamp. Record sleeves leaning against the wall, a chair, a window showing snow falling outside in blue darkness. Almost everything in deep shadow except the pool of lamplight on the turntable.

**C. The games room (Games)**
> A cramped 1990s bedroom at night. An old CRT television on the floor glows faintly, a grey game console with a cartridge sits in front of it, two controllers with cables trailing across the floor. A window behind shows snow and distant lit windows. The CRT screen and one desk lamp are the only light. Generic unbranded hardware, no logos.

**D. The plaza (special game or piece)**
> A vast empty outdoor plaza at night under falling snow, paved stones disappearing into darkness. One street lamp in the far distance, a single bench, a tiny faceless figure at the edge of the light. Enormous empty space above, deep Prussian-blue sky with no moon.

**E. Window iris (transition frame)**
> Close up on one lit window in a dark plum wall at night, snow falling in front. Warm amber light, a faint silhouette of a room inside. Flat and graphic.

## 3. Cut-out pieces (for the interactive parts)

These must be separate so they can move. Use GPT Image 2.6 or 2.5 with **background: transparent**, or Seedream with **remove_bg** on. Add the style block.

- The walker: "a faceless solid near-black silhouette of a person in a long coat, hands in pockets, side view, walking"
- A record sleeve: "a square vinyl record sleeve, flat front view, blank cover in muted plum and blue" (so your own cover art can go on it later)
- A record player, top-down view, with the platter and tonearm drawn as **separate** images
- A game cartridge, front view, blank label

## 4. Animated loops (Seedance)

Take your favourite street frame from section 2 and run it through Seedance 2.0 (std, 720p) as the start image, with audio off:

> Locked-off camera, nothing moves except: snow falling gently at three depths, the street lamp breathing slightly in brightness, one distant window switching off. The figure stands still. Seamless and calm, no camera movement.

Also try one with "very slow sideways camera drift to the right" for the parallax feel.

## 5. Public-domain route (Kiyochika)

Kobayashi Kiyochika died in 1915, and the Art Institute of Chicago marks these
prints public domain (CC0). Download them, then upload each one as an image
reference in Nano Banana Pro or Seedream with the prompt "a new original
night street scene in exactly the style, palette and print texture of the
reference image" plus scene A.

- Matsuchi Hill in Snow at Dusk (1896): https://www.artic.edu/iiif/2/a3626934-8d04-02a7-ca7a-0c9abd741b19/full/1686,/0/default.jpg
- The Moon Beyond Shinagawa (1884): https://www.artic.edu/iiif/2/5285bd18-47ea-3aa9-03bc-a7ce91a67724/full/1686,/0/default.jpg
- Moonlight through the Clouds off the Haneda Coast: https://www.artic.edu/iiif/2/2c3cbd8c-1598-17d1-d162-642950e8cc2f/full/1686,/0/default.jpg

## What to bring back

Save your favourites (and the ones that are almost right) into the repo or
upload them in chat. Note which model made each. Tell me what you love and
what feels wrong; that will decide the art route.
