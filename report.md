## My approach:
1. [CLIP](https://github.com/openai/CLIP) is used for text-to-image comparison
2. [Unicom](https://github.com/OML-Team/open-metric-learning) is used for image-to-image comparison
3. [ffmpeg](https://medium.com/@publiciscommerce/extracting-i-frames-keyframes-from-a-video-using-ffmpeg-cb7f2ae3add1) is used to extract keyframes
4. [ChromaDB](https://www.trychroma.com) is used because I have not found how to store metadata (image filename etc) in FAISS

## Challenges:
1. For some reason text-to-image works bag after moving to ChromaDB :(

## TODO:
1. Try different distances except default cosine distance
2. Fix text-to-image