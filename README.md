# Project Brief
Earth-observation satellites such as Landsat, Sentinel and Cartosat produce huge, high-resolution images. Onboard memory, downlink time over ground stations and archive downloads are all limited, so the images must be compressed. But satellite images are used for land-use mapping, agriculture, disaster assessment and planning, so careless compression can destroy the very details people need.

# The Vision
A compression and decompression system that shrinks satellite images while preserving structure and detail. It compares classic codecs (JPEG, JPEG 2000, WebP, AVIF) with learned codecs (neural-network encoder-decoder models) at low, medium and high compression levels, and analyses how each behaves on urban, forest, farmland, water, desert and mountain scenes.

# Overview
Every image travels through the same stages: it is fetched, prepared, encoded into a small file, decoded back, and finally scored. The same pipeline is repeated for every codec and every compression level, so results can be compared fairly.
<img width="1154" height="302" alt="image" src="https://github.com/user-attachments/assets/8fb9ea1b-ff57-44b8-be74-6f4e857bd34a" />
